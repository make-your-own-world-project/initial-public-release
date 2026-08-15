> Română: Traducere asistată automat a sursei autorizate în limba engleză. Corecțiile în limba maternă sunt binevenite. [engleză](../../README.md) | [Toate limbile](../README.md)

# Ce este real și ce rămâne

![Idei, teste, eșecuri și capabilități verificate care traversează porți diferite de implementare](../../assets/evidence-implementation-gates.png)

## Cursuri de probe

Modelul de dovezi păstrează mai multe clase distincte:

- **dovada principală:** artefacte sursă conservate și evenimente de interacțiune;
- **dovezi derivate:** text extras, unități semantice, relații, clasificări,
  observații temporale și alte reprezentări versionate;
- **dovezi de execuție:** manifeste, observații de apel, costuri, identități model și
  rezultatele etapei;
- **dovezi de acceptare:** invarianți independenți, chitanțe, pachete promovate și
  hash-uri exacte de ieșire;
- **intenția de proiectare:** arhitectura și comportamentul planificat nedemonstrat încă în execuție;
- **afirmații istorice:** ceea ce a raportat o versiune anterioară sau un experiment despre sine.

Un test de promovare este o dovadă doar pentru plicul pe care îl exercită. Un document de lansare nu este dovada că timpul de execuție curent încă se potrivește cu acesta. O bibliotecă instalată nu este o capacitate implementată.

## Fundații implementate

Implementarea a demonstrat următoarele fundații mărginite:

- conservarea surselor abordate pe conținut și manipularea dovezilor orientată spre anexe;
- artefacte separate, reprezentări, localizatori și evenimente sursă;
- evenimente de conversație legate de actor și secvență;
- preprocesarea discursului și coreferenței cu felii de sursă mărginite;
- clasificarea relației argumentelor cu intervale exacte de sursă și încercări reținute;
- un grafic tip propoziție și relație;
- proiecția dependenței deterministe;
- contribuții la Matricea Sensului Personal în cadrul cererii cu incertitudine și
  steaguri de protectie;
- selecție înapoi și obiecte de reluare înainte cu același grafic în testele mărginite;
- alocarea de unități semantice deținute la nivel global și planificarea artefactelor întrețesute;
- etaje de randare împământate și comparație opțională a candidaților;
- promovare independentă bazată pe chitanță;
- lucrări de artefacte durabile și un vizualizator de raționament;
- o limită de publicare a documentelor publice cu versiuni adresate conținutului.

Aceste afirmații descriu limitele componentelor demonstrate, nu o pretenție că întreaga viziune este completă.

Comparația demonstrată înregistrează, de asemenea, o limită externă-cog. Un model de frontieră a primit o sarcină utilă pregătită, specifică cererii și a contribuit la o redare mai bună fără a primi corpus menținut sau a deveni autoritate de eliberare. Dovezile susțin acea tranzacție limitată; nu stabilește ce reține orice furnizor în afara căii artefactelor testate, care rămâne o întrebare separată contractuală și de confidențialitate. Ea stabilește că contribuția utilă nu a necesitat transferul evidenței umane pentru reducerea distructivă în valoarea deținută de furnizor.

## Cântare platformă instalată

Un inventar de sistem de fișiere delimitat al arborelui aplicației instalate a numărat aproximativ 566.000 de fișiere și 218 GiB. Activele modelului au reprezentat aproximativ 172 GiB, dependențele și durata de execuție a limbii pentru 25 GiB, starea datelor și alte active pentru 20 GiB și sursa de implementare pentru aproximativ 184 MiB. Inventarul a întâmpinat unele intrări care nu pot fi citite sau se modifică, așa că acestea sunt estimări la scară operațională, mai degrabă decât o listă de materiale software.

Asimetria este o dovadă intenționată a arhitecturii. Codul sursă este o mică parte din amprenta instalată; Greutățile modelului și duratele de funcționare reutilizabile domină. Prin urmare, planul de control urmărește valoarea, autoritatea și costul de operare al fiecărui specialist, mai degrabă decât să trateze dimensiunea instalată ca capacitate. O viitoare lansare de cod distribuibil are nevoie de un inventar de dependență specific artefactelor, versiuni exacte, licențe, hashuri și limită reproductibilă de construcție.

## Lecții de inginerie păstrate prin proiectare

Dezvoltarea a produs mai multe lecții de inginerie durabilă:

- solicitarea unui model general pentru a simula un specialist dispărut;
- tratarea unui proces de ieșire sau a unui manifest auto-raportat ca dovadă a capacității;
- rularea discursului după clasificarea semantică și duplicarea muncii de specialitate;
- atribuirea primei apariții repetate a citatului ca proveniență;
- permiterea unui element de probă din întregul dosar să facă compoziția neverificabilă;
- tratarea relațiilor zero acceptate ca defecțiune a conductei;
- confundarea unei proiecții grafice deterministe cu un specialist executat separat;
- potrivirea unui profil de țesătură în timp ce produceți proză nesuportată sau ilizibilă;
- depanare cu execuții cu întreg corpus atunci când cazurile mici și medii au expus defectul;
- reglarea unui produs într-un mod care ar putea regresa pe altul.

Arhitectura publică păstrează aceste corecții pentru că explică scopul constrângerilor actuale și fac rafinarea viitoare mai fiabilă.

## Oportunități de dezvoltare actuale

Câteva capabilități majore rămân incomplete sau necesită dovezi mai ample:

- etichetele de relații au nevoie de o evaluare independentă a calității experților, nu doar structurală
  validare;
- legăturile temporale de depozit încrucișat și reatribuirea necesită testare continuă la nivel mai mare
  limite de surse mixte;
- șoferii personali de nivel înalt trebuie să rămână nepopulați până la dovezi legate de sursă și
  comportamentul lentilelor le justifică;
- diferite tipuri de produse necesită linii de asamblare calibrate, protejate împotriva regresiei;
- Feedback-ul privind protocolul uman necesită dovezi longitudinale ale rezultatelor;
- mecanismele figurative și narative necesită o evaluare conștientă de produs înainte
  se acordă autoritatea;
- documentația publică completă necesită o revizuire editorială continuă ca înregistrare privată
  evoluează.

## Scara de validare

Dezvoltarea continuă de la mic la mare:

1. schemă pură și dispozitive invariante;
2. exemple semantice scurte cu topologie cunoscută;
3. felii mici sursă reală;
4. felii de format mediu mixt și de timp mixt;
5. limite de scalabilitate mai mari după trecerea nivelurilor anterioare;
6. comparație creată de oameni versus generată de sistem sub aceleași dovezi,
  receptor, formă și buget.

Comparația diagnostichează dacă pierderea a venit din selecția graficului, alocarea importanței, reluarea înainte, realizarea sau lizibilitatea finală, mai degrabă decât atribuirea fiecărui defect la „calitatea modelului” generică.
