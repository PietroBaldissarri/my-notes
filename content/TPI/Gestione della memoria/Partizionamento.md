**Partizione fissa**

All’atto dell’inizializzazione del sistema, staticamente viene stabilita la dimensione delle partizioni e viene creata una tabella che memorizza lo stato delle partizioni, indicando quali sono libere e quali occupate.
Le partizioni possono anche essere di dimensione diversa. Per ogni partizione viene gestita una coda dei processi in attesa in base alle loro dimensioni: un nuovo job viene aggiunto alla coda della partizione più piccola che è in grado di contenerlo.

**Partizione variabile**

È possibile modificare dinamicamente sia il numero sia la dimensione di ogni singola partizione, ad esempio unendo blocchi contigui precedentemente distinti o suddividendone uno particolarmente sovradimensionato, a seconda delle richieste di spazio all’atto del caricamento dei processi.
Strategie di allocazione dinamica della memoria centrale:
- **First-fit**: il gestore della memoria scandisce la tabella delle partizioni finché trova la prima zona libera abbastanza grande per contenere il processo. Metodo più veloce
- **Best-fit**: il gestore della memoria scandisce tutta la tabella delle partizioni e sceglie la zona libera più piccola sufficientemente grande da contenere il processo. Metodo più lento del first-fit e tende a lasciare zone di memoria troppo piccole per essere usate
- **Worst-fit**: sceglie la zona libera più grande
- **Next-fit**: cerca il primo spazio libero in grado di accogliere il processo partendo dallo spazio libero successivo all’ultimo processo allocato. Questo evita di allocare i processi tutti all’inizio della RAM

[[Gestione della Memoria]]

