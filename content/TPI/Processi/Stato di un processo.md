Durante il ciclo di vita di un processo, questo può trovarsi in una certa “situazione” rispetto alla CPU, definita come **stato del processo**.
Lo stato può essere:
- **new**: stato in cui si trova appena creato (quindi appena caricato in RAM)
- **ready**: un processo è nello stato di pronto se ha tutte le risorse necessarie alla sua evoluzione ad eccezione della CPU
- **running**: la CPU sta eseguendo le sue istruzioni, quindi a esso è assegnato il processore
- **waiting**: un processo è in attesa quando gli manca una risorsa per poter evolvere; quindi attende che si verifichi un evento che lo riporti in stato di “ready”
- **terminated**: tutto il codice del processo è stato eseguito e quindi ha terminato l’esecuzione; il SO può rilasciare tutte le risorse che utilizzava

[[Cos'è un processo]]