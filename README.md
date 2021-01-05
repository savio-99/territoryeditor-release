# Territory Editor - Gestione dei registri dei territori

## Installazione e Requisiti
Per installarlo basterà, dal menu release, scaricare l'installer. Il programma non necessita di librerie aggiuntive 
o programmi di terze parti. Però per poterlo utilizzare sono necessarie queste caratteristiche:
 - OS: Windows (x64)
 - RAM: Min 2Gb, Cons 4Gb
 - CPU: Min i3 e corrispettiva AMD, Cons i5 e corrispettiva AMD
 - HDD: Min 500Mb, poi in base al numero dei territori (circa 1Mb-2Mb a territorio)
 - DISPLAY: Min HD per utilizzo solo per registri, Min FullHD per la creazione di cartine

## Primo avvio
All'avvio del software verrà prima di tutto richiesto di selezionare la cartella dove il programma dovrà operare. E' 
preferibile selezionare una cartella in cloud, in questo modo tutti i dispositivi con la cartella sincronizzata e 
il programma installato potranno lavorare sugli stessi documenti. 
Dopo la richiesta della cartella, verrà richiesto l'inserimento precauzionale del file S-13.pdf. Questo files è 
necessario per il funzionamento del programma. Se non inserito il programma si chiuderà. Dopo il corretto 
inserimento e caricamento verranno generate diverse cartelle e files.
Le cartelle generate saranno:
 - Registri territori: Al suo interno saranno presenti i PDF dei registri territori. (S-13.pdf)
 - Cartine: Cartella che contiene le cartine dei territori generate tramite app
 - Layout: Cartella contenente i latout finali dei territori inviabili agli utenti
 - settings.dat: E' un file contenente i dati di impostazione dell'applicazione. Al suo interno contiene l'elenco 
   dei nomi dei proclamatori. Questo files non sarebbe da modificare per evitare di perdere tutti i dati 
   dell'applicazione.

## Utilizzo delle varie schede

### Registri
In questa scheda si gestiranno le registrazioni di assegnazione o ritiro dei vari territori. Le modifiche in questa 
sezione non sono a sincronizzazione istantanea, perciò si consiglia di evitare di modificare le assegnazioni con due 
dispositivi contemporaneamente, anche se su comuni diversi.
L'interfaccia di questa sezione è composta da:
 - In alto un menu a tendina che permette di selezionare il comune dove si desidera effettuare i cambiamenti.
 - A sinistra l'elenco dei territori nel rispettivo comune, bisogna selezionare dall'elenco il territorio che si 
   desidera modificare.
 - Al centro lo storico delle varie assegnazioni
 - A destra il pannello per inserire o modificare l'ultima assegnazione sopra, mentre sotto il pannello per 
   modificare una assegnazione precedente.
   
### Statistiche
In questa sezione il programma, una volta inserita la data in cui iniziano le registrazioni dei territori, la data 
dell'ultima visita del CO (Sorvegliante), ed eventualmente la data di inizio e fine di una campagna, calcola tutte 
le statistiche di percorrenza e lavorazione di ogni comune e calcola anche i totali.

### Proclamatori
In questa sezione vedi l'elenco dei proclamatori che ha almeno un territorio assegnato. Si visualizzarà quali e 
quanti territori possiede attualmente.

### Scadenze
In questa sezione si visualizzerano i territori che dovrebbero essere consegnati a breve. Si visualizzerà il 
proclamatore che ce l'ha in mano, da quanti giorni e l'urgenza:
 - Bassa: Da 60 a 90 giorni (2-3 mesi)
 - Media: Da 90 a 120 giorni (3-4 mesi)
 - Alta: Più di 120 giorni (4 mesi o più)

### Cartine
Questa sezione permette di gestire le cartine per comune e l'inserimento di nuove. Per inserire una nuova cartina si 
dovrà:
 1. Abilitare la propria connessione ad internet e selezionare il comune e il territorio obbiettivo
 1. Cliccare sul tasto "Sostituisci cartina"
 1. Utilizzare il browser per navigare nella posizione desiderata per la modifica. Per maggiore precisione si potrà 
    premere "Shift" e con il tasto Sx del mouse selezionare l'area desiderata. Infine premere avanti.
 1. Utilizzare i vari strumenti per creare il territorio che si desidera. Infine premere fine.

### Layouts
In questa sezione si possono generare i PDF finiti dei territori. Per farlo basterà selezionare il giusto comune e territorio con cartina e premere il tasto "Genera PDF". Per ora c'è un solo design possibile di PDF, successivamente verranno inseriti diversi layout.

### Impostazioni
In quest'area è possibile gestire i proclamatori (Aggiungere, Rimuovere o Rinominare) e i vari territori (Aggiungere 
o Rimuovere un comune, Aggiungere un territorio nel comune).
La rimozione di un proclamatore dalle impostazioni NON ne comporta la rimozione anche sui registri, verrà solamente 
rimosso dal menù di selezione nella scheda Registri, quando si vorrà assegnare un territorio.
La rimozione di un comune è annullabile, infatti quando il programma elimina il comune non fa altro che rinominare 
il pdf nella cartella "Registri territori" in un formato .old. Per annullarla basterà rinominare il file in .pdf e 
riavviare il programma. Altrimenti se si vuole completare la rimozione basterà eliminare il file .old, senza 
possibilità di ripristino.

## Informazioni ulteriori
In caso si voglia inserire una nuova funzione o si voglia segnalare un problema si consiglia di scriverlo nella sezione "Issues" di questa pagina. E' preferibile, nel descrivere il problema o la funzione che si desidera richiedere, inserire queste informazioni:
 - Versione applicazione installata
 - Operazione effettuata
 - Cosa ci si aspetta dall'operazione
 - Cosa in realtà è successo nell'applicazione
###
Ad ogni segnalazione verrà assegnatio un livello di urgenza. Può essere che passi diverso tempo prima che siano aggiunte funzionalità non necessarie a tutti gli utenti. Ricordo inoltre che questo programma è in fase di sviluppo e non è completo.
