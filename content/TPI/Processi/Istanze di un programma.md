E’ possibile avere in esecuzione contemporaneamente più istanze di un programma, ossia più processi originati dallo stesso codice

I processi possono essere:
- **Indipendenti**: un processo può evolvere autonomamente senza necessità di scambiare dati con altri processi
- **Cooperanti**: due o più processi per evolvere necessitano di scambiarsi informazioni (si pensi ad un videogame con due giocatori dove ogni giocatore è un processo: i processi devono coordinarsi, ossia sincronizzarsi, per scambiare informazioni)
- **Competitori**: due processi possono ostacolarsi a vicenda, per usare la medesima risorsa, compromettendo la terminazione delle loro elaborazioni

[[Cos'è un processo]]