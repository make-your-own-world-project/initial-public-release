> Polski: Wspomagane maszynowo tłumaczenie wiarygodnego źródła w języku angielskim. Mile widziane poprawki w języku ojczystym. [angielski](../../README.md) | [Wszystkie języki](../README.md)

# Co teraz działa

![Lokalna maszyneria zorganizowana według odpowiedzialności wokół wspólnego, kontrolowanego szkieletu](../../assets/public-machinery-catalog.png)

## Jak czytać ten katalog

Katalog jest publicznym odpowiednikiem widoku Datacenter w Kontroli Misji. Opisuje, co wnosi każdy trybik i co zostałoby utracone, gdyby zniknął, bez publikowania prywatnych adresów, układu maszyny, danych uwierzytelniających, ścieżek plików ani rytmu działania. Wykres na żywo pozostaje operacyjnym źródłem prawdy.

Status komponentu ma znaczenie. Narzędzie może być aktywne, zachowane jako system źródłowy, ocenione, ale nie przyjęte, lub może być wycofanym poprzednikiem. Obecność w tym katalogu nie przyznaje komponentowi uprawnień wykraczających poza jego określoną rolę.

Zasada ta obejmuje zdolność na granicach zewnętrznych. Kiedy jest używany, zajmuje ograniczoną stację i otrzymuje specjalnie skonstruowany ładunek zamiast nieograniczonego dostępu do utrzymywanego korpusu. Ładunek obsługuje zadeklarowaną operację, ale pomija stan trwały potrzebny do zrekonstruowania szerszego systemu lub niezależnego wygenerowania przyszłych wypłat. Stacja otrzymuje pracę, a nie opiekę nad danymi ludzkimi, z których scentralizowana instytucja mogłaby wydobyć trwałą wartość.

## Drogi do i wokół systemu

### Mózg robota (LibreChat)


**Odpowiedzialność.** Zapewnij wymienne okno rozmowy zwrócone w stronę człowieka. Przenosi żądania i odpowiedzi, podczas gdy trwała pamięć, odzyskiwanie, rozumowanie i weryfikacja pozostają w usługach pod nim.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

**Główne narzędzia publiczne.**[LibreChat](https://github.com/danny-avila/LibreChat),[Node.js](https://github.com/nodejs/node)

### Rozdzielacz konwersacji


**Odpowiedzialność.** Powiadomienia, gdy rozmowa zamieniła się w dwa tematy i zaproponowanie osobnego zgłoszenia gotowego.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

**Główne narzędzia publiczne.**[FastAPI](https://github.com/fastapi/fastapi)

### Kontrola Misji


**Odpowiedzialność.** Okno na maszynę: co działa, co wymaga uwagi i co aktualnie robi. Na tej granicy publikacji strona stanu przedstawia wszystkie monitorowane systemy działające w instalacji lokalnej.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Stan operacyjny informuje o stanie usługi; zaakceptowane artefakty i potwierdzenia ustanawiają oddzielne granice wykonania i dowodów semantycznych.

**Główne narzędzia publiczne.**[FastAPI](https://github.com/fastapi/fastapi),[Grafwiz](https://gitlab.com/graphviz/graphviz),[Psychopatyk](https://github.com/psycopg/psycopg)

### Semantyczny router


**Odpowiedzialność.** Kieruj ograniczone żądania do odpowiedniego lokalnego silnika i wymagaj wyraźnej autoryzacji przed użyciem wnioskowania zewnętrznego. Drogie możliwości są wybierane tylko wtedy, gdy żądanie uzasadnia zmierzony koszt.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

**Główne narzędzia publiczne.**[FastAPI](https://github.com/fastapi/fastapi). Envoy i vLLM Semantic Router pozostają zapisane w indeksie źródłowym jako sprawdzone lub wycofane poprzedniki, a nie bieżące zależności wykonawcze.

### Pełne historie agentów


**Odpowiedzialność.** Zachowaj kompletne, uporządkowane strumienie zdarzeń agentów jako dowód interakcji, w tym zwroty ludzi, zwroty asystentów, narzędzia, błędy i poprawki. Historie odnotowują, co się wydarzyło; nie zamieniają oświadczeń agentów w zweryfikowane fakty.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Dostarcza tylko to, co określa jego źródło i pochodzenie; Dalsza interpretacja pozostaje odrębna.

### Dokumenty projektowe


**Odpowiedzialność.** Zachowaj prywatny projekt, dowody i zapisy projektu, które wyjaśniają, dlaczego platforma istnieje i jak zmieniła się jej architektura. Produkty publiczne korzystają ze sprawdzonych instrumentów pochodnych, zamiast ujawniać lokalizację prywatnego dokumentu.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Dostarcza tylko to, co określa jego źródło i pochodzenie; Dalsza interpretacja pozostaje odrębna.

### Vikunja


**Odpowiedzialność.** Zachowaj zewnętrzny system zadań jako niezależne źródło starsze niż platforma. Integracja może odczytywać autoryzowane dowody zadań bez wchłaniania systemu zadań do korpusu lub zmiany jego cyklu życia.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Dostarcza tylko to, co określa jego źródło i pochodzenie; Dalsza interpretacja pozostaje odrębna.

**Główne narzędzia publiczne.**[Vikunja](https://github.com/go-vikunja/vikunja)

## Konserwacja i odzyskiwanie

### Przyjmowanie wiedzy


**Odpowiedzialność.** Sposób, w jaki sprawy docierają. Upuść dokument, eksport, plik notatek, a wylądują one w miejscu, które można znaleźć, a nie nigdzie.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

### MongoDB


**Odpowiedzialność.** Prowadzi rozmowy zgodnie z ich przebiegiem.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Dostępność i integralność są niezbędne; przechowywane dane same się nie interpretują i nie weryfikują.

**Główne narzędzia publiczne.**[MongoDB](https://github.com/mongodb/mongo)

### PostgreSQL


**Odpowiedzialność.** Przechowuj trwałą, ustrukturyzowaną dokumentację projektu, stan pochodny i indeksy wyszukiwania, które mają przetrwać wymienne usługi aplikacyjne. Przechowywane zapisy zachowują odrębny autorytet i pochodzenie, a nie stają się jedną niezróżnicowaną pamięcią.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Dostępność i integralność są niezbędne; przechowywane dane same się nie interpretują i nie weryfikują.

**Główne narzędzia publiczne.**[PostgreSQL](https://github.com/postgres/postgres),[pgwektor](https://github.com/pgvector/pgvector)

## Rozumowanie i rekonstrukcja

### Klasyfikator relacji argumentów

przypięty AMF_ARI Klasyfikacja procesora OpenVINO pod kątem wnioskowania, konfliktu, przeformułowania lub braku związku

**Odpowiedzialność.** Klasyfikuj związek pomiędzy dwoma dostarczonymi propozycjami; nie tworzy żadnej propozycji ani nie wnioskuje o motywach osobistych. Przykład: rozróżnij jedno stwierdzenie potwierdzające drugie od tego, które mu zaprzecza lub nie zwracaj żadnej obsługiwanej relacji.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

**Główne narzędzia publiczne.**[Model AMF ARI RoBERTa OpenVINO](https://huggingface.co/arg-tech/amf-ari-roberta-ov-int8)

### Artefakty ludzkie


**Odpowiedzialność.** Zdefiniuj produkty skierowane do człowieka, które może wyprodukować linia montażowa. Każdy produkt ma własnego odbiorcę, cel, strukturę, politykę dowodową i umowę dostawy, a nie ma wspólnego ogólnego zarysu.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

### Uziemienie + weryfikacja dostawy

niezależna bramka odbiorcza sprawdzająca wierność, pochodzenie, utratę, inwencję, splot i zrozumienie

**Odpowiedzialność.** Niezależnie sprawdź, czy artefakt zachowuje wspierane znaczenie i spełnia zadeklarowaną umowę dostawy przed wypuszczeniem. Przykład: odrzuć czytelny akapit, który formułuje wnioski, i osobno odrzuć ugruntowany dokument, którego struktura jest nieczytelna dla docelowego czytelnika.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

### Rozdzielczość publiczności

stan odbiorcy, wymagania wstępne, rejestr i znaczenie

**Odpowiedzialność.** Opisz, co odbiorca ma wiedzieć, potrzebować i tolerować, zachowując jednocześnie jasne założenia. Przykład: poproś przewodnika właściciela domu o wyjaśnienie pH przed użyciem skrótów znanych technikowi basenowemu.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

### Zwinięcie całego drzewa + pakiety

podział ograniczony kontenerem, selekcja, zyski i straty

**Odpowiedzialność.** Wybierz i zrównoważ to, co pasuje do żądanego artefaktu, rejestrując jednocześnie to, co zostało pominięte i zachowując znaczący kształt drzewa. Przykład: umieść każdą główną gałąź w artykule zawierającym 1000 słów, zamiast pozwalać, aby największa gałąź źródłowa pochłonęła cały budżet.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

**Główne narzędzia publiczne.**[submodlib](https://github.com/decile-team/submodlib),[kolanem](https://github.com/arvkevi/kneed)

### Kompaktowy model roboczy

przenośny nośnik o zasięgu żądań dla wybranych jednostek, relacji, trajektorii, bloków źródłowych, planów, uchwytów i ksiąg przekazania

**Odpowiedzialność.** Spakuj wybrane fakty, relacje, chronologię, niepewność, awarie i uchwyty źródeł w przenośny kontekst specyficzny dla danego zadania. Przykład: podaj edytorowi łańcuch konserwacji puli i wyjaśnij, dlaczego jego etapy łączą się bez ładowania całego korpusu lub usuwania łączy.

**Należy zachować.** source_spans; id_relacji; chronologia; niepewność; awarie; usunięcie się; niewiadome

**Kształt zasobu.** Procesor i pamięć RAM proporcjonalne do ograniczonego wyboru; bez procesora graficznego i leasingu

**Granica.** Jakość jest ograniczona relacjami z wydobyciem i pokryciem stanu depozytu

### Mechanika dostaw

rejestr, tryby, profile splotu, tempo, gęstość i elementy sterujące deslop

**Odpowiedzialność.** Dostarczaj mierzone ograniczenia dostawy, takie jak tempo, gęstość, rejestr i trajektoria splotu, dla tego produktu i odbiorców. Przykład: podaj wyjaśnienia dla dzieci, krótsze pakiety i inny schemat powtarzania niż raport techniczny, bez zmiany leżących u ich podstaw faktów.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

### Wstępne przetwarzanie dyskursu

dokładnie ograniczone wycinki, kandydaci referencji FastCoref i dzierżawione łącza operandów isanlp RST

**Odpowiedzialność.** Identyfikuj potencjalne odniesienia i zakresy dyskursu przed klasyfikacją rozumowania, zachowując dokładne współrzędne źródła. Przykład: połącz „to” z wymienionym kandydatem na pompę i ujawnij dwie klauzule połączone przyczynową relacją dyskursu.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

**Główne narzędzia publiczne.**[IsaNLP RST](https://github.com/tchewik/isanlp_rst),[FastCoref](https://github.com/shon-otmazgin/fastcoref)

### Rekonstrukcja naprzód całego artefaktu

warunki wstępne, odniesienia, klej przyczynowy, progresja, wprowadzenie i zakończenie

**Odpowiedzialność.** Odbuduj wybrany materiał w kolejności czytelnika, przywracając warunki wstępne, odniesienia, powiązania przyczynowe, postęp i uczciwe zakończenie. Przykład: wprowadź cel przed procedurą i zamknij nierozwiązaną kwestię, gdy nie ma żadnych wniosków.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

### Wykres dlaczego i projekcja zależności

deterministyczny pogląd na sklasyfikowane krawędzie grafów, który nie może wprowadzać nowych twierdzeń rozumowania

**Odpowiedzialność.** Przekładaj przyjęte krawędzie relacji na możliwe do sprawdzenia zależności i dlaczego poglądy bez dodawania interpretacji. Przykład: pokaż, że wniosek B zależy od przesłanki A, ponieważ istnieje dokładnie sklasyfikowana krawędź.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

**Główne narzędzia publiczne.**[SiećX](https://github.com/networkx/networkx)

### Uziemiona interaktywna odpowiedź


**Odpowiedzialność.** Prześlij odpowiedź konwersacyjną z odpowiednim uzasadnieniem, pochodzeniem, niepewnością i ścieżkami ekspansji. Ścieżka odpowiedzi może obejmować pełne rozmowy i cykle życia dowodów, nie udając, że jest to proces generowania dokumentów.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

### Most protokołu ludzkiego

kodowanie zorientowane na odbiornik stałego obsługiwanego ładunku

**Odpowiedzialność.** Przekształć ustalony, obsługiwany ładunek w formę, którą zamierzona osoba może zastosować, korzystając z umowy dotyczącej produktu i wymierzonego wzorca dostawy; nie może zmienić dowodów. Przykład: zamień ten sam ugruntowany łańcuch rozumowania w zwięzły e-mail lub etapowy przewodnik, zmieniając strukturę przekazu, a nie wnioski.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

### Interaktywny zespół kontekstowy


**Odpowiedzialność.** Stwórz ograniczony wykres dowodów i uzasadnień dla bieżącego pytania, zachowując chronologię, poprawki, awarie, tożsamość źródła i autoryzację. Dostarcza kontekst odpowiedzi bez spłaszczania korpusu we fragmentach wyszukiwania.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

### Bezstratne przystąpienie


**Odpowiedzialność.** Przed interpretacją dopuszczaj oryginalne bajty i zdarzenia natywne, zapisując jedynie zaobserwowane fakty dotyczące przybycia. Opisy, znaczniki czasu wywnioskowane z treści, tożsamości i relacji pozostają oddzielnymi obserwacjami wersjonowanymi.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

### Podstawowy dowód


**Odpowiedzialność.** Przechowuj wiarygodne depozyty, z których muszą wynikać późniejsze oświadczenia i produkty. Ich istnienie trwa nawet wtedy, gdy system nie jest jeszcze w stanie wyjaśnić ich znaczenia lub związku.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

### Ukończ tymczasowe drzewo

pełne dowody wstępne, struktura zależności, alternatyw i niepowodzeń

**Odpowiedzialność.** Przechowuj pełne drzewo kandydatów o zasięgu żądań, w tym alternatywy, niepowodzenia, niewiadome i zastąpione widoki, aby zwinięcie mogło zobaczyć, co by straciło. Przykład: przed wybraniem materiału na przewodnik należy zachować zarówno nieudaną obróbkę, jak i późniejszą korektę.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

### Wykres rozumowania

chronologia, relacje typowane, cykle życia roszczeń, niepowodzenia i niepewność

**Odpowiedzialność.** Utrzymuj mapę propozycji, chronologii, prób, wyników, konfliktów, zależności i niepewności, ograniczoną do żądania. Przykład: połącz nieudane leczenie z korekcją, która je zastąpiła, nie usuwając żadnego ze stanów.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

### Żądanie + Umowa na Artefakt

cel, odbiorca, pojemnik, kanał, budżet i prawdziwość

**Odpowiedzialność.** Zamroź cel, odbiorcę, produkt, kanał, budżet i standard prawdy, aby każdy trybik na dalszym szczeblu łańcucha dostaw wykonywał to samo zadanie. Przykład: przed rozpoczęciem selekcji dowodów odróżnij wyjaśnienie dla ogólnego czytelnika składające się z 500 słów od raportu o incydencie technicznym.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

### Odwrotna ekspansja

zbieraj do tyłu bez przycinania; zmierzyć wkład krańcowy

**Odpowiedzialność.** Przejdź od prośby lub późniejszych dowodów do wcześniejszych powiązanych zapisów i zbierz całą podróż kandydata, zanim cokolwiek zostanie odrzucone. Przykład: prześledź aktualne pytanie dotyczące glonów, przeglądając wcześniejsze zapisy dotyczące pH, wielkości basenu, konserwacji i kontekstu użytkowania.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

### Wpisane ruchy retoryczne

zadania semantyczne i zależności, nigdy nie nagłówki podciągów

**Odpowiedzialność.** Przydziel każdej wybranej jednostce zadanie komunikacyjne i zależność w oparciu o umowę dotyczącą produktu, a nie pasujące słowo nagłówkowe. Przykład: oznacz dowody jako potwierdzające twierdzenie, a niepowodzenie jako rozpoczęcie odzyskiwania, zamiast nazywać oba „istotą”.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

### Rekonstrukcja semantyczna

byty, propozycje, epizody, próby, wyniki i pytania

**Odpowiedzialność.** Konwertuj obserwacje źródłowe na przypisane obiekty semantyczne bez decydowania o ich ostatecznym znaczeniu i prezentacji. Przykład: przedstaw proponowaną poprawkę, próbę, jej niepowodzenie i pozostałe pytanie jako osobne połączone rekordy.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

### Wersjonowane reprezentacje


**Odpowiedzialność.** transkrypcje, struktura, tekst, OCR, układ i widoki pochodne

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

### Dlaczego to miało znaczenie

przypisana motywacja, troska, konsekwencja i aktualne znaczenie

**Odpowiedzialność.** Należy przedstawić bezpośrednie i wyraźnie przypisane dowody na to, dlaczego zwrócono uwagę, pozostawiając nieuzasadnione powody nieznane. Przykład: utrzymuj, że zadanie konserwacyjne miało znaczenie, ponieważ chroniło ludzi korzystających ze wspólnego sprzętu, jeśli jest to udokumentowane, zamiast zgadywać ten motyw na podstawie wyłącznie kwestii technicznych.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

### Rozumowanie + silnik artefaktów

rekonstrukcja z bramką pokwitowań, załamanie, protokół ludzki i renderowanie atomowe Markdown

**Odpowiedzialność.** Koordynacja ograniczonej ścieżki rekonstrukcji i renderowania oraz udostępnianie potwierdzeń każdego etapu; nie zastępuje specjalistycznej oceny. Przykład: przeprowadź żądanie utworzenia przez wybór, planowanie, realizację, sprawdzanie poprawności i zapis niepodzielny.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

### Menedżer ds. montażu i możliwości

cofa wymagane pola, wycenia wymagania wstępne, wybiera prawdziwych specjalistów, zamawia fale zależności i pomija pracę o zerowej wartości

**Odpowiedzialność.** Wybieraj, którzy specjaliści są potrzebni, w jakiej kolejności działają i jaka praca nie wnosi wartości dodanej; nie spełnia swoich zadań. Przykład: zaplanuj realizację relacji przed realizacją zdania i pomiń niedostępny zabieg stylistyczny, który nie wnosi nic wymaganego.

**Należy zachować.** must_preserve_fields; linia_pola; wyraźna_niedostępność

**Kształt zasobu.** Procesor; niska pamięć; bez procesora graficznego i leasingu

**Granica.** Obserwacje kosztów i wartości ujawniają decyzje, ale nigdy nie definiują znaczenia ludzkiego

### Uzgadniacz budżetu przewoźnika atomowego

mierzy niepodzielne źródło, klej i nośniki relacji przed realizacją i redystrybuuje ustalony budżet całego produktu poprzez prawdziwy luz sekcji

**Odpowiedzialność.** Sprawdź, czy niepodzielne fakty i nośniki relacji zmieszczą się w każdej sekcji, a następnie przesuń tylko dostępny luz, zachowując przy tym całkowity budżet dokumentu. Przykład: powiększ sekcję procedury zawierającą 90 słów, zawierającą wymaganą instrukcję atomową zawierającą 120 słów, zapożyczając nieużywane słowa z innej sekcji.

**Należy zachować.** cały_artifact_budget; wymagane_retoryczne_prace; autorytet_źródłowy; wykres_kształt

**Kształt zasobu.** Procesor; czas działania prawie zerowy; zapobiega marnowaniu pracy procesora graficznego/modelu/weryfikatora Stage 8

**Granica.** nie może streścić niepodzielnego zdania; kończy się niepowodzeniem, jeśli wszyscy wymagani przewoźnicy przekraczają zadeklarowany budżet produktu

### Menedżer ponownego wiązania powiązanego ze źródłem

przenosi tylko całkowicie odizolowany oddział, gdy przypisane mu zadanie produktu jest niezgodne, a jedno miejsce docelowe jest w sposób możliwy do udowodnienia kompatybilne

**Odpowiedzialność.** Przenieś kompletną, izolowaną gałąź materiału dowodowego do tej sekcji, której praca może legalnie z niej skorzystać, odmawiając jednocześnie niejednoznacznych lub powiązanych ze sobą ruchów. Przykład: przypisz samodzielną notatkę dotyczącą odzyskiwania z konfiguracji do rozwiązywania problemów bez duplikowania jej w obu sekcjach.

**Należy zachować.** tożsamość_gałęzi; zakres_źródła; id_relacji; marginal_gain_ledger

**Kształt zasobu.** Procesor; niskie opóźnienia; bez procesora graficznego i leasingu

**Granica.** odrzuca ruchy związane z relacjami, niejednoznaczne, częściowe lub związane z nadmierną wydajnością

### Realizator relacji obejmujących cały dokument

zamienia akceptowane krawędzie rozumowania tego samego przekroju i przekroju poprzecznego w zwarty, niezależnie odtwarzalny język łącznikowy bez powtarzania obu argumentów

**Odpowiedzialność.** Zamień zaakceptowane relacje grafów na krótki, spójny język, zachowując jednocześnie możliwość niezależnego odtwarzania kierunku, argumentów i zakresów źródłowych. Przykład: zrozum A-przyczyny-B jako ograniczony most przyczynowy, zamiast drukować A i B jako niepowiązane, sąsiadujące ze sobą fakty.

**Należy zachować.** kierunek_relacji; operand_identity; dokładne_rozpiętości_nośnika; zakres_źródła; linia_sekcji

**Kształt zasobu.** Procesor; czas działania prawie zerowy; bez procesora graficznego i leasingu

**Granica.** realizuje tylko jawnie akceptowane rodzaje relacji; zwarte mostki zachowują tożsamość krawędzi wpisanej, ale pozostają sformułowane mechanicznie; krawędzie tego samego nośnika, niejednoznaczne, ukryte i nieznane pozostają widoczne na wykresie, ale nie są potwierdzone jako proza

### Silnik wiedzy


**Odpowiedzialność.** Koordynuj przystąpienie, pochodne reprezentacje, poszukiwania, pochodzenie i trwałe miejsca pracy bez łączenia tych obowiązków w jeden stan prawdy. Udostępnia konsumentom obsługiwane interfejsy, podczas gdy podstawowe dowody pozostają niezależne.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

### Mikroplaner wpisanych klauzul / zdań

przypisuje nośniki powiązane ze źródłem do wpisywanych na maszynie zadań retorycznych i kompiluje plany zdań, zdań i akapitów

**Odpowiedzialność.** Podziel zatwierdzone znaczenia i relacje na zdania, zdania i zadania akapitowe, zachowując jednocześnie ich powiązania źródłowe; nie wymyśla sformułowań ani twierdzeń. Przykład: zaplanuj klauzulę przyczynową, po której następuje jej konsekwencja i przejście dla realizatora powierzchni.

**Należy zachować.** semantic_unit_ids; id_relacji; formularze źródłowe

**Kształt zasobu.** Procesor; niskie opóźnienia; bez procesora graficznego i leasingu

**Granica.** nie wymyśla brakującej propozycji ani nie naprawi niesklasyfikowanego związku

**Główne narzędzia publiczne.**[spaCy](https://github.com/explosion/spaCy),[BlingFire](https://github.com/microsoft/BlingFire)

### Menedżer ds. kontraktów produktowych

konwertuje gatunek, odbiorcę, cel, kanał, prawdziwość, uwagę i budżet na wymagane pola produktu i pracę retoryczną

**Odpowiedzialność.** Zmień żądanie w konkretną listę kontrolną gotowego produktu, bez wybierania dowodów i ich pisania. Przykład: w przypadku podręcznika użytkownika wymagaj wymagań wstępnych, uporządkowanych działań, wskazówek dotyczących odzyskiwania i zamknięcia przed uruchomieniem dowolnego edytora.

**Należy zachować.** zadeklarowany_cel; odbiornik; prawdziwość; kanał

**Kształt zasobu.** Procesor; czas działania prawie zerowy; bez procesora graficznego i leasingu

**Granica.** nie wnioskuje o znaczeniu źródłowym ani nie wybiera faktów

### Realizator powierzchni kontraktowych

stosuje ograniczoną gramatykę, morfologię, typografię, perspektywę i transformacje maszynowe do jednostek dostawy

**Odpowiedzialność.** Stosowanie gramatyki, morfologii, typografii i dozwolonej perspektywy do już zatwierdzonego planu; nie może decydować o nowym znaczeniu. Przykład: zamień zapisany na maszynie plan rozkazujący w instrukcję gramatyczną bez dodawania nigdy nie dostarczonego oświadczenia dotyczącego bezpieczeństwa.

**Należy zachować.** Claim_authority; powiązania_źródłowe i_relacyjne; retoryczna_zadanie

**Kształt zasobu.** Procesor; opcjonalny redaktor-kandydat może korzystać z istniejącej dzierżawy procesora graficznego, ale nie ma do tego uprawnień

**Granica.** Gramatyka zamknięta jest wierna, ale może pozostać sztywna stylistycznie

**Główne narzędzia publiczne.**[spaCy](https://github.com/explosion/spaCy)

## Zarządzanie, weryfikacja i operacje

### Amf Ari


**Odpowiedzialność.** Uruchom przypięty klasyfikator relacji argument-relacja na dostarczonych parach propozycji i zwróć punktowane wsparcie, próby konfliktu, przeformułowania lub braku relacji. Nie tworzy propozycji, nie wnioskuje o motywach, nie certyfikuje własnych etykiet.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

**Główne narzędzia publiczne.**[OtwórzVINO](https://github.com/openvinotoolkit/openvino),[Model AMF ARI RoBERTa OpenVINO](https://huggingface.co/arg-tech/amf-ari-roberta-ov-int8)

### Indeksator czatu


**Odpowiedzialność.** Zapisuje rozmowy na dłużej, zamiast pozostawiać je w oknie czatu.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

### Indeksator plików


**Odpowiedzialność.** Odkryj kwalifikujące się pliki i prześlij ograniczone prace indeksacyjne zachowujące pochodzenie. Nie może traktować dat systemu plików, nazw plików ani wyodrębnionego tekstu jako wiarygodnego czasu utworzenia, tożsamości lub motywu.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

### Telemetria sprzętowa


**Odpowiedzialność.** Rejestruj ograniczoną historię stanu maszyny, aby można było porównać awarie z mocą, temperaturą, pamięcią i stanem akceleratora. W opisie publicznym pominięto częstotliwość próbkowania prywatnego i układ maszyny.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

**Główne narzędzia publiczne.**[psutil](https://github.com/giampaolo/psutil)

### Obraz


**Odpowiedzialność.** Twórz obrazy lokalnie, aby koncepcja wizualna nie musiała przekraczać zewnętrznych granic. Generowanie obrazu pozostaje oddzielone od organu dowodowego i pozwolenia na publikację.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

**Główne narzędzia publiczne.**[stable-diffusion.cpp](https://github.com/leejet/stable-diffusion.cpp),[Z-Image-Turbo](https://huggingface.co/Tongyi-MAI/Z-Image-Turbo),[Odniesienie do opakowania Z-Image-Turbo-Windows](https://github.com/airesearch-official/Z-Image-Turbo-Windows)

### Ollama


**Odpowiedzialność.** Ciężki umysł. Wolniejsze i większe, przeznaczone do pytań, które naprawdę wymagają więcej myślenia niż szybkości.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

**Główne narzędzia publiczne.**[Ollama](https://github.com/ollama/ollama),[Qwen3](https://github.com/QwenLM/Qwen3)

### Wstaw Ollamę


**Odpowiedzialność.** Umożliwia wyszukiwanie tekstów według znaczenia, a nie konkretnych słów.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

**Główne narzędzia publiczne.**[Ollama](https://github.com/ollama/ollama),[Tekst osadzania Nomic](https://huggingface.co/nomic-ai/nomic-embed-text-v1.5)

### Dzierżawa mocy


**Odpowiedzialność.** Pozwala maszynie spokojnie pracować na biegu jałowym i obudzić się z pełną mocą do prawdziwej pracy.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

### Zmiana tytułu rozmowy


**Odpowiedzialność.** Nadaje rozmowom nazwy, które coś znaczą, dzięki czemu można znaleźć listę, a nie ścianę pierwszych zdań.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

### Obserwator semantyczny


**Odpowiedzialność.** Sprawdza, czy odpowiedź jest poparta materiałem, z którego pochodzi.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

**Główne narzędzia publiczne.**[Transformatory](https://github.com/huggingface/transformers),[Miniczek](https://github.com/Liyan06/MiniCheck),[FaktCG](https://github.com/derenlei/FactCG)

### Analiza nachylenia


**Odpowiedzialność.** Prowadzi rejestr niepowodzeń każdego umysłu i tego, czy jest lepiej, czy gorzej.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

**Główne narzędzia publiczne.**[spaCy](https://github.com/explosion/spaCy),[BlingFire](https://github.com/microsoft/BlingFire),[NLTK](https://github.com/nltk/nltk)

### Przemawia


**Odpowiedzialność.** Zamienia mowę w tekst, więc mówienie jest sposobem na zapisywanie rzeczy.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

**Główne narzędzia publiczne.**[Przemawia](https://github.com/speaches-ai/speaches),[szybciej-szeptem](https://github.com/SYSTRAN/faster-whisper),[szybsza destylacja-szept-duży-v3](https://huggingface.co/Systran/faster-distil-whisper-large-v3)

### Służba zadaniowa


**Odpowiedzialność.** Czytaj autoryzowane zapisy zadań jako dowód planowanej pracy, bez przekształcania ich w przypomnienia, wywnioskowane motywy lub podstawową prawdę.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

### vLLM


**Odpowiedzialność.** Codzienny umysł. Szybki, zawsze załadowany, odpowiada prawie na wszystko.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

**Główne narzędzia publiczne.**[vLLM](https://github.com/vllm-project/vllm),[Qwen3](https://github.com/QwenLM/Qwen3)

### Trwałe prace sceniczne

ograniczone partie, punkty kontrolne, anulowanie, wznowienie i częściowa awaria

**Odpowiedzialność.** Uruchamiaj długie etapy artefaktów jako ograniczone zadania, które można wznawiać, z prawdziwymi stanami terminali, zamiast wiązać je z jednym żądaniem przeglądarki. Przykład: wznów po zweryfikowanym punkcie kontrolnym awansu, zamiast powtarzać kosztowne rozumowanie po przerwie.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

### Wykonanie + Menedżer manifestu

uruchamia przypisany adapter i rejestruje metodę fizyczną, punkt końcowy, wersję modelu, skróty, krawędzie wywołań, czas, ponowne próby i dyspozycję

**Odpowiedzialność.** Uruchom każdego przypisanego specjalistę i zapisz, co zostało fizycznie wykonane, wraz z danymi wejściowymi, tożsamością, czasem, ponownymi próbami i wynikiem. Przykład: pokaż, że przypięty klasyfikator AMF obsługiwał etap 2, zamiast ufać etykiecie manifestu, która jedynie twierdzi, że tak.

**Należy zachować.** input_hashes; tożsamość_adaptera; stan_awarii

**Kształt zasobu.** Koordynator CPU; deleguje pracę procesora graficznego wyłącznie za pośrednictwem zadeklarowanych właścicieli dzierżawy

**Granica.** wykonanie rekordów; nie może potwierdzić własnego sukcesu

### Arbitraż dotyczący dzierżawy GPU


**Odpowiedzialność.** Koordynuj przekazywanie porad pomiędzy obciążeniami akceleratora zarządzanymi przez platformę bez ujawniania tożsamości urządzenia fizycznego lub wywłaszczania prac już w trakcie wykonywania.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

### Koordynator Rezydencji Power

**Odpowiedzialność.** Utrzymuj jeden model stanu AKTYWNY, CIEPŁY, BEZCZYNNY i NIGDY w obrębie mechanizmów zasilania i rezydencji platformy rozproszonej.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

### Oczekiwana/obserwowana księga ładunku

łączy odpowiedzialność każdego koła zębatego z obserwowanymi polami, gotowością, pominięciami, wartością, kosztem, czasem, ponownymi próbami i żądaniem naprawy

**Odpowiedzialność.** Porównaj to, co każdy trybik miał wnieść, z tym, co faktycznie przekazał, łącznie z kosztami i brakującymi wkładami. Przykład: ujawnij, że analiza relacji trwała 40 sekund, ale nie dostarczyła edytorowi żadnej użytecznej krawędzi łączącej.

**Należy zachować.** handoff_identity; trawi; brakujące_pola; podstawa_kosztu

**Kształt zasobu.** Procesor; bliskie zeru w odniesieniu do rozumowania i weryfikacji

**Granica.** Czas sekcji przenośnej nie zastępuje czasu fizycznego etapu/modelu w manifeście wykonania

### Menedżer jakości świadomy produktu

sprawdza kompletność retoryczną, spójność rozumowania, czytelność, typografię, powielanie, uwagę, budżet, splot, niechlujność i wykonalność działań dla żądanego produktu

**Odpowiedzialność.** Oceń, czy ten konkretny produkt działa zgodnie z zadeklarowanym czytelnikiem i przeznaczeniem na różnych osiach jakości, a następnie określ odpowiedzialny etap naprawy. Przykład: podręcznik może nie zawierać wskazówek dotyczących odzyskiwania, nawet jeśli każde zdanie jest gramatyczne i oparte na podstawach.

**Należy zachować.** Individual_axis_results; odrzucony_kandydat_dowód

**Kształt zasobu.** Procesor plus ograniczony weryfikator/deslop HTTP; historycznie największy udział Etapu 8

**Granica.** Należy zmierzyć i wersjonować osie gatunkowe; jeden nieprzejrzysty wynik jakości jest zabroniony

### Menedżer paragonów i promocji

niezależnie przelicza niezmienniki i pozwala na promocję i zapis artefaktów atomowych tylko na podstawie potwierdzenia PASS

**Odpowiedzialność.** Niezależnie zweryfikuj pakiet i zapisz artefakt dopiero po przejściu każdego wymaganego niezmiennika. Przykład: odmów promocji, gdy moduł renderujący zgłosi sukces, ale jego odbiór nie może odtworzyć powiązania źródłowego.

**Należy zachować.** Failure_results; niewiadome; wydanie_tożsamości; granica_wycofywania

**Kształt zasobów.** Procesor i wejścia/wyjścia; bez procesora graficznego i leasingu

**Granica.** Autentyczność manifestu ostatecznie zależy od sprawdzonego niezmiennego powiązania wydania/konfiguracji

### Pochodzenie + kontrola strat

tożsamość źródła, stan epistemiczny, wnioskowanie, wynalazek i odrzucone gałęzie

**Odpowiedzialność.** Każde stwierdzenie powinno być powiązane z tym, kto lub co je dostarczyło, kiedy miało zastosowanie oraz czy zostało zaobserwowane, wywnioskowane, zastąpione, odrzucone czy nieznane. Przykład: zachowaj późniejszą reinterpretację bez nadpisywania wcześniejszego przekonania, które faktycznie kierowało działaniem.

**Należy zachować.** Dokładna tożsamość wykresu, pochodzenie pokrewieństwa i zadeklarowana granica komponentów.

**Kształt zasobów.** Wdrożenie na żywo rejestruje rzeczywiste wykorzystanie procesora, pamięci, pamięci masowej, akceleratora i dzierżawy; ten katalog publiczny nie ujawnia rozmieszczenia maszyn.

**Granica.** Może wykonywać tylko zadeklarowaną odpowiedzialność za wykresy i nie może naprawiać brakujących lub nieuzasadnionych dowodów wcześniejszych.

## Dodatkowe zadeklarowane komponenty

### Bezpieczna brama internetowa

Zapewnia uwierzytelniony zdalny dostęp od zatwierdzonych klientów bez bezpośredniego udostępniania usług platformy prywatnej w publicznym Internecie.

### Nadzorca Platformy

Uruchamia usługi w kolejności zależności, obserwuje ich kondycję i wykonuje ograniczone akcje ponownego uruchomienia. Jego awaria eliminuje skoordynowany nadzór bez ponownego definiowania stanu usług, które pozostają uruchomione.

## Granica kompletności

Katalog obejmuje aktywne komponenty logiczne na wykresie utrzymywanej architektury, a nie każdy pakiet przechodni instalowany przez każde środowisko wykonawcze. Przyszła wersja oprogramowania wymaga dokładnego zestawienia materiałów i pakietu licencji wygenerowanego na podstawie określonych dystrybuowanych bajtów.
