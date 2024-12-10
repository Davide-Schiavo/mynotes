TORNA ALLA HOME :[[TPI]]
- PAGINAZIONE
    

Il programma è diviso in pagine della stessa dimensione, senza tener conto della distinzione tra area del codice e area dei dati.

- SEGMENTAZIONE
    

Ogni modulo software in cui è stato suddiviso il programma svolge una funzione diversa, a ogni modulo è stata associata parte della memoria centrale di dimensione variabile.

Lo spazio degli indirizzi di un processo è diviso in segmenti logici:

- Un segmento è caricato in un frame di pari dimensione.
    
- I segmenti di un processo possono essere caricati in frame non contigui, quelli non caricati sono conservati sul disco.
    

La traduzione degli indirizzi logici in fisici avviene attraverso la tabella dei segmenti:

- Il numero di segmento è usato come indice della tabella
    

Ogni voce contiene:

- L’indirizzo base di segmento(indirizzo fisico di partenza)
    
- Limite del segmento
    

VANTAGGI SEGMENTAZIONE

- La gestione di strutture dati dinamiche è semplificata
    
- Viene facilitata la condivisione dei segmenti tra alcuni processi
    
- Si semplifica il Linking 
    
- Ogni segmento può avere un diverso tipo di protezione
    

SVANTAGGI SEGMENTAZIONE

- Frazionamento esterno della memoria.