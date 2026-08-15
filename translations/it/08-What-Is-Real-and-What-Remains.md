> Italiano: Traduzione assistita da macchina dell'autorevole fonte inglese. Sono gradite correzioni nella lingua madre. [Inglese](../../README.md) | [Tutte le lingue](../README.md)

# Cosa è reale e cosa resta

![Idee, test, fallimenti e capacità verificate attraversano cancelli di implementazione distinti](../../assets/evidence-implementation-gates.png)

## Classi di prova

Il modello delle prove mantiene distinte diverse classi:

- **evidenza primaria:** artefatti originali preservati ed eventi di interazione;
- **evidenza derivata:** testo estratto, unità semantiche, relazioni, classificazioni,
  osservazioni temporali e altre rappresentazioni con versione;
- **prove di esecuzione:** manifesti, osservazioni delle chiamate, costi, identità del modello e
  risultati di fase;
- **prova di accettazione:** invarianti indipendenti, ricevute, pacchetti promossi e
  hash di output esatti;
- **intento progettuale:** architettura e comportamento pianificato non ancora dimostrati in esecuzione;
- **affermazioni storiche:** ciò che una versione o un esperimento precedente riportava su se stesso.

Il superamento della prova costituisce prova solo per l'involucro che esercita. Un documento di rilascio non è la prova che il runtime corrente lo corrisponda ancora. Una libreria installata non è una funzionalità distribuita.

## Fondazioni implementate

L’implementazione ha dimostrato le seguenti fondazioni limitate:

- conservazione della fonte indirizzata al contenuto e gestione delle prove orientata all'aggiunta;
- artefatti, rappresentazioni, localizzatori ed eventi sorgente separati;
- eventi di conversazione legati ad attori e sequenze;
- preelaborazione del discorso e della coreferenza con porzioni di sorgente delimitate;
- classificazione delle relazioni degli argomenti con intervalli di origine esatti e tentativi mantenuti;
- un grafico di proposizioni e relazioni digitato;
- proiezione deterministica delle dipendenze;
- Contributi della matrice di significato personale nell'ambito della richiesta con incertezza e
  bandiere di protezione;
- selezione all'indietro e oggetti di riproduzione in avanti dello stesso grafico nei test limitati;
- allocazione di unità semantiche di proprietà globale e pianificazione di artefatti interlacciati;
- pavimenti di rendering messi a terra e confronto opzionale dei candidati;
- promozione indipendente con ricevuta di ritorno;
- lavori di artefatti durevoli e un visualizzatore di ragionamento;
- un confine di pubblicazione di documenti pubblici con versioni indirizzate al contenuto.

Queste affermazioni descrivono i limiti dei componenti dimostrati, non un'affermazione che l'intera visione sia completa.

Il confronto dimostrato registra anche un confine con l'ingranaggio esterno. Un modello di frontiera ha ricevuto un payload preparato e specifico per la richiesta e ha contribuito a un rendering più raffinato senza ricevere il corpus mantenuto o diventare autorità di rilascio. Le prove supportano tale transazione limitata; non stabilisce cosa conserva un fornitore al di fuori del percorso degli artefatti testati, che rimane una questione contrattuale e di privacy separata. Stabilisce che il contributo utile non richiedeva il trasferimento del record umano per la riduzione distruttiva in valore di proprietà del fornitore.

## Bilancia a piattaforma installata

Un inventario limitato del filesystem dell'albero dell'applicazione installato contava circa 566.000 file e 218 GiB. Le risorse del modello rappresentavano circa 172 GiB, dipendenze e runtime del linguaggio per 25 GiB, stato dei dati e altre risorse per 20 GiB e origine di implementazione per circa 184 MiB. L'inventario ha rilevato alcune voci illeggibili o modificate, quindi si tratta di stime su scala operativa piuttosto che di una distinta base del software.

L'asimmetria è una prova intenzionale dell'architettura. Il codice sorgente è una piccola parte dell'impronta installata; i pesi dei modelli e i tempi di esecuzione riutilizzabili lo dominano. Il piano di controllo tiene quindi traccia del valore, dell'autorità e del costo operativo di ciascuno specialista anziché considerare le dimensioni installate come una capacità. Una futura versione di codice distribuibile necessita di un inventario delle dipendenze specifico dell'artefatto, versioni esatte, licenze, hash e limiti di build riproducibili.

## Lezioni di ingegneria conservate dalla progettazione

Lo sviluppo ha prodotto diverse lezioni di ingegneria durevoli:

- suggerire un modello generale per simulare uno specialista scomparso;
- trattare l'uscita dal processo o il manifest auto-segnalato come prova di capacità;
- eseguire il discorso secondo una classificazione semantica e duplicare il lavoro specialistico;
- assegnare la prima occorrenza di citazione ripetuta come provenienza;
- consentire a un elemento di prova dell'intero fascicolo di rendere la composizione non verificabile;
- trattare le relazioni zero accettate come fallimento della pipeline;
- confondere una proiezione grafica deterministica con uno specialista eseguito separatamente;
- abbinare un profilo di trama producendo prosa non supportata o illeggibile;
- debugging con esecuzioni dell'intero corpus quando casi di piccole e medie dimensioni hanno evidenziato il difetto;
- mettere a punto un prodotto in modo tale da far regredire un altro.

L’architettura pubblica conserva queste correzioni perché spiegano lo scopo dei vincoli attuali e rendono più affidabili i futuri perfezionamenti.

## Opportunità di sviluppo attuali

Molte delle principali capacità rimangono incomplete o richiedono prove più ampie:

- le etichette relazionali necessitano di una valutazione di qualità da parte di esperti indipendenti, non solo strutturale
  convalida;
- i collegamenti temporali tra depositi incrociati e la riattribuzione necessitano di test continui su livelli più ampi
  confini di fonti miste;
- i driver personali di alto livello devono rimanere non popolati fino a quando non saranno raccolte prove legate alla fonte e
  il comportamento delle lenti li giustifica;
- diverse tipologie di prodotto necessitano di linee di assemblaggio calibrate e protette dalla regressione;
- Il feedback sul protocollo umano necessita di prove di risultati longitudinali;
- I meccanismi figurativi e narrativi richiedono prima una valutazione consapevole del prodotto
  l'autorità è concessa;
- la documentazione pubblica completa richiede una revisione editoriale continua come documentazione privata
  si evolve.

## Scala di convalida

Lo sviluppo procede dal piccolo al grande:

1. schema puro e fissaggi invarianti;
2. brevi esempi semantici con topologia nota;
3. piccole fette di sorgente reale;
4. tranci medi formato misto e tempo misto;
5. limiti di scalabilità più ampi dopo il superamento dei livelli precedenti;
6. confronto creato da esseri umani rispetto a quello generato dal sistema con le stesse prove,
  destinatario, forma e budget.

Il confronto diagnostica se la perdita deriva dalla selezione del grafico, dall’assegnazione dell’importanza, dalla riproduzione in avanti, dalla realizzazione o dalla leggibilità finale piuttosto che assegnare ogni difetto alla generica “qualità del modello”.
