Questa tecnica ibrida di gestione della memoria prende il meglio delle precedenti proposte:

Paginazione:
- identificazione dei frame liberi attraverso i bit di validità
- scelta del frame libero, non necessariamente contiguo, in cui caricare una pagina, quindi senza alcuna frammentazione

Segmentazione:
- verifica degli accessi e delle operazioni
- condivisione di porzioni di memoria

La memoria centrale fisica è divisa in pagine fisiche (frame) di dimensione fissa.
Lo spazio di indirizzamento del processo è suddiviso in segmenti logici (segmenti) di dimensioni diverse, ciascuno suddiviso in pagine logiche.
I segmenti contengono informazioni di tipo diverso, mentre le pagine di cui sono costituiti sono porzioni indifferenziate del loro spazio di indirizzamento.
I frame hanno la stessa dimensione delle pagine logiche, che infatti vengono caricate in essi.

[[Memoria Virtuale]]
