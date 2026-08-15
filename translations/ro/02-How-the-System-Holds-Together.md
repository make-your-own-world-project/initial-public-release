> Română: Traducere asistată automat a sursei autorizate în limba engleză. Corecțiile în limba maternă sunt binevenite. [engleză](../../README.md) | [Toate limbile](../README.md)

# Cum se menține sistemul

![Dosarul păstrat care susține specialiști înlocuibili și un avion de control inspectabil](../../assets/core-architecture-layers.png)

## Separarea responsabilitatilor

Platforma separă patru preocupări care cooperează fără a deveni una pe cealaltă:

1. **Conservare** păstrează dovezile originale și proveniența observată.
2. **Înțelegerea** adaugă obiecte semantice versionate, relații, stări temporale,
  și interpretări susținute.
3. **Recuperare și interacțiune** adună dovezi specifice cererii pentru întrebări,
  explorare și conversație.
4. **Reconstituirea artefactelor** transformă o lume mărginită a dovezilor într-o lume declarată
  produs pentru un receptor declarat.

Instrucțiunile produsului nu se scurg înapoi în adevărul corpus. Un capitol, un public, un gen, o mișcare retorică sau un buget de cuvânt aparține unei retrageri. Nu este o etichetă intrinsecă a unui artefact sursă.

## Topologie stratificată

```text
PRIMARY EVIDENCE
  immutable artifacts, interaction events, source identity, observed arrival
        |
        v
VERSIONED REPRESENTATIONS
  extracted text, media observations, chunks, entities, embeddings, locators
        |
        v
SEMANTIC AND TEMPORAL MAPS
  propositions, discourse links, argument edges, chronology, supersession,
  uncertainty, open attachment points, Personal Meaning Matrix contributions
        |
        +---------------------------+
        |                           |
        v                           v
INTERACTIVE CONTEXT             ARTIFACT CONTRACT
  request-scoped traversal        receiver, purpose, form, budget, evidence rules
        |                           |
        |                           v
        |                       REVERSE EXPANSION
        |                           |
        |                       WHOLE-TREE COLLAPSE
        |                           |
        |                       FORWARD RECONSTRUCTION
        |                           |
        +----------------------> HUMAN PROTOCOL + WEAVE
                                    |
                                INDEPENDENT GATES
                                    |
                              RECEIPT-GATED PRODUCT
```

## Aderarea nu pretinde că știe

Înregistrarea sosirii poate indica că anumiți octeți au ajuns la sistem printr-un anumit canal. Nu decide în tăcere cine a creat artefactul, cine apare în el, când a apărut subiectul său, dacă un nume de fișier este corect, de ce a contat sau cine deține conținutul său. Acestea sunt observații separate cu dovezi și autoritate separate.

Arhitectura distinge artefactul original de reprezentările derivate din acesta. Textul extras, descrierile, înglobările, clasificările, rezumatele și relațiile pot fi regenerate sau înlocuite. Ele nu înlocuiesc sursa.

## Căi interactive și documente

Răspunsul interactiv și generarea artefactelor împărtășesc dovezi, proveniență, relații tipizate, incertitudine și mecanisme de validare. Ele rămân distincte de același flux de lucru.

O solicitare interactivă poate necesita o conversație completă, un ciclu de viață al sarcinii, o parcurgere a relațiilor înguste sau o clarificare. Nu este nevoie să construiască un container de cărți și să prăbușească global un arbore istoric.

Generarea artefactelor are nevoie de un produs declarat, un receptor, un buget și un plan de artefact. Trebuie să vadă structura provizorie relevantă înainte de tăiere și trebuie să țină seama de ceea ce a fost omis.

## Arhitectură dinamică mai degrabă decât un lanț fix

Linia de asamblare este compilată pentru produs. Ieșiri diferite pot folosi specialiști diferiți, pot comanda aceiași specialiști în mod diferit sau necesită mai multe instanțe ale unei singure capacități. Managerul folosește contracte de capacitate și dovezi anterioare, mai degrabă decât doar nume de scenă codificate.

Invarianții universali rămân stabili pe fiecare linie: identitatea sursei, proprietatea, starea epistemică, incertitudinea, contabilizarea pierderilor, transferurile tipărite, observarea costurilor, verificarea independentă și rollback.

Un model general extern poate ocupa o stație tipizată atunci când contribuția sa măsurată justifică transferul. Acesta primește doar sarcina utilă în funcție de cerere cerută de acea stație, nu corpus menținut sau autoritatea codificată de planul de control mai larg. Înlocuirea sau îndepărtarea acestei stații lasă intactă evidența durabilă și capacitatea viitoare de reconstrucție. Stația delimitată poate contribui fără a primi cunoștințele umane, un sistem centralizat s-ar aplatiza altfel în valoare instituțională.
