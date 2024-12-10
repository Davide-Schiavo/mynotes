TORNA ALLA HOME :[[TPI]]
- Riduzione della frammentazione della memoria (quantità di memoria non utilizzabile).
    
- Il SO tiene in memoria centrale solo le parti del programma in uso, il resto sul disco.
    
- Caricando solo parte del programma alla volta è possibile eseguire programmi di qualsiasi grandezza.
    

PAGINAZIONE

Gli obbiebbivi sono:

- Mantenere in memoria solo le parti necessarie
    
- Gestire piccoli porzioni di memoria
    
- Non sprecare spazio
    
- Usare porzioni di memoria non contigue per lo stesso programma
    
- Non dare l’incombenza della suddivisione del programma al programmatore.
    

- La memoria fisica viene divisa in blocchi di dimensioni fissa, detti frame o pagine fisiche.
    
- Il programma è diviso in blocchi di uguali dimensioni, detti pagine o pagine logiche.
    
- Il numero di pagine logiche può essere diverso da quello delle pagine fisiche.
    
- Se il numero di pagine logiche è minore, il programma potrebbe essere caricato tutto in memoria, se quelle logiche sono di più il programma viene caricato parzialmente.
    

Il sistema operativo mantiene una tabella delle pagine dove il numero di frame è usato come indice della tabella, nella tabella sono memorizzati:

- Indirizzi fisici iniziali.
    
- Pagina occupata oppure libera.
    
- ID del processo.
    

Per ottenere un indirizzo fisico, ho bisogno di due elementi che vanno sommati(f+ d):

- Numero di pagina fisica (p), utile alla MMU che preleva l’indirizzo fisico(f).
    
- Spiazzamento nella pagina o offset(d).
    

PAGE FAULT si verifica quando durante l’esecuzione di un programma viene fatto riferimento ad un’istruzione che non è presente in alcun frame.
[[paginazione VS segmentazione]]