# Project plan v1.0

# Indice

[Introduzione](#1-introduzione)

[Modello di processo](#2-modello-di-processo)

[Organizzazione del progetto](#3-organizzazione-del-progetto)

[Standard, linee guida, procedure](#4-standard-linee-guida-procedure)

[Attività di gestione](#5-attività-di-gestione)

[Rischi](#6-rischi)

[Personale](#7-personale)

[Metodi e tecniche](#8-metodi-e-tecniche)

[Garanzia di qualità](#9-garanzia-di-qualità)

[Pacchetti di lavoro](#10-pacchetti-di-lavoro)

[Risorse](#11-risorse)

[Budget e programma](#12-budget-e-programma)

[Cambiamenti](#13-cambiamenti)

[Consegna](#14-consegna)

# Project plan v1.0
# 1. Introduzione
La modellazione e la renderizzazione 3D sono una tecniche fondamentali nel campo della grafica computerizzata, utilizzate per creare rappresentazioni tridimensionali di oggetti, personaggi e ambienti che vengono usati per generare immagini o video realistici di tali oggetti. Questo progetto si propone di esplorare le potenzialità della renderizzazione 3D attraverso la creazione di immagini dettagliate e realistiche partendo dai modelli.
I responsabili sono:
+ Shoeib Yousef 
+ Sergi Annalisa
+ Ferrari Mattia
  
L’obiettivo principale è sviluppare e comprendere i principi fondamentali della geometria, della texture e dell’illuminazione. L’applicazione offrirà all’utente le seguenti funzioni: 
1. **Creazione del modello**:  tramite importazione di file che contengono i dati sui vertici del modello.  
2. **Texturing e Materiali**: applicazione di texture e materiali per aggiungere realismo al modello.
3. **Illuminazione** : configurazione dell’illuminazione come aggiunta di fonti di luce.
4. **Rendering**: rendering finale per ottenere immagini di alta qualità.
# 2. Modello di processo
Adotteremo un modello di processo di tipo agile SCRUM che ci permetterà di gestire lo sviluppo del software in cicli iterativi e incrementali (sprint), di cui si terrà traccia attraverso Jira. Questo approccio ci consentirà di rilasciare versioni funzionali del software a intervalli regolari, migliorando continuamente grazie alle revisioni periodiche . Il team lavorerà in modo collaborativo e autogestito per garantire trasparenza e adattamento continuo durante tutto il ciclo di sviluppo.
# 3. Organizzazione del progetto
Il progetto è realizzato per il corso di ingegneria del software dell’università degli studi di Bergamo e includerà le seguenti fasi:
1. **progettazione iniziale**: in questa fase studieremo i vari requisiti del progetto e definiremo obiettivi e funzionalità che il prodotto finale dovrà offrire all’utente. Verranno inoltre definiti i vari diagrammi UML necessari per la fase di implementazione;
2. **Implementazione**: partendo dai diagrammi definiti nella fase precedente, secondo un modello AGILE (scrum), per ogni sprint sarà definito uno sprint backlog con le varie attività da fare in quello sprint. Attraverso l’uso di una kanban board implementeremo poi le varie funzionalità;
3. **Testing**: il testing verrà fatto alla fine dell’implementazione di ogni gruppo di funzionalità correlate;
4. **Revisione e Ottimizzazione**: in questa fase effettueremo una revisione del modello e miglioreremo le prestazioni e la qualità visiva.
Dal momento che adotteremo un modello AGILE, queste fasi saranno implementate in maniera iterativa e sarà pertanto possibile tornare indietro per effettuare dei cambiamenti (es. aggiunta di nuove funzionalità o miglioramento di quelle già esistenti). 
Il team verrà organizzato usando l’organizzazione SCRUM che prevede di avere un product owner (Shoeib Yousef) e uno scrum master (Sergi Annalisa e Ferrari Mattia si alterneranno ad ogni sprint) 
Oltre ai due ruoli previsti da SCRUM, non è prevista alcuna netta distinzione dei ruoli (data la piccola dimensione del team). Ogni membro del team contribuirà in modo versatile e collaborativo a tutte le fasi del progetto, dalla pianificazione e progettazione, allo sviluppo, test e manutenzione. Questo approccio flessibile favorirà una maggiore coesione del gruppo e permetterà di sfruttare al meglio le competenze individuali, garantendo al contempo una comunicazione efficace e una rapida risoluzione dei problemi.
# 4. Standard, linee guida, procedure
Data la lingua di programmazione scelta (Java), il progetto segue gli standard di Oracle, garantendo conformità alle best practice e alle linee guida ufficiali per lo sviluppo in Java. 
Ogni settimana, il team parteciperà a un incontro di aggiornamento (Daily Scrum) per discutere lo stato di avanzamento delle attività assegnate, identificare eventuali problematiche e pianificare le azioni correttive necessarie. Durante questi incontri, i membri del team collaboreranno per risolvere i problemi e riassegnare i compiti in base alle esigenze del progetto.

# 5. Attività di gestione
Le varie attività del progetto saranno gestite attraverso l’utilizzo di strumenti quali la     kanban board (messa a disposizione da github), che verrà usata per tener traccia in tempo reale dello stato di avanzamento del progetto, e Jira, che supporterà la gestione dei backlog, la pianificazione degli sprint e il monitoraggio delle attività. Questi strumenti ci permetteranno di visualizzare chiaramente le priorità, le dipendenze e i progressi, facilitando la collaborazione e la comunicazione all'interno del  nostro team. Ogni sprint sarà quindi ben organizzato e le revisioni periodiche ci aiuteranno a migliorare il nostro processo di sviluppo.  

# 6. Rischi
Essendo un progetto di grande portata, il rischio è quello di non avere il tempo di raggiungere tutti gli obiettivi prefissati. Per questo motivo, il progetto sarà diviso in fasi. Ci concentreremo sul produrre un MVP (Minimum Viable Product), quindi la prima fase sarà la creazione del renderer con le sue funzionalità di base, alle quali saranno aggiunte altre funzionalità e ottimizzazioni nelle fasi/iterazioni successive. In seguito, verranno aggiunte altre funzionalità di mesh editing.

# 7. Personale
Il team seguirà l’organizzazione SCRUM, che prevede di avere un product owner e uno scrum master. Oltre ai due ruoli previsti da SCRUM non è prevista una divisione rigida dei ruoli quindi adotteremo un approccio completamente collaborativo sia durante la fase di raccolta dei dati sia durante quella di stesura dei documenti. Ognuno di noi raccoglierà dati in modo indipendente, ma successivamente ci confronteremo in sessioni di lavoro di gruppo per analizzare insieme le informazioni e valutarne l’utilità rispetto agli obiettivi del progetto. Anche la stesura dei documenti avverrà attraverso sessioni condivise in modo da garantire una coerenza complessiva nel risultato finale. Questo approccio ci permetterà di avere una visione comune, completa e chiara a tutti riguardo gli obiettivi del progetto.

# 8. Metodi e tecniche

## 8.1 Ingegneria dei requisiti 
Per l’elicitazione dei requisiti adotteremo i seguenti metodi:
+ **Derivazione da sistema esistente (blender)**: usando blender come esempio, identificheremo le funzionalità che il programma deve avere;
+ **Analisi basata su scenario**
I requisiti verranno poi inseriti nel product backlog, da cui verranno estratti e  successivamente eseguiti i task con priorità più alta. 

## 8.2 Gestione versioni
Le versioni verranno rilasciate usando la release di GitHub. In caso di bug è prevista l’apertura di un issue con la successiva creazione di un branch per la risoluzione del bug e il testing. Se i test sono superati, si procede con il merge e il rilascio di una nuova versione stabile.
La numerazione delle versioni partirà da V1.0, dove il primo numero si incrementa solo al rilascio di funzionalità completamente nuove, mentre il secondo si incrementa per i rilasci di bugfix e ottimizzazioni.

## 8.3 Test
Sono previsti dei test con Junit che dipendono dalle funzionalità. Verranno anche create delle scene di prova delle quali si farà il rendering dopo l’aggiunta delle funzionalità per assicurarsi che il programma rispetti ancora i requisiti. Data la natura grafica del progetto, l’ispezione del risultato finale sarà fatta direttamente da una persona ”in modo visivo”.

# 9. Garanzia di qualità
Per garantire che il progetto soddisfi le aspettative, implementeremo una serie di casi di test utilizzando JUnit per il codice Java. Questi test mirano a identificare errori e bug significativi, concentrandosi principalmente sul rilevamento degli errori e sul controllo del sistema. In particolare, grazie a  Junit verificheremo le singole unità di codice per assicurare che ogni componente funzioni correttamente in isolamento, e utilizzeremo test automatizzati per garantire la copertura completa del codice. 

# 10. Pacchetti di lavoro
È prevista una divisione del codice in pacchetti in base alle funzioni svolte:
+ **Oggetti di scena**: gestisce la creazione e la manipolazione degli oggetti presenti nella scena, come modelli 3D, texture e materiali;
+ **Renderer**: si occupa del rendering della scena, trasformando i dati degli oggetti in immagini visibili sullo schermo;
+ **Luci**: controlla le sorgenti di luce nella scena, inclusi tipi di luce, intensità, colore e ombre;
+ **Materiali**: contiene i tipi e le caratteristiche dei vari materiali di cui gli oggetti possono essere fatti;
+ **Risorse**: contiene i vari asset grafici che servono per il rendering della scena;
+ **Camera (punto di vista)**: gestisce la posizione e l'orientamento della camera, determinando il punto di vista da cui viene visualizzata la scena;
+ **GUI**: gestisce l'interfaccia utente grafica, inclusi pulsanti, menu e altri elementi interattivi;
+ **Scena**: contiene tutti gli elementi della scena, inclusi oggetti, luci e camera, e gestisce la logica della scena stessa;
+ **Main**: contiene il punto d’ingresso principale del programma, avviando e coordinando l'esecuzione del software;
+ **Utils**: include funzioni di utilità generali e strumenti per il caricamento di file, come modelli 3D e texture.
+ **Test**: contiene i vari classi con i test case previsti per verificare il corretto funzionamento del codice
# 11. Risorse
La grafica 3D è un'attività molto intensa dal punto di vista computazionale quindi è previsto l’uso di un pc con scheda grafica dedicata.
Per imparare a usare OpenGL, sono stati utilizzati anche i tutorial disponibili al link:  https://learnopengl.com/Introduction. 
Altre risorse necessarie per lo sviluppo di questo software includono:
+ Libreria grafica: LWJGL (Lightweight Java Game Library), una libreria open-source che fornisce accesso a diverse API native per lo sviluppo di applicazioni grafiche, audio e di calcolo parallelo in Java. ;
+ GitHub per il controllo delle versioni e la collaborazione;
+ Jira per tenere traccia del lavoro, registrare le ore e la Kanban board con le funzionalità da mettere 

# 12. Budget e programma
Si terrà traccia delle ore svolte da ciascun membro del gruppo tramite Jira. Questo ci permetterà non solo di monitorare il tempo in modo da poter stimare il carico di lavoro ma anche di gestire le varie scadenze, individuando quali sono le problematiche riscontrate che causano rallentamenti. 

# 13. Cambiamenti
Eventuali modifiche verranno implementate usando GitHub e Jira  in modo controllato e sistematico al fine di ridurre al minimo i rischi di malfunzionamento o di degrado delle prestazioni del software. Dapprima identificheremo le richieste di modifica; successivamente verrà valutato l'impatto che queste avranno sull’intero progetto. Sulla base di ciò, considereremo o meno la loro approvazione, a cui seguirà l’implementazione in un nuovo branch. Infine, la revisione post-implementazione ci permetterà di osservare i risultati del cambiamento rispetto agli obiettivi iniziali, verificando se il cambiamento ha prodotto i benefici attesi e se è allineato con la strategia generale e in caso di esito positivo si unisce il nuovo branch al main. Il Jira Service Management sarà di grande aiuto in quest’ultima fase, poiché identificherà facilmente le aree di miglioramento e permetterà di documentare i risultati ottenuti. 
	
# 14. Consegna
 Le modalità di consegna prevedono la condivisione del project plan, del progetto e della relativa documentazione con il professore Angelo Gargantini e con l’esercitatrice Silvia Bonfanti tramite una repository su github. Tutta la documentazione sarà organizzata in unico file che avrà quattro sezioni: 
+ **gestione del progetto**: in cui verrà indicato il tipo di processo seguito effettivamente, come il gruppo ha usato gli strumenti indicati nel project plan e il tipo di organizzazione seguita dal gruppo stesso; 
+ **requisiti**: verrà qui delineato come sono stati elicitati i vari requisiti del progetto;  
+ **design e architettura**: in cui verranno inseriti i diagrammi affrontati durante l’intero corso ossia use case diagram, class diagram, state machine diagram, sequence diagram, communication diagram, activity diagram e component diagram con il progetto Papyrus contente i vari diagrammi, due design pattern e misurazione con Stan4j;
+ **testing**: il quale specificherà i casi di test e le misure di copertura; 
+ **maintenance**: dove verranno indicate eventuali attività di refactoring o reverse engineering.  
È prevista inoltre la consegna di una presentazione che illustrerà ciò che è stato affrontato dal gruppo.
  
