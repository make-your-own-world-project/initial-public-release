> Italiano: Traduzione assistita da macchina dell'autorevole fonte inglese. Sono gradite correzioni nella lingua madre. [Inglese](../../README.md) | [Tutte le lingue](../README.md)

# Dare credito e restituire valore

![Percorsi di conoscenza attribuiti che restituiscono utili mappe pubbliche senza cancellarne le fonti](../../assets/publish-reciprocity-open-paths.png)

Il sistema è stato assemblato indipendentemente da hardware in gran parte di seconda mano, risorse personali e sforzi sostanziali al di fuori dell'occupazione. Le sue fondamenta intellettuali provenivano da persone e istituzioni disposte a pubblicare lavori che altri potessero ispezionare, testare, adattare entro i suoi termini, criticare e su cui basarsi. L'attribuzione registra quindi sia una discendenza tecnica sia un obbligo reciproco: l'opera pubblica ha reso possibile l'opera, e l'edizione pubblica restituisce i suoi reperti circoscritti senza rivendicare la proprietà dei contesti che li hanno prodotti.

## Perché esiste questo registro

Il lavoro non potrebbe esistere senza persone che scelgono di pubblicare ricerche, scrivere e mantenere software, preservare opere culturali, tradurre testi, curare corpora, gestire archivi e rendere il proprio lavoro disponibile per il riutilizzo o lo studio. La loro decisione di condividere è un esercizio di sovranità. La disponibilità pubblica non rende il loro contributo anonimo o senza proprietario.

Il registro registra i principali contributi utilizzati nell'architettura pubblica. Indica cosa ha fornito ciascuna fonte, come è stato utilizzato e la relazione tra la fonte e questo progetto. Le categorie sono importanti:

- **dipendenza attiva** significa che il software o il modello viene eseguito in un percorso corrente;
- **metodo adattato** significa che un'implementazione utilizza un meccanismo pubblicato senza
  rivendicare il codice originale come autore del progetto;
- **fonte di calibrazione** significa che il materiale è stato misurato e non riprodotto in pubblico
  pubblicazione;
- **influenza del design** significa che l'opera ha cambiato una decisione architettonica;
- **valutato o rifiutato** preserva il credito e il risultato di un esperimento senza
  implicando l'adozione.

Nessuna voce implica che i suoi autori, manutentori, comunità, editori, archivi o istituzioni approvino questo progetto. Questo ZIP di documentazione non ridistribuisce alcun codice, peso del modello, testo del set di dati o testo dell'articolo.

## Fondamenti letterari, linguistici e comunicativi

| Contributo | Fonte pubblica o opera identificativa | Cosa contribuisce qui | Relazione |
|---|---|---|---|
| Carlota S. Smith | *Modi del discorso: la struttura locale dei testi* | Distinzioni grammaticali tra modalità discorsive; supporta l'analisi della consegna digitata. | Influenza del design |
| M. A. K. Halliday e Ruqaiya Hasan | *Coesione in inglese* | Separa la coesione superficiale dalla coerenza effettiva. | Influenza del progetto e basi di misurazione |
| M. A. K. Halliday | Registrati come campo, tenore e modo | Tratta il pubblico e la situazione comunicativa come dimensioni misurate piuttosto che come decorazione immediata. | Influenza del design |
| Douglas Biber | *Variazioni tra parlato e scrittura* | Analisi dei registri multidimensionali utilizzando caratteristiche osservabili co-occorrenti. | Lignaggio della misurazione della trama |
| William Mann e Sandra Thompson | Teoria della struttura retorica | Relazioni del discorso, nuclearità e distinzione tra materiale centrale e di supporto. | Lignaggio specialistico attivo |
| Giovanni Swales | *Analisi del genere* | Mosse e passaggi retorici utilizzati per descrivere la struttura del prodotto. | Linea prodotto-contratto |
| Gérard Genette e la tradizione formalista russa | *Discorso narrativo*; fabula e sjuzhet | Separa il materiale dell'evento dall'ordine e dal punto di vista del suo racconto. | Influenza narrativa e ricostruttiva |
| HP Grice | “Logica e conversazione” | Massime cooperative e differenza tra violazione deliberata e violazione accidentale. | Protocollo umano e progettazione del rilevatore |
| Douglas Walton | Schemi argomentativi e domande critiche | Fornisce modelli di sfida ispezionabili anziché un punteggio di argomento opaco. | Influenza dell'analisi degli argomenti |
| Alexandra Aikhenvald | *Evidenzialità* | Tratta la marcatura delle fonti e delle prove come una responsabilità linguistica. | Influenza del ruolo epistemico |
| Claude Shannon | “Una teoria matematica della comunicazione” | Fornisce il vocabolario della comunicazione formale per informazioni, limiti di canale, ridondanza e perdita. | Influenza dell'architettura della comunicazione |
| Herbert Clark e Susan Haviland | Dato-nuovo contratto | Supporta la misurazione di ciò che si presume sappia un ricevente e di ciò che deve essere introdotto. | Lignaggio della misurazione della trama |
| Morton Ann Gernsbacher | Quadro di costruzione della struttura | Supporta l'istituzione, la mappatura e l'analisi di coerenza orientate al destinatario. | Influenza del protocollo umano |
| Beniamino Bloom; Lorin Anderson e David Krathwohl | Tassonomie degli obiettivi didattici | Fornisce un vocabolario esplicitamente delimitato per la profondità attesa del ricevitore. | Influenza del contratto di pubblico |

Questi lavori fornivano metodi e domande, non risposte universali su una persona. Il contributo architettonico è quello di collegare i loro meccanismi limitati a una catena di montaggio che preservi la provenienza e di mantenere ogni inferenza reversibile e ispezionabile.

## Selezione, editing e realizzazione

| Contributo | Fonte pubblica | Cosa contribuisce qui | Relazione |
|---|---|---|---|
| Jaime Carbonell e Jade Goldstein | "L'uso dell'MMR, riclassificazione basata sulla diversità per riordinare i documenti e produrre riepiloghi" | Bilancia pertinenza e novità durante la selezione limitata. | Metodo adattato |
| Hui Lin e Jeff Bilmes | Riepilogo submodulare sotto budget | Selezione a rendimento decrescente con un budget esplicito. | Metodo adattato |
| Eric Malmi, Sebastian Krause, Sascha Rothe, Daniil Mirylenka e Aliaksei Severyn | Laser Tagger | Dimostra la modifica vincolata con un vocabolario di inserimento chiuso. | Influenza del design valutato |
| Kostiantyn Omelianchuk, Vitaliy Atrasevych, Artem Chernodub e Oleksandr Skurzhanskyi | GETTOR | Dimostra le trasformazioni con tag e la correzione iterativa. | Influenza del design valutato |
| Jonathan Mallinson, Jakub Adamek, Eric Malmi e Aliaksei Severyn | ModificaT5 | Dimostra il riordino basato su puntatori che limita l'invenzione. | Influenza del design valutato |
| Eric Malmi e collaboratori; la più ampia comunità di realizzazione della superficie | Lavoro di realizzazione basato sulla grammatica, da grafico a testo e vincolato | Rafforza la separazione tra determinazione, pianificazione, realizzazione e verifica del contenuto. | Influenza dell'architettura; nessuna adozione generale del runtime |

## Specialisti del ragionamento, del discorso e della verifica

| Contributo | Fonte pubblica | Cosa contribuisce qui | Relazione |
|---|---|---|---|
| Collaboratori di Elena Chistova e IsaNLP | [Scheda modello IsaNLP RST Parser v3](https://huggingface.co/tchewik/isanlp_rst_v3)e il suo lavoro ACL citato; record della scheda modello CC BY-NC 4.0 | Produce strutture discorsive limitate e candidati a relazioni. Non determina il significato personale. | Specialista attivo; il modello viene utilizzato entro i limiti della licenza non commerciale e non ridistribuito qui |
| Shon Otmazgin, Arie Cattan, Yoav Goldberg e collaboratori di FastCoref | [Documento F-COREF e implementazione ufficiale](https://github.com/shon-otmazgin/fastcoref), MIT | Produce catene di coreferenza candidate per la successiva convalida associata all'origine. | Specialista attivo |
| Chris Reed, il gruppo ARG-tech, collaboratori di AIF/xAIF e collaboratori di AMF/ARI | [oRegistro del modulo AMF](https://github.com/arg-tech/oAMF),[Set di dati AIF e registro dei modelli](https://github.com/arg-tech/aif-arg-datasets)e specifiche collegate | Classifica le relazioni tra proposizioni limitate e fornisce un vocabolario interoperabile con grafi di argomenti. | AMF/ARI è un lignaggio specialistico attivo; oAMF è stato valutato come tecnica nota di orchestrazione piuttosto che come adozione su larga scala |
| Liyan Tang, Philippe Laban e Greg Durrett | [MiniCheck](https://aclanthology.org/2024.emnlp-main.499/);[codice ufficiale](https://github.com/Liyan06/MiniCheck) | Osservazioni efficienti di fattualità su rivendicazioni e documenti giustificativi. | Specialista valutato; non rilasciare autorità |
| Deren Lei, Yaxi Li, Siyao Li, Mengya Hu, Rui Xu, Ken Archer, Mingyu Wang, Emily Ching e Alex Deng | [FattoCG](https://aclanthology.org/2025.naacl-long.258/);[codice ufficiale](https://github.com/derenlei/FactCG) | Osservazioni di fattualità multi-hop basate su grafici. | Specialista valutato; non rilasciare autorità |
| Philippe Laban, Tobias Schnabel, Paul N. Bennett e Marti A. Hearst | [SummaC](https://aclanthology.org/2022.tacl-1.10/) | Espone problemi di granularità di frasi/documenti nel controllo di coerenza. | Influenza del design |
| Lorena Scirè, Simone Conia, and Roberto Navigli | [FENICE](https://arxiv.org/abs/2403.02270) | Estrazione delle richieste e allineamento delle prove per la valutazione del riepilogo. | Influenza del design |
| Xiangkun Hu e collaboratori | [RefChecker](https://github.com/amazon-science/RefChecker) | Supporto dettagliato, confutazione e record sconosciuti. | Influenza del design valutato |
| Trieu H. Trinh e collaboratori | [AlphaGeometria](https://github.com/google-deepmind/alphageometry) | Chiusura di deduzione monotona e tracce di dipendenza dalla prova esplicita. Le regole della geometria non vengono utilizzate. | Influenza del design |

MiniCheck e FactCG sono stati valutati con revisioni pubbliche bloccate e le relative licenze pubblicate. I loro punteggi non erano separabili su importanti mutazioni a forma di progetto, quindi sono stati rimossi dall'autorità di rilascio. Preservare quel risultato negativo fa parte della reciprocità: agli strumenti viene riconosciuto ciò che possono osservare senza travisare ciò che i loro autori affermavano di poter dimostrare.

## Collaboratori del software

I seguenti progetti software pubblici forniscono macchinari limitati. I rispettivi avvisi e licenze sul copyright regolano qualsiasi ridistribuzione del loro codice; questa documentazione pubblica non la ridistribuisce.

| Software | Contributori o steward | Licenza registrata | Ruolo limitato |
|---|---|---|---|
| spaCy e i suoi modelli linguistici | Explosion AI, Matthew Honnibal, Ines Montani e collaboratori | MIT | Parte del discorso, morfologia, analisi delle dipendenze e misurazioni strutturali |
| Fuoco scintillante | Microsoft e collaboratori | MIT | Segmentazione della frase |
| LemmInfletto | Brad Jascob e collaboratori | MIT | Inflessione inglese |
| submodlib | Vishal Kaushal, Rishabh Iyer, Ganesh Ramakrishnan e collaboratori di DECILE | MIT | Selezione submodulare |
| NLTK | Steven Bird, Edward Loper, Ewan Klein e collaboratori | Apache-2.0 | Accesso al corpus e utilità linguistiche |
| NumPy | Collaboratori di NumPy | Clausola BSD-3 | Array numerici e matrici di similarità |
| SciPy | Collaboratori di SciPy | Clausola BSD-3 | Clustering e operazioni statistiche |
| ReteX | Collaboratori di NetworkX | Clausola BSD-3 | Operazioni e misurazioni sui grafici diretti |
| inginocchiato | Kevin Arvai e collaboratori | Clausola BSD-3 | Rilevamento del punto di ginocchio per le curve di calibrazione misurate |
| PyYAML | Kirill Simonov e collaboratori | MIT | Scambio di configurazioni strutturate |
| httpx | Tom Christie e collaboratori | Clausola BSD-3 | Trasporto HTTP del limite del servizio |
| psycopg | Daniele Varrazzo e collaboratori | LGPL-3.0 | Accesso PostgreSQL |
| Pydantico | Contributori pidantici | MIT | Convalida tipizzata e serializzazione |
| ApriVINO | Intel e collaboratori | Apache-2.0 | Inferenza del modello limitato dove configurato |
| descrizioni del testo | Lasse Hansen, Kenneth Enevoldsen e collaboratori | Apache-2.0 | Leggibilità, coerenza e misurazioni della teoria dell'informazione |
| LFTK | Bruce W. Lee e Jason Hyung-Jong Lee | Licenza di progetto pubblico; verificare con qualsiasi versione ridistribuita | Estrazione delle caratteristiche linguistiche valutate per la calibrazione |

La tabella è un inventario principale, non un sostituto degli avvisi di dipendenza generati dalla macchina in una futura distribuzione del codice. Versioni esatte, hash, licenze transitive e testi di licenza completi devono accompagnare qualsiasi versione che ridistribuisca software o file di modello.

## Opere culturali, corpora, archivi e comunità

L'analisi misura i modelli di consegna e le proprietà strutturali. A meno che una licenza separata non consenta la riproduzione, l'output pubblico contiene misurazioni aggregate e identità di origine, non testo di origine.

| Fonte | Persone o istituzioni accreditate | Permessi e limiti d'uso | Contributo |
|---|---|---|---|
| Progetto Gutenberg | Michael S. Hart, correttori di bozze distribuiti, autori partecipanti, redattori, traduttori e volontari | Vengono misurati i testi di dominio pubblico verificati; I termini e il marchio dell'edizione Project Gutenberg rimangono rispettati. | Calibrazione letteraria e di forma del prodotto di lungo periodo |
| LibriVox | Lettori volontari, manutentori e autori di testi di origine di pubblico dominio | LibriVox registra testi di pubblico dominio e dedica le sue registrazioni al pubblico dominio secondo la sua politica dichiarata. | Calibrazione della consegna vocale del candidato; non raggruppato silenziosamente con la stampa |
| Corpo Marrone | W. Nelson Francis, Henry Kučera, Brown University e curatori | Utilizzato attraverso i termini del corpus distribuito per la misurazione aggregata. | Contrasti di registro etichettati per genere |
| Reuters-21578 | Reuters, David Lewis e curatori | Misurazioni aggregate solo secondo i termini di distribuzione del set di dati. | Confronto wire-copy denso |
| Corpus di chat NPS | Eric Forsyth, Jane Lin, Craig Martell e la Scuola di specializzazione navale | Misurazione aggregata; il testo personale non viene riprodotto pubblicamente. | Confronto chat da uomo a uomo |
| Traduzioni della Dichiarazione Universale dei Diritti Umani | OHCHR e traduttori delle Nazioni Unite | Traslazioni parallele misurate come controllo; attribuzione mantenuta. | Separa i modelli di protocollo multilingue dalle abitudini inglesi |
| arXiv | Cornell University, arXiv, autori partecipanti e manutentori | I metadati vengono trattati secondo i termini pubblicati; gli abstract rimangono opera degli autori e non vengono riprodotti. | Misurazione longitudinale del registro scientifico |
| PubMed/MEDLINE | Biblioteca nazionale di medicina degli Stati Uniti, riviste partecipanti e autori | Solo misurazione aggregata; gli abstract non vengono ridistribuiti e non è implicita alcuna approvazione da parte della NLM. | Confronto scientifico in prosa |
| Delpher | Koninklijke Bibliotheek, collaboratori, editori e autori della digitalizzazione | Misurazione aggregata solo perché i diritti a livello di articolo variano. | Confronto di giornali di lungo periodo |
| Wikipedia | Wikimedia Foundation e redattori che contribuiscono | Fonte CC BY-SA; nessun testo di articolo è riprodotto in questa pubblicazione. | Confronto dei registri dell'enciclopedia |
| Overflow dello stack | Stack Exchange e la community di risposta | Fonte CC BY-SA; nessun testo del post è riprodotto qui. | Confronto risposte forum |
| Campioni di Hacker News e Mastodon | Operatori di piattaforme e singoli autori di comunità | Non si presuppone alcuna licenza generale sui contenuti; solo le osservazioni aggregate non identificative sono pubblicabili. | Confronto esplorativo in formato moderno |

La reciproca restituzione del progetto pubblico non è il possesso di queste opere. È un resoconto verificabile dei metodi che hanno adottato, dei limiti individuati, delle ipotesi fallite che hanno contribuito a falsificare e di misurazioni riutilizzabili che preservano un percorso di ritorno ai contributori.

La reciprocità governa anche l’uso del modello esterno. Fornire un carico utile di lavoro autorizzato per un contributo limitato non rende il servizio esterno proprietario del corpus mantenuto, così come l’utilizzo della ricerca pubblicata non ne cancella la paternità. Il contributo dovrebbe essere accreditato e misurato, mentre la fonte, l’autorità e il valore continuo della documentazione sottostante rimangono distinti. La reciprocità impedisce che la derivazione utile diventi una scusa per distruggere il contesto umano e concentrarne il valore all'interno dell'istituzione ricevente.

## Diritti e confine di completezza

Lo stato di dominio pubblico, l'accesso aperto, l'open source e l'autorizzazione per l'analisi computazionale sono stati di diritti diversi. Il registro registra la base applicabile anziché considerare la “disponibile online” come un’autorizzazione. Le fonti che richiedono elusione, autorizzazione incerta o una teoria del fair use non rivista sono escluse dai nuovi set di dati di pubblicazione.

Il registro copre i principali fondamenti visibili nella documentazione pubblica. Il progetto privato mantiene un inventario in evoluzione più ampio, inclusi i candidati valutati e rifiutati. Una futura versione accademica o software deve produrre un'esatta distinta dei materiali del software specifica per l'artefatto, un registro di modelli e set di dati, una bibliografia, un pacchetto di licenze e un record di trasformazione. L'omissione da questo riepilogo non cancella il credito né concede l'autorizzazione.
