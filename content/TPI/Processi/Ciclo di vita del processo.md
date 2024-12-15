Quando è creato un nuovo processo, gli viene assegnato un **identificatore** (PID, Process Identifier) e viene inserito nell’elenco dei processi pronti (RL, Ready List)

Quando viene eseguito e caricato sul processore può uscire per tre motivi:
- **termina la sua esecuzione**, cioè il processo esaurisce il suo codice e quindi finisce
- **termina il suo tempo di CPU**, cioè il quanto di tempo a sua disposizione, e quindi ritorna nella lista dei processi pronti RL
- **manca la disponibilità di una risorsa**: per poter evolvere necessita di una risorsa al momento non disponibile e quindi il processo si sospende e passa nello stato di attesa formando la waiting list (WL)

[[Cos'è un processo]]