> Polski: Wspomagane maszynowo tłumaczenie wiarygodnego źródła w języku angielskim. Mile widziane poprawki w języku ojczystym. [angielski](../../README.md) | [Wszystkie języki](../README.md)

# Jak system trzyma się razem

![Zachowana dokumentacja potwierdzająca wymiennych specjalistów i kontrolowaną płaszczyznę kontrolną](../../assets/core-architecture-layers.png)

## Podział obowiązków

Platforma wyodrębnia cztery koncerny, które współpracują nie stając się sobą:

1. **Konserwacja** zachowuje oryginalne dowody i zaobserwowane pochodzenie.
2. **Zrozumienie** dodaje wersjonowane obiekty semantyczne, relacje, stany czasowe,
  i wspierane interpretacje.
3. **Wyszukiwanie i interakcja** gromadzą dowody specyficzne dla żądania w przypadku pytań,
  eksploracja i rozmowa.
4. **Rekonstrukcja artefaktów** przekształca ograniczony świat dowodów w zadeklarowany
  produkt dla zadeklarowanego odbiorcy.

Instrukcje dotyczące produktu nie przedostają się do korpusu prawdy. Rozdział, publiczność, gatunek, posunięcie retoryczne lub budżet słów należą do jednego wycofania. Nie jest to wewnętrzna etykieta artefaktu źródłowego.

## Topologia warstwowa

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

## Przystąpienie nie udaje, że wie

Rekord przybycia może stwierdzać, że określone bajty dotarły do ​​systemu określonym kanałem. Nie decyduje po cichu, kto stworzył artefakt, kto się w nim pojawia, kiedy pojawił się jego temat, czy nazwa pliku jest dokładna, dlaczego ma to znaczenie i kto jest właścicielem jego zawartości. Są to odrębne obserwacje z odrębnymi dowodami i autorytetami.

Architektura odróżnia oryginalny artefakt od wywodzących się z niego przedstawień. Wyodrębniony tekst, opisy, elementy osadzone, klasyfikacje, podsumowania i relacje można odtworzyć lub zastąpić. Nie zastępują źródła.

## Ścieżki interaktywne i dokumentacyjne

Interaktywne odpowiadanie i generowanie artefaktów udostępniają dowody, pochodzenie, wpisane relacje, niepewność i mechanizmy walidacji. Różnią się one od tego samego przepływu pracy.

Interaktywna prośba może wymagać pełnej rozmowy, cyklu życia zadania, przejścia wąskiej relacji lub wyjaśnienia. Nie ma potrzeby konstruowania pojemnika na książki i globalnego zwijania drzewa historycznego.

Generowanie artefaktów wymaga zadeklarowanego produktu, odbiorcy, budżetu i planu obejmującego cały artefakt. Przed przycięciem musi zobaczyć odpowiednią tymczasową strukturę i uwzględnić to, co zostało pominięte.

## Dynamiczna architektura zamiast stałego łańcucha

Linia montażowa jest skompilowana dla produktu. Różne wyniki mogą wykorzystywać różnych specjalistów, inaczej porządkować tych samych specjalistów lub wymagać wielu wystąpień tej samej zdolności. Menedżer korzysta z umów dotyczących zdolności i wcześniejszych dowodów, a nie samych zakodowanych na stałe pseudonimów.

Uniwersalne niezmienniki pozostają stabilne w każdej linii: tożsamość źródła, własność, stan epistemiczny, niepewność, księgowanie strat, wpisane przekazania, obserwacja kosztów, niezależna weryfikacja i wycofywanie.

Zewnętrzny model ogólny może zajmować jedno stanowisko, jeśli jego zmierzony udział uzasadnia przekazanie. Otrzymuje tylko ładunek o zasięgu żądań wymagany przez tę stację, a nie utrzymywany korpus lub uprawnienia zakodowane przez szerszą płaszczyznę sterowania. Wymiana lub usunięcie tej stacji pozostawia nienaruszony trwały zapis i możliwość przyszłej rekonstrukcji. Ograniczona stacja może wnieść swój wkład bez otrzymywania ludzkiej wiedzy, którą scentralizowany system w przeciwnym razie spłaszczyłby do wartości instytucjonalnej.
