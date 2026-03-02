# Analiza zmian ludności największych polskich miast w latach 1500-2019 - Power BI

## Opis projektu
Głównym celem było określenie zmian ludności występujący w trzech największych obecnie polskich miastach: Krakowie, Wrocławiu i Warszawie w latach 1500-2019. Do tego celu użyto danych o ludności pobranych bezpośrednio z Wikipedii
a następnie wykonano na nich w Power Query operację ETL.
## Model Danych
Modelem jest jedna tabela **Dane** która jest połączonym zbiorem trzech tabel z informacjami o ludności dla każdego z miast.

## Raport
(https://github.com/MatemXVI/Analiza-zmian-ludno-ci-najwi-kszych-polskich-miast-w-latach-1500-2019/blob/main/miasta.pdf)

## Kluczowe wnioski 
* **Dominacja Warszawy przed rozbiorami:** Miasto Warszawa stale przewyższa nad liczbą ludności od 1780 roku, w 1624 jednokrotnie przewyższyła Kraków i Wrocław
* **Kraków w I RP czasami "uciekał" Warszawie:** Warszawa w okresie 1620-1770 ma okresy przewyższania Krakowa. Po raz pierwrszy stało się to w 1624 roku, a od 1770 stale góruje nad Krakowem. Jednak już w 1595 ludność Warszawy była bliska Krakowowi
* **Kraków nie tak wielki w I RP:**  W 1700 Ludność Wrocławia i Warszawy była czterokrotnie wyższa od ludności Krakowa.
* **Dominacja Wrocławia nad Krakowem**: W latach 1555-1945 Wrocław przewyższa swoją ludnością Kraków
* **Złoty wiek demografii:** W latach 1850-1939 w każdym z miast ludność wzrosła od 5.5 do ośmiokrotności. W okresie PRL był mniejszy, bo 2.5-3.75 krotny wzrost.
* **Utrzymywanie się ludności miast:** W latach 1990-2019 ludność się utrzymywała z niewielkim, kilkuprocentowym wzrostem. W Warszawie w latach 90. był niewielki spadek ludności
* **Drastyczny skutek wojny:** W latach 1939-1945 ludność Warszawy się zmniejszyła o 867 000 osób, czyli spadła o 67,26% względem stanu przedwojennego.
* **Utrzymywanie się stanu demograficznego w tak trudnych czasach:** W latach 1940-42 mimo działań wojennych i okresu okupacji niemieckiej, ludność Warszawy uległa niewielkiemu wzrostowi

## Wykorzystane funkcje DAX:

* Analiza dynamiki: Wykorzystanie funkcji CALCULATE do wyznaczania historycznych punktów kontrolnych (np. ludność Warszawy w 1939 r.).
* Storytelling: Stworzenie dynamicznych miar tekstowych, które dostosowują tytuły i opisy kart do wybranego miasta.
* Miary porównawcze: Obliczanie procentowych spadków i wzrostów (np. bilans strat wojennych)."

## Zawartość repozytorium
* `miasta.pbix` – pełny plik projektu Power BI.
* `miasta.pdf` – kompletny raport ze wszystkimi stronami analizy.
