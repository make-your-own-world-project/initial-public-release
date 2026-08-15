> Italiano: Traduzione assistita da macchina dell'autorevole fonte inglese. Sono gradite correzioni nella lingua madre. [Inglese](../../README.md) | [Tutte le lingue](../README.md)

# Cosa è in esecuzione adesso

![La macchina locale organizzata per responsabilità attorno ad una dorsale controllata e condivisa](../../assets/public-machinery-catalog.png)

## Come leggere questo catalogo

Il catalogo è la controparte pubblica della vista Datacenter in Mission Control. Descrive il contributo di ciascun ingranaggio e cosa andrebbe perso se scomparisse, senza pubblicare indirizzi privati, layout della macchina, credenziali, percorsi di file o cadenza operativa. Il grafico in tempo reale rimane la fonte operativa della verità.

Lo stato dei componenti è importante. Uno strumento può essere attivo, mantenuto come sistema di origine, valutato ma non adottato o un predecessore ritirato. La presenza in questo catalogo non garantisce a un componente autorità oltre il suo ruolo dichiarato.

Tale regola include la capacità di frontiera esterna. Quando viene utilizzato, occupa una stazione delimitata e riceve un carico utile appositamente creato anziché un accesso illimitato al corpus mantenuto. Il carico utile supporta l’operazione dichiarata ma omette lo stato durevole necessario per ricostruire il sistema più ampio o produrre in modo indipendente prelievi futuri. La stazione riceve lavoro, non la custodia del patrimonio umano da cui un’istituzione centralizzata potrebbe estrarre valore durevole.

## Modi dentro e intorno al sistema

### Cervello robotico (LibreChat)


**Responsabilità.** Fornire la finestra di conversazione sostituibile rivolta alle persone. Trasporta richieste e risposte mentre la memoria durevole, il recupero, il ragionamento e la verifica rimangono nei servizi sottostanti.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

**Principali strumenti pubblici.**[LibreChat](https://github.com/danny-avila/LibreChat),[Node.js](https://github.com/nodejs/node)

### Divisore di conversazione


**Responsabilità.** Avvisa quando una chat si trasforma in due argomenti e si offre di archiviare separatamente quella completata.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

**Principali strumenti pubblici.**[API veloce](https://github.com/fastapi/fastapi)

### Controllo della missione


**Responsabilità.** La finestra sulla macchina: cosa è in funzione, cosa richiede attenzione e cosa sta facendo in questo momento. Al limite della pubblicazione, la pagina di stato riporta tutti i sistemi monitorati operativi sull'installazione locale.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Lo stato operativo riporta lo stato del servizio; gli artefatti e le ricevute accettati stabiliscono i confini separati dell'esecuzione e dell'evidenza semantica.

**Principali strumenti pubblici.**[API veloce](https://github.com/fastapi/fastapi),[Graphviz](https://gitlab.com/graphviz/graphviz),[Psicopg](https://github.com/psycopg/psycopg)

### Router semantico


**Responsabilità.** Indirizza le richieste limitate al motore locale appropriato e richiede l'autorizzazione esplicita prima di utilizzare l'inferenza esterna. La capacità costosa viene selezionata solo quando la richiesta ne giustifica il costo misurato.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

**Principali strumenti pubblici.**[API veloce](https://github.com/fastapi/fastapi). Envoy e il router semantico vLLM rimangono accreditati nell'indice di origine come predecessori controllati o ritirati, non come dipendenze di runtime attuali.

### Completa la cronologia degli agenti


**Responsabilità.** Conserva flussi di eventi dell'agente completi e ordinati come prova dell'interazione, inclusi turni umani, turni di assistenti, strumenti, errori e correzioni. Le storie registrano ciò che accadde; non trasformano le dichiarazioni degli agenti in fatti verificati.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Fornisce solo ciò che ne stabilisce l'origine e la provenienza; l'interpretazione a valle rimane separata.

### Documenti di progetto


**Responsabilità.** Conserva la progettazione privata, le prove e i record del progetto che spiegano perché esiste la piattaforma e come è cambiata la sua architettura. I prodotti pubblici consumano derivati ​​revisionati anziché esporre la posizione del documento privato.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Fornisce solo ciò che ne stabilisce l'origine e la provenienza; l'interpretazione a valle rimane separata.

### Vikunja


**Responsabilità.** Preservare il sistema di attività esterne come fonte di proprietà indipendente che precede la piattaforma. L'integrazione può leggere le prove delle attività autorizzate senza assorbire il sistema delle attività nel corpus o modificarne il ciclo di vita.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Fornisce solo ciò che ne stabilisce l'origine e la provenienza; l'interpretazione a valle rimane separata.

**Principali strumenti pubblici.**[Vikunja](https://github.com/go-vikunja/vikunja)

## Conservazione e recupero

### Assunzione di conoscenze


**Responsabilità.** Il modo in cui le cose entrano in gioco. Lascia un documento, un'esportazione, una pila di appunti e finisce in un posto dove è possibile trovarlo invece che nel nulla.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

### MongoDB


**Responsabilità.** Tiene le conversazioni stesse, così come sono state dette.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Disponibilità e integrità sono necessarie; i dati memorizzati non si interpretano né si verificano.

**Principali strumenti pubblici.**[MongoDB](https://github.com/mongodb/mongo)

### PostgreSQL


**Responsabilità.** Conserva record di progetti strutturati durevoli, stati derivati ​​e indici di ricerca destinati a sopravvivere ai servizi applicativi sostituibili. I documenti archiviati mantengono autorità e provenienza distinte anziché diventare un'unica memoria indifferenziata.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Disponibilità e integrità sono necessarie; i dati memorizzati non si interpretano né si verificano.

**Principali strumenti pubblici.**[PostgreSQL](https://github.com/postgres/postgres),[pgvettore](https://github.com/pgvector/pgvector)

## Ragionamento e ricostruzione

### Classificatore di relazioni tra argomenti

classificazione CPU AMF_ARI OpenVINO bloccata di inferenza, conflitto, riformulazione o assenza di relazione

**Responsabilità.** Classificare la relazione tra due proposizioni fornite; non crea alcuna proposta né deduce motivazioni personali. Esempio: distinguere un'affermazione che ne supporta un'altra da una che la contraddice, oppure non restituire alcuna relazione supportata.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

**Principali strumenti pubblici.**[Modello AMF ARI RoBERTa OpenVINO](https://huggingface.co/arg-tech/amf-ari-roberta-ov-int8)

### Artefatti umani


**Responsabilità.** Definire i prodotti rivolti all'uomo che la catena di montaggio può costruire. Ogni prodotto porta con sé il proprio destinatario, scopo, struttura, politica di prova e contratto di consegna anziché condividere uno schema generico.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

### Messa a terra + Convalida della consegna

controllo di ricezione indipendente sui controlli di fedeltà, provenienza, perdita, invenzione, trama e comprensione

**Responsabilità.** Prima del rilascio, verificare in modo indipendente che l'artefatto conservi il significato supportato e soddisfi il contratto di consegna dichiarato. Esempio: rifiutare un paragrafo leggibile che inventa una conclusione e rifiutare separatamente un documento fondato la cui struttura è inutilizzabile per il lettore a cui è rivolto.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

### Risoluzione del pubblico

stato del destinatario, prerequisiti, registro e pertinenza

**Responsabilità.** Descrivi ciò che il destinatario previsto dovrebbe sapere, aver bisogno e tollerare mantenendo esplicite le ipotesi. Esempio: richiedere a una guida per il proprietario della casa di spiegare il pH prima di utilizzare abbreviazioni familiari a un tecnico della piscina.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

### Collasso dell'intero albero + pacchetti

partizione, selezione, guadagni e perdite vincolati al contenitore

**Responsabilità.** Seleziona e bilancia ciò che può adattarsi all'artefatto richiesto registrando ciò che è stato omesso e preservando la forma significativa dell'albero. Esempio: mantenere ogni ramo principale rappresentato in un articolo di 1.000 parole invece di lasciare che il ramo di origine più grande consumi l'intero budget.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

**Principali strumenti pubblici.**[submodlib](https://github.com/decile-team/submodlib),[inginocchiato](https://github.com/arvkevi/kneed)

### Modello di lavoro compatto

supporto portatile con ambito richiesta per unità selezionate, relazioni, traiettorie, blocchi di origine, piani, maniglie e registri di trasferimento

**Responsabilità.** Raggruppa i fatti, le relazioni, la cronologia, l'incertezza, i fallimenti e gli handle delle fonti selezionati in un contesto portatile specifico per il lavoro. Esempio: fornire all'editor la catena di manutenzione del pool e il motivo per cui i suoi passaggi si collegano senza caricare l'intero corpus o eliminare i collegamenti.

**Deve preservare.** source_spans; ID_relazione; cronologia; incertezza; fallimenti; sostituzione; incognite

**Forma della risorsa.** CPU e RAM proporzionali alla selezione limitata; nessuna GPU o leasing

**Confine.** La qualità è limitata dalla relazione a monte e dalla copertura dello Stato di deposito

### Meccanica di consegna

controlli di registro, modalità, profili di tessitura, ritmo, densità e deslop

**Responsabilità.** Fornisci vincoli di consegna misurati, come ritmo, densità, registro e traiettoria di tessitura, per questo prodotto e pubblico. Esempio: fornire alla spiegazione dei bambini pacchetti più brevi e uno schema di ricorrenza diverso rispetto a una relazione tecnica senza modificare i fatti sottostanti.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

### Preelaborazione del discorso

sezioni delimitate esatte, candidati di riferimento FastCoref e collegamenti di operandi RST isanlp noleggiati

**Responsabilità.** Identificare i referenti candidati e gli intervalli del discorso prima della classificazione del ragionamento preservando le coordinate esatte della fonte. Esempio: collega "esso" al candidato pompa nominato ed esponi le due clausole unite da una relazione di discorso causale.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

**Principali strumenti pubblici.**[IsaNLP RST](https://github.com/tchewik/isanlp_rst),[FastCoref](https://github.com/shon-otmazgin/fastcoref)

### Ricostruzione in avanti dell'intero artefatto

prerequisiti, referenti, collante causale, progressione, introduzione e conclusione

**Responsabilità.** Ricostruisci il materiale selezionato nell'ordine di lettura, ripristinando prerequisiti, referenti, collegamenti causali, progressione e un finale onesto. Esempio: introdurre l'obiettivo prima della procedura e chiudere una questione irrisolta quando non esiste alcuna conclusione.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

### Grafico Perché e proiezione delle dipendenze

visione deterministica dei bordi dei grafici classificati che non può introdurre nuove affermazioni argomentative

**Responsabilità.** Traduci i limiti delle relazioni accettate in dipendenze ispezionabili e perché in visualizzazioni senza aggiungere interpretazione. Esempio: mostrare che la conclusione B dipende dalla premessa A perché esiste quell'esatto limite classificato.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

**Principali strumenti pubblici.**[ReteX](https://github.com/networkx/networkx)

### Risposta interattiva fondata


**Responsabilità.** Restituisci una risposta colloquiale con il ragionamento, la provenienza, l'incertezza e i percorsi di espansione pertinenti. Il percorso della risposta può attraversare conversazioni complete e cicli di vita delle prove senza pretendere di essere un processo di generazione di documenti.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

### Ponte del protocollo umano

codifica orientata al ricevitore del carico utile fisso supportato

**Responsabilità.** Convertire un carico utile fisso e supportato in una forma che la persona designata possa seguire, utilizzando il contratto del prodotto e il modello di consegna misurato; non può cambiare le prove. Esempio: trasformare la stessa catena di ragionamento radicata in un'e-mail concisa o in una guida graduale modificando la struttura di consegna, non le conclusioni.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

### Assemblaggio interattivo del contesto


**Responsabilità.** Costruisci un grafico di prova e ragionamento limitato per la domanda attuale, preservando la cronologia, le correzioni, gli errori, l'identità della fonte e l'autorizzazione. Fornisce il contesto alla risposta senza appiattire il corpus in frammenti di ricerca.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

### Adesione senza perdite


**Responsabilità.** Ammettere i byte originali e gli eventi nativi prima dell'interpretazione, registrando solo i fatti di arrivo osservati. Descrizioni, timestamp dedotti da contenuto, identità e relazioni rimangono osservazioni con versione separata.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

### Prove primarie


**Responsabilità.** Detenere i depositi autorevoli a cui successive rappresentazioni e prodotti dovranno poter risalire. La loro esistenza persiste anche quando il sistema non è ancora in grado di spiegare il loro significato o la loro relazione.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

### Completa l'albero provvisorio

evidenza completa prima della potatura, dipendenza, alternativa e struttura di fallimento

**Responsabilità.** Conserva l'albero candidato completo nell'ambito della richiesta, incluse alternative, errori, incognite e visualizzazioni sostituite, in modo che il collasso possa vedere cosa perderebbe. Esempio: conservare sia un trattamento fallito che la correzione successiva prima di selezionare il materiale per una guida.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

### Grafico del ragionamento

cronologia, relazioni tipizzate, cicli di vita delle rivendicazioni, fallimenti e incertezza

**Responsabilità.** Mantieni la mappa di proposizioni, cronologia, tentativi, risultati, conflitti, dipendenze e incertezze nell'ambito della richiesta. Esempio: collegare un trattamento fallito alla correzione che lo ha sostituito senza eliminare nessuno dei due stati.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

### Richiesta + Contratto artefatto

scopo, destinatario, contenitore, canale, budget e veridicità

**Responsabilità.** Congelare lo scopo, il destinatario, il prodotto, il canale, il budget e lo standard di verità in modo che ogni ingranaggio a valle risolva lo stesso lavoro. Esempio: distinguere una spiegazione di 500 parole per un lettore generale da un rapporto di incidente tecnico prima che inizi la selezione delle prove.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

### Espansione inversa

raccogliere all'indietro senza potatura; misurare il contributo marginale

**Responsabilità.** Passa dalla richiesta o dalle prove successive ai documenti correlati precedenti e raccogli il percorso completo del candidato prima che qualsiasi cosa venga scartata. Esempio: seguire una domanda attuale sulle alghe attraverso i precedenti record di pH, dimensioni della piscina, manutenzione e contesto d'uso.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

### Mosse retoriche digitate

lavori semantici e dipendenze, mai sottostringhe di intestazione

**Responsabilità.** Assegna a ciascuna unità selezionata un lavoro comunicativo e una dipendenza in base al contratto del prodotto, non a una parola di intestazione corrispondente. Esempio: contrassegnare le prove come a supporto di una richiesta e il fallimento come impostazione del recupero anziché chiamarli entrambi "contesto".

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

### Ricostruzione semantica

entità, proposizioni, episodi, tentativi, risultati e domande

**Responsabilità.** Converti le osservazioni della fonte in oggetti semantici attribuiti senza deciderne l'importanza o la presentazione finale. Esempio: rappresentare una soluzione proposta, il tentativo, il suo fallimento e la domanda rimanente come record collegati separati.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

### Rappresentazioni con versione


**Responsabilità.** trascrizioni, struttura, testo, OCR, layout e viste derivate

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

### Perché era importante

motivazione attribuita, preoccupazione, conseguenza e rilevanza attuale

**Responsabilità.** Riporta prove dirette ed esplicitamente attribuite sul motivo per cui è stata investita l'attenzione, lasciando sconosciute le ragioni non supportate. Esempio: affermare che un'attività di manutenzione era importante perché proteggeva le persone che utilizzavano apparecchiature condivise quando il record lo supporta, piuttosto che indovinare quel motivo solo da una questione tecnica.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

### Ragionamento + Motore degli artefatti

ricostruzione con ricevuta di ritorno, collasso, protocollo umano e rendering Markdown atomico

**Responsabilità.** Coordinare il percorso delimitato di ricostruzione e rendering ed esporre la ricevuta di ogni fase; non sostituisce il giudizio specialistico. Esempio: eseguire una richiesta di composizione tramite selezione, pianificazione, realizzazione, convalida e scrittura atomica.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

### Responsabile dell'Assemblea + Capacità

cammina all'indietro nei campi richiesti, valuta i prerequisiti, seleziona specialisti onesti, ordina ondate di dipendenza e salta il lavoro a valore zero

**Responsabilità.** Scegli quali specialisti sono necessari, in quale ordine intervengono e quale lavoro non aggiunge valore; non svolge il loro lavoro. Esempio: pianificare la realizzazione della relazione prima della realizzazione della frase e saltare un passaggio stilistico non disponibile che non apporta nulla di necessario.

**Da conservare.** must_preserve_fields; campo_lignaggio; esplicito_indisponibilità

**Forma della risorsa.** CPU; memoria insufficiente; nessuna GPU o leasing

**Confine.** Le osservazioni sui costi e sul valore espongono le decisioni ma non definiscono mai l'importanza umana

### Riconciliatore del budget della portante atomica

misura la fonte indivisibile, il collante e i vettori di relazione prima della realizzazione e ridistribuisce il budget fisso dell'intero prodotto in base al margine di flessibilità della sezione reale

**Responsabilità.** Controlla se fatti indivisibili e supporti di relazione possono adattarsi a ciascuna sezione, quindi sposta solo il margine disponibile preservando il budget totale del documento. Esempio: ingrandire una sezione di procedura di 90 parole che contiene un'istruzione atomica richiesta di 120 parole prendendo in prestito parole inutilizzate da un'altra sezione.

**Deve preservare.**whole_artifact_budget; lavori_retorici_richiesti; autorità_origine; forma_grafo

**Forma della risorsa.** CPU; tempo di esecuzione prossimo allo zero; previene lo spreco di lavoro su GPU/modello/verificatore Stage 8

**Confine.** non può comprimere una proposizione indivisibile; fallisce se tutti i corrieri richiesti superano il budget del prodotto dichiarato

### Gestore del riassociazione all'origine

sposta solo un ramo isolato completo quando il lavoro del prodotto assegnato è incompatibile e una destinazione è dimostrabilmente compatibile

**Responsabilità.** Spostare un ramo di prova completo e isolato nella sezione il cui lavoro può legittimamente utilizzarlo, rifiutando mosse ambigue o portatrici di relazioni. Esempio: riassegnare una nota di ripristino autonoma dalla configurazione alla risoluzione dei problemi senza duplicarla in entrambe le sezioni.

**Deve preservare.** branch_identity; source_spans; ID_relazione; guadagno_marginale_ledger

**Forma della risorsa.** CPU; bassa latenza; nessuna GPU o leasing

**Confine.** rifiuta movimenti portatori di relazioni, ambigui, parziali o di capacità eccessiva

### Realizzatore di relazioni a livello di documento

trasforma i ragionamenti accettati della stessa sezione e della sezione trasversale in un linguaggio connettivo compatto e riproducibile indipendentemente senza ripetere entrambi gli operandi

**Responsabilità.** Trasforma le relazioni grafiche accettate in un breve linguaggio connettivo mantenendo la direzione, gli operandi e gli intervalli di origine riproducibili in modo indipendente. Esempio: realizzare A-cause-B come un ponte causale delimitato invece di stampare A e B come fatti adiacenti non correlati.

**Deve preservare.** relationship_direction; identità_operando; esatto_carrier_spans; source_spans; sezione_lignaggio

**Forma della risorsa.** CPU; tempo di esecuzione prossimo allo zero; nessuna GPU o leasing

**Boundary.** realizza solo i tipi di relazione accettati espliciti; i ponti compatti preservano l'identità del bordo digitato ma rimangono formulati meccanicamente; i bordi della stessa portante, ambigui, impliciti e sconosciuti rimangono visibili nel grafico ma non affermati come prosa

### Motore della conoscenza


**Responsabilità.** Coordinare l'adesione, le rappresentazioni derivate, la ricerca, la provenienza e i lavori durevoli senza unire tali responsabilità in un unico stato di verità. Espone le interfacce supportate ai consumatori mentre le prove primarie rimangono affrontabili in modo indipendente.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

### Microplanner di clausole/frasi digitate

assegna supporti legati alla fonte a lavori retorici dattiloscritti e compila piani di clausole, frasi e paragrafi

**Responsabilità.** Suddividi il significato e le relazioni approvati in clausole, frasi e paragrafi preservando i collegamenti alla fonte; non inventa formulazioni o affermazioni. Esempio: pianificare una clausola causale seguita dalla sua conseguenza e transizione per il realizzatore della superficie.

**Deve preservare.** semantic_unit_ids; ID_relazione; source_forms

**Forma della risorsa.** CPU; bassa latenza; nessuna GPU o leasing

**Confine.** non inventa una proposizione mancante né ripara una relazione non classificata

**Principali strumenti pubblici.**[SPAZIOSO](https://github.com/explosion/spaCy),[Fuoco scintillante](https://github.com/microsoft/BlingFire)

### Responsabile contratto prodotto

converte genere, destinatario, scopo, canale, veridicità, attenzione e budget nei campi di prodotto richiesti e nel lavoro retorico

**Responsabilità.** Trasforma la richiesta in una checklist concreta per il prodotto finito senza scegliere prove o scriverle. Esempio: per un manuale utente, richiedere prerequisiti, azioni ordinate, indicazioni per il ripristino e una chiusura prima dell'avvio di qualsiasi editor.

**Deve preservare.** scopo_dichiarato; ricevitore; veridicità; canale

**Forma della risorsa.** CPU; tempo di esecuzione prossimo allo zero; nessuna GPU o leasing

**Confine.** non deduce il significato della fonte né sceglie i fatti

### Realizzatore di superfici contrattuali

applica la grammatica limitata, la morfologia, la tipografia, la prospettiva e le trasformazioni tipizzate alle unità di consegna

**Responsabilità.** Applicare grammatica, morfologia, tipografia e prospettiva consentita a un piano già approvato; non può decidere un nuovo significato. Esempio: trasformare un piano imperativo digitato in un'istruzione grammaticale senza aggiungere un'affermazione di sicurezza che non è mai stata fornita.

**Deve preservare.**claim_authority; source_and_relation_bindings; retorico_lavoro

**Forma della risorsa.** CPU; l'editor candidato opzionale può utilizzare un lease GPU esistente ma non ha alcuna autorità

**Confine.** La grammatica chiusa è fedele ma può rimanere stilisticamente rigida

**Principali strumenti pubblici.**[SPAZIOSO](https://github.com/explosion/spaCy)

## Gestione, verifica e operazioni

### Amf Ari


**Responsabilità.** Esegui il classificatore argomento-relazione bloccato sulle coppie di proposizioni fornite e restituisce tentativi di supporto con punteggio, conflitto, riformulazione o assenza di relazione. Non crea proposizioni, non deduce motivazioni né certifica le proprie etichette.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

**Principali strumenti pubblici.**[ApriVINO](https://github.com/openvinotoolkit/openvino),[Modello AMF ARI RoBERTa OpenVINO](https://huggingface.co/arg-tech/amf-ari-roberta-ov-int8)

### Indicizzatore di chat


**Responsabilità.** Mantiene le conversazioni nel registro lungo invece di lasciarle nella finestra della chat.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

### Indicizzatore di file


**Responsabilità.** Scopri i file idonei e invia lavori di indicizzazione delimitati e che preservino la provenienza. Non deve considerare le date del file system, i nomi dei file o il testo estratto come ora, identità o motivo di creazione autorevole.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

### Telemetria hardware


**Responsabilità.** Registra la cronologia limitata delle condizioni della macchina in modo che i guasti possano essere confrontati con alimentazione, temperatura, memoria e stato dell'acceleratore. La descrizione pubblica omette la cadenza di campionamento privata e il layout della macchina.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

**Principali strumenti pubblici.**[psutil](https://github.com/giampaolo/psutil)

### Immagine


**Responsabilità.** Produci immagini localmente in modo che un concetto visivo non debba oltrepassare un confine di inferenza esterno. La generazione delle immagini rimane separata dall'autorità di prova e dall'autorizzazione alla pubblicazione.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

**Principali strumenti pubblici.**[diffusione-stabile.cpp](https://github.com/leejet/stable-diffusion.cpp),[Z-Immagine-Turbo](https://huggingface.co/Tongyi-MAI/Z-Image-Turbo),[Riferimento alla confezione Z-Image-Turbo-Windows](https://github.com/airesearch-official/Z-Image-Turbo-Windows)

### Ollama


**Responsabilità.** La mente pesante. Più lento e più ampio, riservato a domande che richiedono davvero più riflessione che velocità.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

**Principali strumenti pubblici.**[Ollama](https://github.com/ollama/ollama),[Qwen3](https://github.com/QwenLM/Qwen3)

### Ollama Incorpora


**Responsabilità.** Rende la scrittura ricercabile in base al significato anziché alle parole esatte.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

**Principali strumenti pubblici.**[Ollama](https://github.com/ollama/ollama),[Testo incorporato nomico](https://huggingface.co/nomic-ai/nomic-embed-text-v1.5)

### Locazione di potenza


**Responsabilità.** Lascia che la macchina giri al minimo silenziosamente e si riattivi completamente per il vero lavoro.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

### Rititolazione delle conversazioni


**Responsabilità.** Assegna alle conversazioni nomi che significano qualcosa, in modo che l'elenco sia facilmente reperibile anziché un muro di prime frasi.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

### Osservatore semantico


**Responsabilità.** Controlla se una risposta è supportata dal materiale da cui dichiara di provenire.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

**Principali strumenti pubblici.**[Trasformatori](https://github.com/huggingface/transformers),[MiniCheck](https://github.com/Liyan06/MiniCheck),[FattoCG](https://github.com/derenlei/FactCG)

### Analisi della pendenza


**Responsabilità.** Tiene traccia di come ogni mente fallisce e se ciò sta migliorando o peggiorando.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

**Principali strumenti pubblici.**[SPAZIOSO](https://github.com/explosion/spaCy),[Fuoco scintillante](https://github.com/microsoft/BlingFire),[NLTK](https://github.com/nltk/nltk)

### Discorsi


**Responsabilità.** Trasforma il discorso in testo, quindi parlare è un modo per scrivere le cose.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

**Principali strumenti pubblici.**[Discorsi](https://github.com/speaches-ai/speaches),[sussurro più veloce](https://github.com/SYSTRAN/faster-whisper),[distillazione-veloce-whisper-large-v3](https://huggingface.co/Systran/faster-distil-whisper-large-v3)

### Servizio attività


**Responsabilità.** Leggi i record delle attività autorizzate come prova del lavoro pianificato senza convertirli in promemoria, motivazioni dedotte o verità del corpus.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

### vLLM


**Responsabilità.** La mente quotidiana. Veloce, sempre carico, risponde a quasi tutto.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

**Principali strumenti pubblici.**[vLLM](https://github.com/vllm-project/vllm),[Qwen3](https://github.com/QwenLM/Qwen3)

### Lavori teatrali durevoli

lotti limitati, punti di controllo, annullamento, ripresa e fallimento parziale

**Responsabilità.** Esegui lunghe fasi di artefatti come lavori delimitati ripristinabili con stati terminali veritieri invece di legarli a una richiesta del browser. Esempio: riprendere dopo un checkpoint di promozione verificato anziché ripetere un passaggio di ragionamento costoso dopo l'interruzione.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

### Esecuzione + Gestore manifest

esegue l'adattatore assegnato e registra il metodo fisico, l'endpoint, la revisione del modello, gli hash, i limiti delle chiamate, i tempi, i tentativi e la disposizione

**Responsabilità.** Gestisci ogni specialista assegnato e registra ciò che è stato fisicamente eseguito, con i relativi input, identità, tempistica, nuovi tentativi e risultati. Esempio: mostra che il classificatore AMF bloccato ha gestito la Fase 2 invece di fidarsi di un'etichetta manifest che dice semplicemente di averlo fatto.

**Deve preservare.** input_hashes; identità_adattatore; stato_fallimento

**Forma delle risorse.** Coordinatore CPU; i delegati GPU funzionano solo tramite proprietari di leasing dichiarati

**Boundary.** registra l'esecuzione; non può certificare il proprio successo

### Arbitrato sul leasing della GPU


**Responsabilità.** Coordinare i trasferimenti di consulenza tra i carichi di lavoro dell'acceleratore gestiti dalla piattaforma senza esporre l'identità fisica del dispositivo o anticipare il lavoro già in corso.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

### Coordinatore della residenza di potere

**Responsabilità.** Mantieni un modello di stato ATTIVO, CALDO, IDLE e MAI attraverso i meccanismi di alimentazione e residenza della piattaforma distribuita.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

### Registro del carico utile previsto/osservato

unisce la responsabilità di ciascun ingranaggio ai campi osservati, alla disponibilità, alle omissioni, al valore, al costo, ai tempi, ai tentativi e alla richiesta di riparazione

**Responsabilità.** Confronta il contributo previsto da ogni ingranaggio con ciò che effettivamente ha trasmesso, compresi i costi e gli input mancanti. Esempio: esporre che l'analisi della relazione è stata eseguita per 40 secondi ma non ha fornito alcun vantaggio connettivo utilizzabile all'editor.

**Deve preservare.** handoff_identity; digerisce; campi_mancanti; costo_base

**Forma della risorsa.** CPU; quasi zero rispetto al ragionamento e alla verifica

**Confine.** La tempistica della sezione portatile non sostituisce la tempistica della fase/modello fisico nel manifest di esecuzione

### Responsabile della qualità consapevole del prodotto

controlla il completamento retorico, il ragionamento connettivo, la leggibilità, la tipografia, la duplicazione, l'attenzione, il budget, la trama, la sciatteria e le azioni eseguibili per il prodotto richiesto

**Responsabilità.** Valuta se questo prodotto specifico funziona per il lettore e lo scopo dichiarati su assi di qualità separati, quindi identifica la fase di riparazione responsabile. Esempio: un manuale può fallire senza una guida al recupero anche quando ogni frase è grammaticalmente corretta e fondata.

**Deve preservare.** individual_axis_results; prova_candidato_rifiutato

**Forma della risorsa.** CPU più verificatore/deslop limitato HTTP; storicamente la più grande quota Stage 8

**Confine.** gli assi di genere devono essere misurati e versionizzati; un punteggio di qualità opaco è vietato

### Responsabile ricevute e promozioni

ricalcola in modo indipendente gli invarianti e consente la scrittura di promozioni e artefatti atomici solo da una ricevuta PASS

**Responsabilità.** Verifica in modo indipendente il bundle e scrivi l'artefatto solo dopo ogni passaggio invariante richiesto. Esempio: rifiutare la promozione quando il renderer segnala il successo ma la sua ricezione non può riprodurre un'associazione di origine.

**Deve preservare.** Failure_results; incognite; identità_rilascio; rollback_limite

**Forma della risorsa.** CPU e I/O; nessuna GPU o leasing

**Confine.** L'autenticità del manifest dipende in ultima analisi dal vincolo di rilascio/configurazione immutabile rivisto

### Provenienza + controllo delle perdite

identità della fonte, stato epistemico, inferenza, invenzione e rami rifiutati

**Responsabilità.** Mantieni ogni dichiarazione legata a chi o cosa l'ha fornita, quando è stata applicata e se è stata osservata, dedotta, sostituita, rifiutata o sconosciuta. Esempio: preservare una reinterpretazione successiva senza sovrascrivere la convinzione precedente che ha effettivamente guidato un'azione.

**Deve preservare.** Identità esatta del grafico, provenienza della relazione e confine del componente dichiarato.

**Forma delle risorse.** La distribuzione in tempo reale registra l'utilizzo effettivo di CPU, memoria, storage, acceleratore e lease; questo catalogo pubblico non espone il posizionamento della macchina.

**Confine.** Può eseguire solo la propria responsabilità grafica dichiarata e non può riparare prove a monte mancanti o non supportate.

## Componenti aggiuntivi dichiarati

### Gateway Web sicuro

Fornisce accesso remoto autenticato da client approvati senza esporre direttamente i servizi della piattaforma privata all'Internet pubblica.

### Supervisore della piattaforma

Avvia i servizi in ordine di dipendenza, ne osserva l'integrità ed esegue azioni di riavvio limitate. Il suo fallimento elimina la supervisione coordinata senza ridefinire lo stato dei servizi che rimangono in funzione.

## Confine di completezza

Il catalogo copre i componenti logici attivi nel grafico dell'architettura mantenuta, non tutti i pacchetti transitivi installati da ogni runtime. Una futura versione del software richiede un'esatta distinta dei materiali del software e un pacchetto di licenze generato dai byte specifici distribuiti.
