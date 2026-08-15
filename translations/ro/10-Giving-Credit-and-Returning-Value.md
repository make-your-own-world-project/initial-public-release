> Română: Traducere asistată automat a sursei autorizate în limba engleză. Corecțiile în limba maternă sunt binevenite. [engleză](../../README.md) | [Toate limbile](../README.md)

# Acordarea de credit și returnarea valorii

![Căi de cunoștințe atribuite care returnează hărți publice utile fără a le șterge sursele](../../assets/publish-reciprocity-open-paths.png)

Sistemul a fost asamblat independent de hardware în mare parte second-hand, resurse personale și efort substanțial în afara angajării. Fundamentul său intelectual a venit de la oameni și instituții dornici să publice lucrări pe care alții le-ar putea inspecta, testa, adapta în termenii ei, critica și pe care să le construiască. Atribuirea înregistrează așadar atât descendența tehnică, cât și o obligație reciprocă: lucrarea publică a făcut opera posibilă, iar ediția publică își returnează constatările mărginite fără a pretinde proprietatea asupra contextelor care le-au produs.

## De ce există acest registru

Lucrarea nu ar putea exista fără oameni care au ales să publice cercetări, să scrie și să întrețină software, să conserve opere culturale, să traducă texte, să organizeze corpuri, să opereze arhive și să-și pună munca la dispoziție pentru reutilizare sau studiu. Decizia lor de a împărți este un exercițiu de suveranitate. Disponibilitatea publică nu face contribuția lor anonimă sau fără proprietar.

Registrul înregistrează principalele contribuții utilizate în arhitectura publică. Acesta precizează ce a furnizat fiecare sursă, cum a fost utilizată și relația dintre sursă și acest proiect. Categoriile sunt importante:

- **dependență activă** înseamnă că software-ul sau modelul se execută pe o cale curentă;
- **metoda adaptată** înseamnă că o implementare folosește un mecanism publicat fără
  revendicarea codului original ca fiind creat de proiect;
- **sursa de calibrare** înseamnă că materialul a fost măsurat, nu a fost reprodus în public
  eliberare;
- **influența designului** înseamnă că lucrarea a schimbat o decizie arhitecturală;
- **evaluat sau respins** păstrează creditul și rezultatul unui experiment fără
  implicând adoptarea.

Nicio intrare nu implică faptul că autorii, întreținerii, comunitățile, editorii, arhivele sau instituțiile săi susțin acest proiect. Această documentație ZIP nu redistribuie codul, greutatea modelului, textul setului de date sau textul articolului.

## Fundamente literare, lingvistice și de comunicare

| Contribuţie | Sursă publică sau lucrare de identificare | Ce contribuie aici | Relaţie |
|---|---|---|---|
| Carlota S. Smith | *Moduri de discurs: Structura locală a textelor* | Distincții gramaticale între modurile de discurs; acceptă analiza de livrare tipizată. | Influența designului |
| M. A. K. Halliday și Ruqaiya Hasan | *Cohesion în engleză* | Separă coeziunea suprafeței de coerența reală. | Influența proiectării și baza de măsurare |
| M. A. K. Halliday | Înregistrați-vă ca câmp, tenor și mod | Tratează audiența și situația comunicativă mai degrabă ca dimensiuni măsurate decât ca o decorare promptă. | Influența designului |
| Douglas Biber | *Variație în vorbire și scriere* | Analiza registrului multidimensional folosind caracteristici observabile concomitente. | Linia de măsurare a țesăturii |
| William Mann și Sandra Thompson | Teoria Structurii Retorice | Relații discursive, nuclearitate și distincția dintre materialul central și materialul suport. | Linie activă de specialitate |
| John Swales | *Analiza de gen* | Mișcări retorice și pași utilizați pentru a descrie structura produsului. | Linia produs-contract |
| Gérard Genette și tradiția formalistă rusă | *Discurs narativ*; fabula si sjuzhet | Separă materialul evenimentului de ordinea și punctul de vedere al relatării acestuia. | Influență narativă și reconstrucție |
| H. P. Grice | „Logic și conversație” | Maximele de cooperare și diferența dintre încălcarea deliberată și încălcarea accidentală. | Protocol uman și proiectarea detectorului |
| Douglas Walton | Scheme de argumentare și întrebări critice | Oferă modele de provocare inspectabile, mai degrabă decât un punctaj de argument opac. | Influența argumentului-analiza |
| Alexandra Aikhenvald | *Evidență* | Tratează sursa și marcarea dovezilor ca pe o responsabilitate lingvistică. | Influența rolului epistemic |
| Claude Shannon | „O teorie matematică a comunicării” | Furnizează vocabularul formal de comunicare pentru informații, limitele canalului, redundanță și pierderi. | Influența arhitecturii de comunicare |
| Herbert Clark și Susan Haviland | Contract dat-nou | Sprijină măsurarea a ceea ce se presupune că știe un receptor și a ceea ce trebuie introdus. | Linia de măsurare a țesăturii |
| Morton Ann Gernsbacher | Structura-cadru de construire | Sprijină stabilirea, maparea și analiza coerenței orientate către receptor. | Influența protocolului uman |
| Benjamin Bloom; Lorin Anderson și David Krathwohl | Taxonomii obiective educaționale | Furnizează un vocabular delimitat în mod explicit pentru adâncimea așteptată a receptorului. | Influența audienței-contract |

Aceste lucrări au furnizat metode și întrebări, nu răspunsuri universale despre o persoană. Contribuția arhitecturală este de a conecta mecanismele lor delimitate la o linie de asamblare care păstrează proveniența și de a menține fiecare inferență reversibilă și inspectabilă.

## Selectare, editare și realizare

| Contribuţie | Sursă publică | Ce contribuie aici | Relaţie |
|---|---|---|---|
| Jaime Carbonell și Jade Goldstein | „Utilizarea MMR, reclasificarea bazată pe diversitate pentru reordonarea documentelor și producerea de rezumate” | Echilibrează relevanța și noutatea în timpul selecției limitate. | Metoda adaptata |
| Hui Lin și Jeff Bilmes | Rezumat submodular la buget | Selecție cu rentabilitate descrescătoare în cadrul unui buget explicit. | Metoda adaptata |
| Eric Malmi, Sebastian Krause, Sascha Rothe, Daniil Mirylenka și Aliaksei Severyn | LaserTagger | Demonstrează o editare restrânsă cu un vocabular de inserare închis. | Influența proiectată evaluată |
| Kostiantyn Omelianchuk, Vitaliy Atrasevych, Artem Chernodub și Oleksandr Skurzhanskyi | GECToR | Demonstrează transformări etichetate și corecție iterativă. | Influența proiectată evaluată |
| Jonathan Mallinson, Jakub Adamek, Eric Malmi și Aliaksei Severyn | EditT5 | Demonstrează reordonarea bazată pe pointeri care limitează invenția. | Influența proiectată evaluată |
| Eric Malmi și colaboratorii; comunitatea mai largă de realizare a suprafeței | Lucrări de realizare bazate pe gramatică, grafic-la-text și constrânse | Consolidează separarea determinării, planificarii, realizării și verificării conținutului. | Influența arhitecturii; nicio adoptare generală a timpului de execuție |

## Specialiști în raționament, discurs și verificare

| Contribuţie | Sursă publică | Ce contribuie aici | Relaţie |
|---|---|---|---|
| Elena Chistova și colaboratorii IsaNLP | [Card model IsaNLP RST Parser v3](https://huggingface.co/tchewik/isanlp_rst_v3)și lucrările sale ACL citate; cardul model înregistrează CC BY-NC 4.0 | Produce structuri de discurs mărginite și candidați de relație. Nu determină sensul personal. | Specialist activ; modelul este utilizat în limitele licenței sale necomerciale și nu este redistribuit aici |
| Shon Otmazgin, Arie Cattan, Yoav Goldberg și colaboratorii FastCoref | [Lucrare F-COREF și implementare oficială](https://github.com/shon-otmazgin/fastcoref), MIT | Produce lanțuri de coreferență candidate pentru validarea ulterioară la sursă. | Specialist activ |
| Chris Reed, grupul ARG-tech, colaboratori AIF/xAIF și colaboratori AMF/ARI | [Registrul modulului oAMF](https://github.com/arg-tech/oAMF),[Setul de date AIF și modelul de registru](https://github.com/arg-tech/aif-arg-datasets), și specificațiile legate | Clasifică relațiile de propoziție mărginite și furnizează vocabular interoperabil argument-grafic. | AMF/ARI este o descendență activă de specialitate; oAMF a fost evaluată ca stadiul tehnicii de orchestrare, mai degrabă decât a fost adoptat cu ridicata |
| Liyan Tang, Philippe Laban și Greg Durrett | [MiniCheck](https://aclanthology.org/2024.emnlp-main.499/);[cod oficial](https://github.com/Liyan06/MiniCheck) | Observații eficiente de fapt asupra cererilor și documentelor de întemeiere. | Specialist evaluat; nu eliberează autoritatea |
| Deren Lei, Yaxi Li, Siyao Li, Mengya Hu, Rui Xu, Ken Archer, Mingyu Wang, Emily Ching și Alex Deng | [FactCG](https://aclanthology.org/2025.naacl-long.258/);[cod oficial](https://github.com/derenlei/FactCG) | Observații de fapte multi-hop informate grafic. | Specialist evaluat; nu eliberează autoritatea |
| Philippe Laban, Tobias Schnabel, Paul N. Bennett și Marti A. Hearst | [SummaC](https://aclanthology.org/2022.tacl-1.10/) | Expune problemele de granularitate a propoziției/documentului în verificarea coerenței. | Influența designului |
| Lorena Scirè, Simone Conia și Roberto Navigli | [GARDĂ](https://arxiv.org/abs/2403.02270) | Extragerea revendicărilor și alinierea dovezilor pentru evaluarea rezumativă. | Influența designului |
| Xiangkun Hu și colaboratori | [RefChecker](https://github.com/amazon-science/RefChecker) | Sprijin cu granulație fină, respingere și înregistrări necunoscute. | Influența proiectată evaluată |
| Trieu H. Trinh și colaboratori | [AlphaGeometry](https://github.com/google-deepmind/alphageometry) | Închidere monotonă a deducției și urme explicite de dependență de dovezi. Nu se folosesc reguli de geometrie. | Influența designului |

MiniCheck și FactCG au fost evaluate cu revizuiri publice fixate și licențele lor publicate. Scorurile lor nu au fost separabile pe mutații importante în formă de proiect, așa că au fost eliminate de la autoritatea de eliberare. Păstrarea acestui rezultat negativ face parte din reciprocitate: instrumentele sunt creditate pentru ceea ce pot observa fără a denatura ceea ce autorii lor au susținut că ar putea dovedi.

## Colaboratori de software

Următoarele proiecte software publice oferă mașini delimitate. Notificările și licențele privind drepturile de autor respective guvernează orice redistribuire a codului lor; această documentație publică nu o redistribuie.

| Software | Colaboratori sau administrator | Licență înregistrată | Rol mărginit |
|---|---|---|---|
| spaCy și modelele sale de limbaj | Explosion AI, Matthew Honnibal, Ines Montani și colaboratori | MIT | Parte de vorbire, morfologie, analiza dependenței și măsurători structurale |
| BlingFire | Microsoft și colaboratorii | MIT | Segmentarea propoziției |
| LemmInflect | Brad Jascob și colaboratorii | MIT | Inflexiune engleză |
| submodlib | Vishal Kaushal, Rishabh Iyer, Ganesh Ramakrishnan și colaboratori DECILE | MIT | Selectie submodulara |
| NLTK | Steven Bird, Edward Loper, Ewan Klein și colaboratori | Apache-2.0 | Acces corpus și utilități lingvistice |
| NumPy | Colaboratori NumPy | BSD-3-Clauza | Rețele numerice și matrice de similaritate |
| SciPy | Colaboratori SciPy | BSD-3-Clauza | Clustering și operațiuni statistice |
| NetworkX | Colaboratori NetworkX | BSD-3-Clauza | Operații și măsurători grafice direcționate |
| îngenunchează | Kevin Arvai și colaboratori | BSD-3-Clauza | Detectarea punctului genunchiului pentru curbele de calibrare măsurate |
| PyYAML | Kirill Simonov și colaboratori | MIT | Schimb de configurații structurate |
| httpx | Tom Christie și colaboratorii | BSD-3-Clauza | Transport HTTP la limita serviciului |
| psihologic | Daniele Varrazzo și colaboratori | LGPL-3.0 | Acces PostgreSQL |
| Pydantic | Colaboratori pidantici | MIT | Validare și serializare tip |
| OpenVINO | Intel și colaboratori | Apache-2.0 | Inferența modelului limitat acolo unde a fost configurată |
| textdescriptive | Lasse Hansen, Kenneth Enevoldsen și colaboratori | Apache-2.0 | Lizibilitate, coerență și măsurători teoretice informaționale |
| LFTK | Bruce W. Lee și Jason Hyung-Jong Lee | Licență publică de proiect; verificați cu orice versiune redistribuită | Extragerea caracteristicilor lingvistice evaluată pentru calibrare |

Tabelul este un inventar principal, nu un substitut pentru notificările de dependență generate de mașină într-o distribuție de cod viitoare. Versiunile exacte, hashe-urile, licențele tranzitive și textele complete ale licențelor trebuie să însoțească orice versiune care redistribuie fișiere software sau model.

## Lucrări culturale, corpuri, arhive și comunități

Analiza măsoară modelele de livrare și proprietățile structurale. Cu excepția cazului în care o licență separată permite reproducerea, rezultatul public conține măsurători agregate și identități sursei, nu textul sursă.

| Sursă | Persoane sau instituții care sunt creditate | Limită de permis și utilizare | Contribuţie |
|---|---|---|---|
| Proiectul Gutenberg | Michael S. Hart, corectori distribuiti, autori participanți, editori, traducători și voluntari | Sunt măsurate textele din domeniul public verificate; Termenii și marca comercială ale ediției Project Gutenberg rămân respectate. | Calibrare literară de lungă durată și forma produsului |
| LibriVox | Cititori voluntari, menținerii și autorii textelor sursă din domeniul public | LibriVox înregistrează texte din domeniul public și își dedică înregistrările domeniului public conform politicii sale. | Calibrarea candidaților-livrare vorbită; nu adunate în tăcere cu tipărirea |
| Corpus brun | W. Nelson Francis, Henry Kučera, Universitatea Brown și curatori | Folosit prin termenii corpus distribuit pentru măsurarea agregată. | Contraste de registru etichetate pe gen |
| Reuters-21578 | Reuters, David Lewis și curatori | Măsurătorile agregate numai conform condițiilor de distribuție a setului de date. | Comparație densă de copiere a firului |
| Corpus de chat NPS | Eric Forsyth, Jane Lin, Craig Martell și Școala Postuniversitară Navală | Măsurarea agregată; textul personal nu este reprodus public. | Comparație prin chat de la om la om |
| Declarația Universală a Drepturilor Omului traduceri | OHCHR al Națiunilor Unite și traducători | Translațiile paralele măsurate ca control; atribuirea reținută. | Separă modelele de protocol în mai multe limbi de obiceiurile engleze |
| arXiv | Universitatea Cornell, arXiv, autori și menținători | Metadatele sunt tratate conform termenilor publicati; rezumatele rămân opera autorilor și nu sunt reproduse. | Măsurare longitudinală științifică-registru |
| PubMed/MEDLINE | Biblioteca Națională de Medicină din SUA, reviste participante și autori | Doar măsurare agregată; rezumatele nu sunt redistribuite și nu este implicită aprobarea NLM. | Comparația proză științifică |
| Delpher | Koninklijke Bibliotheek, colaboratori la digitalizare, editori și autori | Măsurare agregată numai deoarece drepturile la nivel de articol variază. | Comparația ziarelor de lungă durată |
| Wikipedia | Fundația Wikimedia și editori colaboratori | sursa CC BY-SA; niciun text al articolului nu este reprodus în această publicație. | Comparația registrului enciclopediei |
| Depășirea stivei | Stack Exchange și comunitatea de răspuns | sursa CC BY-SA; nici un text al postării nu este reprodus aici. | Comparație forum-răspuns |
| Hacker News și mostre Mastodon | Operatori de platformă și autori individuali ai comunității | Nu se presupune nicio licență de conținut general; sunt publicate numai observațiile agregate neidentificative. | Comparație exploratorie în format modern |

Revenirea reciprocă a proiectului public nu este deținerea acestor lucrări. Este un raport auditabil al metodelor pe care le-au activat, granițele găsite, ipotezele eșuate pe care le-au ajutat să le falsifice și măsurători reutilizabile care păstrează o cale de întoarcere către contribuatorii lor.

Reciprocitatea guvernează și utilizarea modelului extern. Furnizarea unei sarcini de lucru autorizate pentru o contribuție limitată nu face ca serviciul extern să fie proprietarul corpusului menținut, la fel cum utilizarea cercetării publicate nu șterge autoritatea acestuia. Contribuția trebuie creditată și măsurată, în timp ce sursa, autoritatea și valoarea continuă a înregistrării subiacente rămân distincte. Reciprocitatea împiedică derivarea utilă să devină o scuză pentru a distruge contextul uman și pentru a-și concentra valoarea în interiorul instituției primitoare.

## Limită de drepturi și integralitate

Starea domeniului public, accesul deschis, sursa deschisă și permisiunea pentru analiza computațională sunt stări diferite ale drepturilor. Registrul înregistrează baza aplicabilă, în loc să trateze „disponibil online” ca o permisiune. Sursele care necesită ocolire, autorizare incertă sau o teorie a utilizării loiale nerevizuite sunt excluse din noile seturi de date de publicare.

Registrul acoperă principalele fundații vizibile în documentația publică. Proiectul privat menține un inventar mai mare în evoluție, inclusiv candidații evaluați și respinși. O viitoare versiune academică sau software trebuie să producă o listă de materiale exactă a software-ului specific artefactului, un registru al modelului și al setului de date, bibliografie, pachetul de licențe și înregistrarea transformării. Omiterea din acest rezumat nu șterge creditul sau acordă permisiunea.
