La **memoria fisica** viene suddivisa in blocchi di dimensione fissa detti **frame** o **pagine fisiche**.
Il **programma** è suddiviso in blocchi di uguale dimensione detti **pagine** o pagine logiche.

Il numero di pagine logiche può differire dal numero di pagine fisiche.
Per eseguire un programma, all’atto del caricamento iniziale, serve che nella memoria fisica venga caricata la prima pagina logica contenente la prima istruzione da eseguire. Quindi è sufficiente che nella memoria fisica sia libera una sola pagina.

Il SO mantiene una tabella delle pagine dove il numero di frame è usato come indice della tabella. 
Nella tabella sono memorizzate:
- indirizzi fisici iniziali di tutti i frame presenti nella memoria fisica
- indicazione di pagina occupata / libera
- eventuale ID del processo caricato

[[Memoria Virtuale]]
