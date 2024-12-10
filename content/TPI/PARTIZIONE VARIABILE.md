TORNA ALLA HOME :[[TPI]]
È possibile modificare dinamicamente sia il numero sia la dimensione delle partizioni presenti.

Strategie di allocazione dinamica della memoria centrale(Utilizzabili anche per partizioni fisse):

- First fit: è il metodo più veloce, il gestore della memoria scorre la tabella delle partizioni finché non ne trova una abbastanza grande per contenere il processo.
    
- Best fit:  il gestore della memoria scorre la tabella delle partizioni finché non trova la partizione più piccola che riesce a contenere il processo. È più lenta della First fit e tende a lasciare piccoli spazi di memoria liberi numeri, ,inutilizzabili.
    
- Worst fit : sceglie la zona  libera più grande.
    
- Next fit : cerca il primo spazio libero in grado di accogliere il processo partendo dallo spazio libero successivo all’ultimo processo allocato.
    

Il partizionamento dinamico è soggetto a frammentazione esterna, una possibile soluzione è quella di spostare periodicamente i processi all’interno della RAM così da ricompattare le aree di memoria libere.