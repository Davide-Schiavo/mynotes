# ATTIVITÀ 1

- ## Passo 1: Creazione dei file e delle directory
    
Utilizzo il comando mkdir e touch  per creare le directory e i file.

- ## Passo 2: Proprietari e permessi
    

Per visualizzare i proprietari e i permessi dei file e delle directory, utilizza il comando ls -l.

- ## Passo 3: Verifica file nascosti
    

Per verificare la presenza di file nascosti nella directory utilizza il comando ls-l  /tmp.

- ## Passo 4: Modifica permessi directory priv-dir
    

Per impedire al gruppo e agli altri di accedere in lettura ed esecuzione alla directory priv-dir: 

chmod 700 /tmp/priv-dir

- ## Passo 5: Modifica permessi directory pub-dir e file priv-file
    

chmod 707 /tmp/pub-dir

chmod 600 /tmp/priv-dir/priv-file

- ## Passo 6: Modifica permessi file pub-file
    

chmod 666 /tmp/pub-dir/pub-file

- ## Passo 7: Creazione file bash test.sh
    

Crea un file con il comando:

echo date > /tmp/”nome file”

  

- ## Passo 8: Esecuzione file bash test.sh
    

chmod +x /tmp/”nome file”

/tmp/”nome file”