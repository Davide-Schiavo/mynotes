Un programma, prima di essere caricato in memoria centrale, viene inserito in una coda di ingresso e poi trasferito in una Reading List (RL). Il compilatore e il linker stabiliscono i collegamenti tra istruzioni e indirizzi logici, che diventeranno indirizzi fisici al momento del caricamento. Questo tipo di codice è definito rilocabile.

- Durante la fase di caricamento in memoria, tutti i riferimenti del programma sono sommati a un indirizzo base, in un processo chiamato rilocazione statica. 
    
- Durante l’esecuzione, invece, si utilizza un registro base che contiene l’indirizzo della prima posizione di memoria centrale; si calcola l’indirizzo assoluto sommando a ogni indirizzo relativo il registro base, in una tecnica chiamata rilocazione dinamica.
    

MMU (MEMORY MANAGEMENT UNIT)

È un dispositivo hardware che associa gli indirizzi virtuali a quelli fisici.

Linking e Binding

- Linking consiste nel modo di calcolare un indirizzo logico.
    
- Binding trasformare un indirizzo logico in fisico, ci sono tre modi:
    

- Indirizzamento assoluto : durante la compilazione.
    
- Rilocazione statica : nel momento del loading del programma.

Per caricare un programma in memoria centrale lo spazio libero deve essere :

- SUFFICIENTEMENTE GRANDE
    
- CONTIGUO
    

Oggi ci sono programmi anche più grandi della RAM del computer , quindi delle soluzioni sono:

- Scaricare i processi inattivi della RAM sul disco, detto operazione di Swapping.
    
- Caricamento dinamico, caricare in RAM alcuni moduli , solo nel momento dell’effettivo richiesta.
    
- Effettuare un frazionamento del programma, Overlay.
    
- Partizione della memoria: soluzione migliore; a ogni processo si lascia una porzione di memoria fissa di memoria per eseguire lo Swapping, riducendo la frammentazione

[[PARTIZIONI FISSE]]
[[PARTIZIONE VARIABILE]]
