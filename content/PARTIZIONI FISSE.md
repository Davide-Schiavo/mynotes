Quando si inizializza un sistema vengono stabilite le dimensioni delle partizioni, possono essere diverse tra loro, per ogni partizione c’è una coda che l’attesa dei job, vengono aggiunti nella coda della partizione più piccola che riesce a contenerlo.

PROBLEMI?

I problemi sono :

- Frammentazione esterna : quando un job è più grande di qualsiasi partizione ma potrebbe essere contenuto nella memoria complessiva.
    
- Frammentazione interna: quando abbiamo un job piccolo, tutte le partizioni piccole ma in grado di contenerlo hanno la coda piena, andrebbe nella coda della partizione più grande, causando uno spreco di memoria.
    

Per evitarlo ci fa uso di una singola coda d’ingresso.

- Si percorre la coda dall’inizio fino ad individuare un job che possa essere contenuto nella partizione libera.
    
- Si percorrere tutta la coda, individuando il più grande job che possa essere contenuto nella partizione libera.