Il compilatore genera gli indirizzi ipotizzando che il programma venga caricato nella memoria a partire dalla cella 0 e in base a questo valore vengono generati tutti gli indirizzi e i collegamenti dati/istruzioni.

Possono essere generati in due modi diversi:
- **Rilocazione Statica**: all’atto del caricamento in memoria, viene individuato l’indirizzo iniziale (indirizzo base) e viene sommato a tutti i riferimenti presenti nel programma (offset)
- **Rilocazione DInamica**: In fase di esecuzione del programma, viene inserito in apposito registro (registro base) il valore dell’indirizzo effettivo della prima locazione di memoria centrale; quindi durante l’esecuzione, istruzione per istruzione, si calcola l’indirizzo assoluto sommando a ogni indirizzo relativo il contenuto del registro base

[[Gestione della Memoria]]
