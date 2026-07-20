## [0.7.303] - 2026-07-20

- Skaner produktów: przebudowano modal, dodając duże zdjęcie po lewej oraz większe, czytelniejsze dane w jednej lub dwóch kolumnach po prawej.
- Skaner produktów: zmieniono etykietę opisu na „Opis produktu, do czego służy”.
- Skaner produktów: usunięto podkreślenie widoczne pod polem podczas szybkiej edycji wartości.

## [0.7.302] - 2026-07-20

- Usunięto dodatkowy dolny odstęp w alercie dostępnej aktualizacji, gdy pole komunikatu jest puste.

## [0.7.301] - 2026-07-20

- Wygasły dostęp do aktualizacji jest oznaczany czerwonym alertem.
- Pomarańczowy alert pojawia się na miesiąc przed końcem aktualizacji i przypomina o możliwości odnowienia dostępu.

## [0.7.300] - 2026-07-20

- Wyrównano kolejne wiersze tekstu w alercie licencyjnym do wspólnej lewej krawędzi obok ikony.

## [0.7.299] - 2026-07-20

- Uporządkowano odstępy w alercie o wygasłym dostępie do aktualizacji.

## [0.7.298] - 2026-07-20
- Aktualizacje: przy wygasłym dostępie moduł pokazuje numer dostępnej wersji, ale nie udostępnia przycisku instalacji.

## [0.7.297] - 2026-07-20
- Licencje: po wygaśnięciu dostępu do aktualizacji status zmienia kolor na żółty i wyjaśnia, że moduł pozostaje aktywny bezterminowo.
- Licencje: datę dostępu do aktualizacji skrócono do czytelnego formatu RRRR-MM-DD.

## [0.7.296] - 2026-07-20
- Aktualizacje i licencje: połączono moduł z API prestino.pl oraz spersonalizowanymi paczkami licencyjnymi.
- Ustawienia: dodano status pełnej licencji i alert dostępnej aktualizacji, usuwając stary przycisk, kanały i changelog z GitHuba.
- Produkty: dodano szybką edycję miejsca magazynowania dla produktów prostych i kombinacji.

## [0.7.295] - 2026-07-20
- Produkty: dodano opcjonalną kolumnę „Miejsce magazynowania” dla produktów prostych i kombinacji.

## [0.7.294] - 2026-07-12
- Aktualizacje: poprawiono kodowanie polskich znaków w changelogu wyświetlanym w panelu modułu.

## [0.7.293] - 2026-07-12
- Produkty: przeniesiono wybór trybu wyszukiwania do rozwijanego menu pod ikoną filtrów obok przycisku czyszczenia pola.

## [0.7.292] - 2026-07-10
- Produkty: poprawiono przełączniki aktywności, aby po zmianie statusu odświeżały listę i respektowały uprawnienia edycji w nowym widoku panelu.

## [0.7.287] - 2026-05-25
- Statystyki: wykres porownania rocznego pokazuje wartosc sprzedazy netto zamiast liczby sprzedanych sztuk.
- Statystyki: w tooltipie miniwykresu dziennego wiersz `Zamowienia` pokazuje sama liczbe bez powtorzonej etykiety.
- Statystyki: tooltip miniwykresu dziennego pokazuje wartosci netto, brutto, ilosc i liczbe zamowien w osobnych wierszach.
- Statystyki: miniwykresy dzienne w kafelkach miesiecznych maja dwa razy wyzszy obszar, dzieki czemu slupki sa czytelniejsze.

## [0.7.283] - 2026-05-23
- Aktualizacje: gdy zakres changeloga jest pusty, panel pokazuje pelny najnowszy wpis wersji zamiast komunikatu o braku wpisow.
- Aktualizacje: poprawiono kodowanie polskich znakow w changelogu i zawsze sprawdzany jest nowszy podpisany manifest przez GitHub API, aby ominac cache raw GitHuba.
- Moduł: podmieniono ikonę `logo.png` na nowszą wersję grafiki.
- Aktualizacje: release beta publikuje teraz kanoniczny changelog z repozytorium modulu, bez doklejania kolejnych blokow na koncu pliku buildow.
- Aktualizacje: rozdzielono sprawdzanie dostępności aktualizacji od pobierania changeloga, aby błąd changeloga nie blokował przycisku aktualizacji.
- Aktualizacje: utwardzono sprawdzanie nowych wersji, aby changelog i przypadkowy output PHP nie psuły odpowiedzi JSON oraz komunikatów w panelu.
- Moduł: dodano nową ikonę `logo.png` używaną w panelu modułów PrestaShop.
- Statystyki: w raporcie wybranych produktów dodano przełączanie kierunku sortowania `↓` / `↑` oraz poprawiono warstwę podglądu zdjęcia, aby nie był ucinany.
- Aktualizacje: poprawiono sygnatury nullable w updaterze i serwisie, aby ostrzeżenia `Deprecated` z nowszych wersji PHP nie psuły odpowiedzi JSON podczas sprawdzania aktualizacji.
- Statystyki: raport wybranych produktów ma ciaśniejsze kolumny, niższe wiersze oraz miniatury zgodne z zakładką `Produkty`, z pierwszym zdjęciem kombinacji.
- Statystyki: dopracowano raport wybranych produktów: wartości netto i brutto są w jednym wierszu, nazwy produktów nie są pogrubione, a stopka `Razem` nie pokazuje już pasków postępu.
- Produkty: poprawiono pozycję licznika wybranych produktów przy przycisku `Raport` i ukrywanie licznika, gdy nic nie jest wybrane.
- Statystyki: w raporcie wybranych produktów dodano poziome paski postępu pokazujące sprzedaną ilość względem najlepszej pozycji w danej kolumnie.
- Statystyki: raport wybranych produktów domyślnie sortuje po bieżącym miesiącu i pozwala przełączyć sortowanie kliknięciem nagłówków `Ostatnie 3 miesiące` oraz `Bieżący rok`.
- Ustawienia: pod przyciskiem aktualizacji dodano changelog obejmujący zakres od zainstalowanej wersji do wersji dostępnej.
- Statystyki: raport wybranych produktów pokazuje teraz jeden box z kolumnami dla produktu, bieżącego miesiąca, ostatnich 3 miesięcy i bieżącego roku.
- Statystyki: dodano raport sprzedaży wybranych produktów z miesięczną ilością oraz wartością netto i brutto.
- Produkty: dodano oznaczanie produktów do raportu sprzedaży i licznik wybranych pozycji w pasku narzędzi.

## [0.7.267] - 2026-05-20
- Addons: poprawiono zmienną listy ignorowanych produktów w kwerendzie magazynowej zgłoszoną przez validator.
- Addons: dopasowano kolejne sygnatury metod i formatowanie kontrolera wsparcia do standardów PrestaShop.

## [0.7.266] - 2026-05-20
- Addons: zmieniono autora i nagłówki licencyjne modułu na `Prestino`, pozostawiając dotychczasowe adresy GitHuba.
- Addons: poprawiono kolejne reguły standardów z raportu validatora PrestaShop.
- Techniczne: dopracowano spacing, inkrementacje i fallbacki klas Symfony/PrestaShop w kontrolerach.

## [0.7.265] - 2026-05-20
- Addons: usunięto nieużywany parametr z konstruktora updatera i zaktualizowano jego wywołania.
- Addons: uzupełniono brakujące metadane licencyjne w starym skrypcie upgrade.
- Addons: dopasowano formatowanie JS/PHP pod kolejne wskazania validatora PrestaShop.

## [0.7.264] - 2026-05-20
- Addons: wyczyszczono kolejne ostrzeżenia kompatybilności z raportu validatora PrestaShop.
- Addons: dodano nagłówki licencyjne i doc commenty do plików modułu oraz bibliotek JS.
- Addons: poprawiono fałszywy sygnał security w formatowaniu liczby w szablonie produktów.

## [0.7.263] - 2026-05-20
- Addons: dodano pliki `index.php` w katalogach modułu oraz rootowy `.htaccess` blokujący listowanie katalogów.
- Addons: poprawiono escaping zmiennych JavaScript w szablonach Smarty i przeniesiono HTML hooka nagłówka BO do szablonu Smarty.
- Addons: wyczyszczono proste ostrzeżenia kompatybilności zgłoszone przez validator, m.in. case klasy modułu, typ aktywności zakładek i zbędne fallbacki.

## [0.7.262] - 2026-05-20
- Addons: dostosowano kontrolery Symfony do walidatora PrestaShop 9 przez użycie `PrestaShopAdminController` i atrybutów `AdminSecurity`.
- Addons: usunięto bezpośrednie użycia `Context::getContext()` oraz jawne type-hinty `Context` z warstwy modułu.

## [0.7.261] - 2026-05-20
- Addons: usunięto nadmiarowy `config_pl.xml` z paczki modułu.
- Addons: dodano wymagany strażnik `_PS_VERSION_` do plików PHP zgłaszanych przez validator PrestaShop.

## [0.7.260] - 2026-05-20
- Techniczne: ustawiono nazwę modułu w konstruktorze jako wartość literalną, aby validator PrestaShop poprawnie rozpoznawał właściwość `$this->name`.

## [0.7.259] - 2026-05-20
- Maile: logo sklepu w wiadomości z dokumentami zamówienia jest osadzane w treści jako grafika, zamiast pojawiać się jako osobny załącznik.
- Zamówienia: powiększono miniatury produktów na liście zamówień do 20 px.

## [0.7.258] - 2026-05-20
- Zamówienia: dopasowano szerokość i rozmiar miniaturek produktów na liście, aby nie nachodziły na kolumnę daty.
- Zamówienia: miniatury produktów na liście pokazują większy podgląd po najechaniu lub fokusie.
- Zamówienia: odświeżono szablon maila z wysyłanymi dokumentami w stylu Modern i usunięto z bieżących tekstów odniesienia do księgowości.

## [0.7.257] - 2026-05-20
- Zamówienia: lista zamówień pokazuje kompaktowe miniatury produktów z każdego zamówienia, maksymalnie 10 obrazków z oznaczeniem `...` dla dłuższych list.

## [0.7.256] - 2026-05-19
- Zamówienia: menu wyboru języka PDF jest przyklejone do przycisku, ma jego szerokość i pokazuje flagi języków.

## [0.7.255] - 2026-05-19
- Zamówienia: dopasowano kolor i pozycję strzałki w przycisku rozwijanego menu `PDF`.

## [0.7.254] - 2026-05-19
- Zamówienia: wybór języka PDF działa jako rozwijane menu pod przyciskiem `PDF`, ze strzałką i opcjami `Polski` oraz `English`.
- Zamówienia: w PDF wycentrowano nagłówki kolumn `EAN`, ilości, ceny jednostkowej i wartości dla wszystkich języków.

## [0.7.253] - 2026-05-19
- Zamówienia: przy generowaniu PDF zamówienia można wybrać język dokumentu `PL` lub `EN`.
- Zamówienia: PDF w języku angielskim używa angielskich etykiet oraz angielskich nazw produktów i kombinacji, jeśli są dostępne w PrestaShop.

## [0.7.252] - 2026-05-19
- Zamówienia: miniatury produktów w modalu `Przyjęcie do magazynu` są dwa razy większe, aby łatwiej rozpoznawać pozycje przed potwierdzeniem.

## [0.7.251] - 2026-05-19
- Mobile: dopracowano pasek zakładek na telefonie — zakładki są równej szerokości, mają stałą wysokość i pokazują same ikony.

## [0.7.250] - 2026-05-19
- Mobile: poprawiono ukrywanie nazw zakładek także w wariancie layoutu, w którym pasek nie jest bezpośrednim dzieckiem nagłówka strony.

## [0.7.249] - 2026-05-19
- Mobile: poprawiono modal skanowania aparatem — zmniejszono wysokość, usunięto kod kreskowy z widoku i dopracowano przewijanie.
- Mobile: zakładki modułu przełączają się na tryb ikon, aby mieściły się poziomo na telefonie.

## [0.7.248] - 2026-05-19
- Produkty: dodano skanowanie kodów kreskowych aparatem telefonu z użyciem tylnej kamery.
- Produkty: wynik skanowania aparatem trafia do istniejącego pola wyszukiwania i uruchamia tę samą logikę co skaner USB.
- Produkty: poprawiono responsywność pola wyszukiwania oraz przycisków akcji na telefonie.
- Zamówienia: nagłówek kolumny w modalu przyjęcia zmieniono na `Zmiana stanu magazynowego`.

## [0.7.247] - 2026-05-19
- Techniczne: podbito wersję modułu po zmianach w zamówieniach, aby aktualizator PrestaShop widział nową betę.

## [0.7.246] - 2026-05-19
- Zamówienia: dodano akcję `Przyjmij do magazynu`, która dodaje produkty z zamówienia do stanów magazynowych PrestaShop.
- Zamówienia: dodano modal potwierdzenia przyjęcia z listą produktów, miniaturami, aktualnym stanem, dodawaną ilością i stanem po zmianie.
- Zamówienia: po przyjęciu produktów zamówienie jest oznaczane jako dodane do magazynu i pokazuje zielony przycisk `Dodano do magazynu`.

## [0.7.245] - 2026-05-16
- Statystyki: małe wykresy miesięczne nadal obrazują wartość sprzedaży, ale używają czytelniejszej skali wizualnej dla niskich słupków.

## [0.7.244] - 2026-05-15
- Statystyki: małe wykresy miesięczne skalują słupki po sprzedanych sztukach, dzięki czemu są wyraźniejsze.

## [0.7.243] - 2026-05-15
- Statystyki: ranking produktów w miesięcznych kafelkach pomija produkty ukryte w ustawieniach modułu.
- Statystyki: liczby porządkowe w rankingu produktów mają regularną grubość tekstu.

## [0.7.242] - 2026-05-15
- Statystyki: wyśrodkowano numerację rankingu produktów i ustawiono regularną grubość nazw produktów.

## [0.7.241] - 2026-05-15
- Statystyki: tooltip dziennego wykresu w kafelku miesięcznym pokazuje dzień tygodnia obok daty.
- Statystyki: miesięczne kafelki mają rozwijany ranking najlepiej sprzedanych produktów z miniaturami i doładowaniem kolejnych pozycji.

## [0.7.240] - 2026-05-14
- Statystyki: tooltipy sprzedaży pokazują teraz osobno sprzedane sztuki i liczbę zamówień.

## [0.7.239] - 2026-05-10
- Statystyki: tooltip dziennego wykresu w kafelku miesięcznym aktywuje się po kolumnie dnia, dzięki czemu łatwiej trafić w niskie słupki.

## [0.7.238] - 2026-05-10
- Statystyki: obniżono tooltip dziennego wykresu o wysokość dziubka, aby siedział bliżej słupka.

## [0.7.237] - 2026-05-10
- Statystyki: obniżono zewnętrzny tooltip dziennego wykresu tak, aby był bliżej aktywnego słupka.

## [0.7.236] - 2026-05-10
- Statystyki: dzienne wykresy w kafelkach miesięcznych używają zewnętrznego HTML tooltipa, aby dymek był pozycjonowany niezależnie od ograniczeń canvasa Chart.js.

## [0.7.235] - 2026-05-10
- Statystyki: pozycja tooltipa dziennego wykresu uwzględnia także wysokość dziubka nad aktywnym słupkiem.

## [0.7.234] - 2026-05-10
- Statystyki: tooltip dziennego wykresu w kafelku miesięcznym jest podnoszony nad słupkiem o wysokość aktywnego słupka.

## [0.7.233] - 2026-05-10
- Statystyki: górne krawędzie miesięcznych kafelków mają ciemniejsze szarości dopasowane do tła kafelków.

## [0.7.232] - 2026-05-10
- Statystyki: tooltip dziennego wykresu w kafelku miesięcznym jest odsuwany nad górę aktywnego słupka.

## [0.7.231] - 2026-05-10
- Statystyki: tooltip dziennego wykresu w kafelku miesięcznym jest pozycjonowany centralnie nad aktywnym słupkiem.

## [0.7.230] - 2026-05-10
- Statystyki: słupki dziennych wykresów w kafelkach miesięcznych używają zieleni zgodnej z etykietą roku 2026.

## [0.7.229] - 2026-05-10
- Statystyki: tooltipy dziennych wykresów słupkowych w kafelkach miesięcznych pokazują się nad słupkiem z dziubkiem skierowanym w dół.

## [0.7.228] - 2026-05-10
- Statystyki: dodano dzienne wykresy słupkowe sprzedaży w trzech kafelkach miesięcznych.

## [0.7.227] - 2026-05-10
- Etykiety produktów: przebudowano układ PDF od nowa na przepływ z marginesem strony 5 mm.

## [0.7.226] - 2026-05-09
- Etykiety produktów: poprawiono realne wyśrodkowanie zawartości PDF i jawne pozycjonowanie kodu EAN13.

## [0.7.225] - 2026-05-08
- Etykiety produktów: dodano spójniejsze marginesy i wyrównanie zdjęcia, tekstu oraz kodu kreskowego.

## [0.7.224] - 2026-05-08
- Etykiety produktów: poprawiono centrowanie kodu kreskowego EAN13 na dole PDF.

## [0.7.223] - 2026-05-08
- Etykiety produktów: PDF jest wymuszany do jednej strony, kod EAN13 jest przypięty i wyśrodkowany na dole, a zdjęcie nie ma ramki ani zaokrągleń.

## [0.7.222] - 2026-05-08
- Produkty: zamieniono ikony akcji `Historia ceny` i `Wykres sprzedaży`.
- Produkty: wykres `Historia ceny` jest teraz wykresem słupkowym.
- Etykiety produktów: dopasowano układ kodu kreskowego, aby nie przechodził na kolejną stronę.

## [0.7.192] - 2026-04-16
- Produkty: wyszukiwanie skanerem po EAN/UPC produktu z kombinacjami nie zwraca już błędu SQL i nie pokazuje debugowych danych zapytania w modalu.

## [0.7.191] - 2026-04-16
- Produkty: ręczne pole EAN w dymku aktywnego skanera ma białe tło i wygląd zwykłego pola tekstowego.

## [0.7.190] - 2026-04-16
- Produkty: pole ręcznego wpisywania EAN w dymku aktywnego skanera jest ukryte pod ikoną i pokazuje się jako proste pole bez etykiety oraz dodatkowej obramówki.

## [0.7.189] - 2026-04-15
- Produkty: bezpośrednie wejście w legacy link zakładki przekierowuje teraz na kanoniczny kontroler, dzięki czemu panel inicjalizuje się poprawnie już przy pierwszym otwarciu.

## [0.7.188] - 2026-04-14
- Dokumentacja: dodano README modułu z opisem funkcji, instalacji, aktualizacji, kopii zapasowych i struktury technicznej.

## [0.7.187] - 2026-04-14
- Rentowność: uproszczono CSS plakietek `Zysk (netto)`, aby style widoku produktów ładowały się stabilnie.

## [0.7.186] - 2026-04-14
- Rentowność: zielone plakietki `Zysk (netto)` używają jaśniejszego odcienia zgodnego ze switchami.

## [0.7.185] - 2026-04-14
- Rentowność: wartości `Zysk (netto)` są prezentowane jako zielone plakietki.

## [0.7.184] - 2026-04-14
- Kopie zapasowe: przycisk `Przywróć` ma pełne niebieskie tło zamiast szarego obrysu.

## [0.7.183] - 2026-04-14
- Kopie zapasowe: przycisk `Usuń` ma pełne czerwone tło zamiast samego obrysu.

## [0.7.182] - 2026-04-14
- Ustawienia: ikony w przyciskach `Dodaj przewoźnika`, `Dodaj rodzaj` i `Dodaj status` mają biały kolor.

## [0.7.181] - 2026-04-14
- Ustawienia: ikona w przycisku `Utwórz kopię` ma biały kolor.

## [0.7.180] - 2026-04-14
- Produkty > Historia ceny: wykres historii cen zakupu zaczyna oś Y od zera.

## [0.7.179] - 2026-04-14
- Menu Back Office: plakietki przy `Zamówienia` są dodawane bezpośrednio do linku menu analogicznie do licznika `Logi` w Allegro.

## [0.7.178] - 2026-04-14
- Menu Back Office: pozycja `Zamówienia` zachowuje stałe wyrównanie także przy widocznych plakietkach liczników.

## [0.7.177] - 2026-04-14
- Menu Back Office: usunięto wpływ plakietek liczników na wcięcie pozycji `Zamówienia`.

## [0.7.176] - 2026-04-14
- Menu Back Office: licznik przy `Zamówienia` obsługuje wiele statusów włączanych przełącznikiem w tabeli `Statusy zamówień`, a kolor każdej plakietki wynika z koloru statusu.

## [0.7.175] - 2026-04-14
- Menu Back Office: ukryto plakietkę przy `Zamówienia`, gdy licznik wynosi `0`.

## [0.7.174] - 2026-04-14
- Menu Back Office: usunięto dodatkowe wcięcie pozycji `Zamówienia` z plakietką licznika.

## [0.7.173] - 2026-04-14
- Menu Back Office: dopasowano styl licznika przy `Zamówienia` do małej plakietki używanej w menu Allegro.

## [0.7.172] - 2026-04-14
- Menu i zakładki: skrócono etykietę `Zamówienia towaru` do `Zamówienia`.

## [0.7.171] - 2026-04-14
- Menu Back Office: poprawiono pozycjonowanie plakietki przy `Zamówienia towaru`, aby licznik był tuż przy tekście i nie zawijał etykiety.

## [0.7.170] - 2026-04-14
- Menu Back Office: przeniesiono licznik zamówień z głównej pozycji `CargoStock Manager` na podmenu `Zamówienia towaru` i dopasowano styl plakietki do menu Allegro.

## [0.7.169] - 2026-04-14
- Menu Back Office: przywrócono pełną nazwę głównej pozycji menu `CargoStock Manager`.

## [0.7.168] - 2026-04-14
- Menu Back Office: dodano licznik zamówień zakupowych przy pozycji CargoStock oraz ustawienie statusu zamówień liczonych w tej etykiecie.

## [0.7.167] - 2026-04-12
- Backupy: po przejęciu uploadu importu kontroler czyści wpis z $_FILES, żeby generowanie linków PrestaShop nie odtwarzało błędnego FileBag.

## [0.7.166] - 2026-04-12
- Backupy: import paczki ZIP nie odczytuje już pliku przez Symfony FileBag, żeby uniknąć błędu FileNotFoundException dla ścieżki tymczasowej uploadu.

## [0.7.165] - 2026-04-12
- Backupy: poprawiono import paczki ZIP na czystej instalacji PrestaShop 8, gdy Symfony zgłasza brak tymczasowego pliku uploadu.

## [0.7.164] - 2026-04-12
- Ustawienia modułu: dodano usuwanie kopii zapasowych z potwierdzeniem.
- Modal sprzedaży: linie separatorów w rocznych panelach 2024, 2025 i 2026 mają kolor panelu.

## [0.7.163] - 2026-04-12
- Ustawienia modułu: dodano tworzenie, listę, pobieranie, przywracanie oraz wgrywanie kopii zapasowych danych modułu.

## [0.7.162] - 2026-04-11
- Modal „Rentowność": przywrócono separator pod pierwszym wierszem w obu panelach.

## [0.7.161] - 2026-04-11
- Modal „Rentowność": naprawiono kolory separatorów wierszy — usunięto szare linie nadpisujące kolorowe.

## [0.7.160] - 2026-04-11
- Modal „Rentowność": wymuszono kolorowe separatory w panelach, żeby nie przebijały szare linie z ogólnych styli.

## [0.7.159] - 2026-04-11
- Dostawcy: formularz dodawania i edycji dostawcy otwiera się w oknie modalnym z blurrem tła.

## [0.7.158] - 2026-04-11
- Modal „Rentowność": panel „Cena w sklepie" ma pomarańczowe separatory i bez linii pod pierwszym wierszem.

## [0.7.157] - 2026-04-11
- Modal „Rentowność": linie separatorów w panelach mają niebieski odcień zgodny z obramowaniem.

## [0.7.156] - 2026-04-11
- Modal „Rentowność": usunięto górną linię oddzielającą pierwszy wiersz w panelach.

## [0.7.155] - 2026-04-11
- Modal „Rentowność": poprawiono czytelność etykiet cenowych paneli, z małymi etykietami „netto" i „brutto".

## [0.7.154] - 2026-04-11
- Modal „Rentowność": etykieta panelu Marketplace pokazuje cenę marketplace netto i brutto.

## [0.7.153] - 2026-04-11
- Modal „Rentowność": etykieta panelu sklepu pokazuje cenę w sklepie netto i brutto.

## [0.7.152] - 2026-04-11
- Modal „Rentowność": usunięto nagłówek „Ustawienia marketplace" z panelu Marketplace.

## [0.7.151] - 2026-04-11
- Modal „Rentowność": ceny i wartości pieniężne są pokazywane z groszami.

## [0.7.150] - 2026-04-11
- Modal „Rentowność": panele „Sklep" i „Marketplace" ostylowane jak karty roczne z wykresu sprzedaży: pastelowe tło, kolorowy górny pasek, plakietka i wiersze w jednej kolumnie.

## [0.7.149] - 2026-04-11
- Modal „Rentowność": sekcje „Sklep" i „Marketplace" pokazują się w dwóch panelach obok siebie, każda w jednej kolumnie.
- Modal „Rentowność": ustawienia marketplace przeniesione wyżej do panelu „Marketplace" bez dodatkowego pudełka.

## [0.7.148] - 2026-04-11
- Zakładka „Produkty": modal „Historia ceny" ma teraz taką samą szerokość jak „Edytuj dane modułowe".

## [0.7.147] - 2026-04-11
- Zakładka „Produkty": modal „Rentowność" ma teraz taką samą szerokość jak „Edytuj dane modułowe".

## [0.7.146] - 2026-04-11
- Zakładka „Produkty": nagłówki modalów „Edytuj dane modułowe", „Wykres sprzedaży", „Historia ceny" i „Rentowność" ujednolicone 1:1 ze stylem modala „Kalkulacja kosztu" z zamówień.

## [0.7.145] - 2026-04-11
- „Produkty w zamówieniu > Edytuj dane produktu": usunięto dodatkową warstwę `modal-content`, żeby modal używał tej samej struktury karty i nagłówka co „Kalkulacja kosztu".

## [0.7.144] - 2026-04-11
- Poprawka: modal „Produkty > edytuj dane modułowe" nie otwierał się przez błąd formatowania waluty w JS.
- „Produkty w zamówieniu > Edytuj dane produktu": nagłówek modala ujednolicony 1:1 ze stylem „Kalkulacja kosztu".

## [0.7.143] - 2026-04-11
- Popup „Wykres sprzedaży": „Mies. MIN x MAX x ŚR. x" w jednym wierszu.

## [0.7.142] - 2026-04-11
- Popup „Wykres sprzedaży": wykres w boxie z zaokrąglonymi rogami; „PORÓWNANIE ROCZNE" i plakietki lat wewnątrz boxa; strzałki nawigacji wewnątrz boxa; legenda Chart.js zastąpiona kolorowymi plakietkami.

## [0.7.141] - 2026-04-11
- Popup „Wykres sprzedaży": „Szacowany zysk" rozbity na dwa spójne wiersze: „Zysk sklep" i „Zysk marketplace".

## [0.7.140] - 2026-04-11
- Popup „Wykres sprzedaży": tooltip wykresu w formacie „Maj 2025: 19 szt. / 1 000 zł netto / 1 230 zł brutto" — jedna linia na rok.

## [0.7.139] - 2026-04-11
- Popup „Wykres sprzedaży": etykieta „Miesięcznie" przed wierszami MIN/MAX/ŚRED. i Wartość / mies.

## [0.7.138] - 2026-04-11
- Poprawka: plakietki lat w nagłówku wykresu były niewidoczne (brak tła poza kontekstem panelu).

## [0.7.137] - 2026-04-11
- Popup „Wykres sprzedaży": tła paneli rocznych jako gradient z góry (kolor linii) do dołu (biały), analogicznie jak wypełnienia na wykresie.

## [0.7.136] - 2026-04-11
- Popup „Wykres sprzedaży": jaśniejsze złote tło panelu najstarszego roku.

## [0.7.135] - 2026-04-11
- Popup „Wykres sprzedaży": panele 3 lat w pastelowych tłach zgodnych z kolorami linii wykresu (złoty / błękitny / zielony).

## [0.7.134] - 2026-04-11
- Popup „Wykres sprzedaży": etykiety „Sklep:" i „Marketplace:" w szacowanym zysku wyszarzone jak „netto" i „brutto".

## [0.7.133] - 2026-04-11
- Popup „Wykres sprzedaży": lata w nagłówku wykresu jako kolorowe plakietki zgodne z kolorami linii.

## [0.7.132] - 2026-04-11
- Popup „Wykres sprzedaży": wartości w kolumnach rocznych pogrubione.

## [0.7.131] - 2026-04-11
- Popup „Wykres sprzedaży": wiersz MIN/MAX/ŚRED. pokazuje trzy wartości inline z etykietami zamiast w formacie x / y / z.

## [0.7.130] - 2026-04-11
- Popup „Wykres sprzedaży": szacowany zysk pokazuje Sklep i Marketplace osobno, każde z wartością netto i brutto w jednym wierszu.

## [0.7.129] - 2026-04-11
- Popup „Wykres sprzedaży": wartość sprzedaży netto/brutto, szacowany zysk netto/brutto oraz wartość miesięczna netto/brutto — każda para w jednym wierszu.

## [0.7.128] - 2026-04-11
- Popup „Wykres sprzedaży": każdy rok w osobnym panelu z zaokrąglonymi narożnikami i kolorowym paskiem u góry; szerokość okna powiększona do 1520 px (jak „Kalkulacja kosztu" w zamówieniach).

## [0.7.127] - 2026-04-11
- Popup „Wykres sprzedaży": statystyki 3 lat pokazane w 3 kolumnach obok siebie; rok jako plakietka w kolorze linii na wykresie (złoty / błękitny / zielony).

## [0.7.126] - 2026-04-10
- Zawartość popupów „Wykres sprzedaży", „Historia ceny" i „Rentowność" przepisana na układ i style `csmgr-cost-*` zgodne z „Kalkulacja kosztu" z zamówień: sekcje z tytułami, grid wierszy etykieta/wartość, stany kolorystyczne dla wartości dodatnich/ujemnych.

## [0.7.125] - 2026-04-11
- Zakładka Produkty, Akcje: popup „Wykres sprzedaży".
- Poprawka: modal „Edytuj dane modułowe" nie otwierał się po kliknięciu (błąd zakresu funkcji formatowania waluty między blokami IIFE).

## [0.7.124] - 2026-04-10
- Zawartość popupa `Produkty > Edytuj dane modułowe` przebudowano na układ i style z modala `Kalkulacja kosztu`: sekcje, grid danych produktu, wiersze etykieta/wartość i uporządkowany opis.

## [0.7.123] - 2026-04-10
- Nagłówki modalów produktowych `Edytuj dane modułowe`, `Wykres sprzedaży`, `Historia ceny` i `Rentowność` dopasowano do stylu modala `Kalkulacja kosztu` z zamówień: mniejsza miniatura, prosty border, tytuł i kombinacja w tym samym układzie.

## [0.7.122] - 2026-04-10
- Po instalacji aktualizacji moduł czyści cache Smarty, XML, Media i wewnętrzny cache PrestaShop, żeby zmiany w szablonach `.tpl` były widoczne od razu po aktualizacji.

## [0.7.121] - 2026-04-10
- Ujednolicono nagłówek modala `Produkty > Edytuj dane modułowe` ze stylem modalów `Wykres sprzedaży`, `Historia ceny` i `Rentowność`: miniatura, nazwa produktu i kombinacja mają ten sam układ.
- W modalu edycji danych modułowych ukryto EAN w nagłówku otwieranym z przycisku edycji produktu.

## [0.7.120] - 2026-04-10
- W `Ustawienia > Lista ukrytych produktów` usunięto kolumnę `Wyświetlany`.
- Pod nazwą produktu na liście ukrytych produktów dodano nazwę kombinacji, np. `Zapach: lawendowy`.

## [0.7.119] - 2026-04-10
- W modalu `Dane modułowe produktu` nagłówek pokazuje nazwę produktu, a pod spodem pełną nazwę kombinacji.
- W modalu `Kalkulacja kosztu` kombinacja produktu korzysta z pełnej etykiety wariantu, np. `Zapach: lawendowy`.

## [0.7.118] - 2026-04-10
- Do modala `Dane modułowe produktu` dodano miniaturkę produktu w nagłówku z fallbackiem dla produktów bez zdjęcia.
- W tym samym modalu `HS Code` został dopasowany do drugiego wiersza obok `Stawka celna`.

## [0.7.117] - 2026-04-10
- W modalu `Dane modułowe produktu` pola nad opisem zostały przełożone do dwóch rzędów na desktopie: pierwszy rząd zawiera model, wagę i ilość w kartonie, a drugi objętość, materiał, stawkę celną i HS Code.

## [0.7.116] - 2026-04-10
- Modal `Produkty > Edytuj dane modułowe` dostał spójny styl z pozostałymi modalami modułu: biały dialog, wspólny cień, pasek górny, przycisk zamknięcia i header.
- Zachowano osobny pełnoekranowy wygląd trybu baterii skanera.

## [0.7.115] - 2026-04-10
- W `Produkty > Historia ceny` ceny zakupu są teraz wyświetlane z groszami w statystykach, liście zakupów, tooltipach i osi wykresu.

## [0.7.114] - 2026-04-10
- Poprawiono zamykanie modala `Połącz z produktem` dla niepowiązanych pozycji w zamówieniu: po udanym relinku stan requestu jest zapamiętywany lokalnie, a modal dostaje pewny reset i zamknięcie bez losowego „przywieszania”.

## [0.7.113] - 2026-04-10
- W modalu `Wyślij do księgowania` checkboxy wróciły do natywnego renderowania przeglądarki z `form-check-input`, a kolor zaznaczenia opiera się o zmienne Back Office (`--bs-primary` / `--primary`), co poprawia zgodność z motywami PrestaShop 8 i 9.

## [0.7.112] - 2026-04-10
- Checkboxy w modalu `Wyślij do księgowania` dostały lokalny styl wizualnie zgodny z turkusowymi checkboxami Back Office, niezależny od globalnych styli formularzy.

## [0.7.111] - 2026-04-10
- Checkboxy w pierwszej kolumnie tabeli modala `Wyślij do księgowania` korzystają teraz z klas `form-check` i `form-check-input`, aby łapały standardowy wygląd Back Office.

## [0.7.110] - 2026-04-10
- W modalu `Wyślij do księgowania` lista plików została przebudowana do układu tabeli spójnego z sekcją `Dokumenty` na widoku zamówienia.
- Pierwsza kolumna używa zwykłych checkboxów w domyślnym stylu Back Office zamiast własnego układu listy.

## [0.7.109] - 2026-04-10
- Formularzowe modale w zamówieniach towaru (`Dodaj produkt`, `Edytuj dane produktu`, `Dodaj notatkę`, `Wyślij do księgowania`) korzystają teraz z tego samego customowego mechanizmu co `Kalkulacja kosztu`.
- Ujednolicono blur, animację, obsługę klawisza `ESC`, kliknięcia w tło i zamykania przez `X` we wszystkich tych modalach.
- Usunięto bootstrapowe sterowanie pozycją formularzowych modalów, co naprawia zbyt niskie położenie okna `Edytuj dane produktu`.

## [0.7.108] - 2026-04-10
- Doprecyzowano centrowanie modalów formularzy po migracji animacji: dialogi korzystają z `modal-dialog-centered` i nie osiadają zbyt nisko.

## [0.7.107] - 2026-04-10
- Poprawiono pozycjonowanie modali formularzy po ujednoliceniu animacji: okna są znów centrowane pionowo i nie zjeżdżają w dół.

## [0.7.106] - 2026-04-09
- Ujednolicono animacje i tło modalów w module do stylu `Kalkulacja kosztu`: wspólny blur, górny pasek i wejście `fade + translateY`.

## [0.7.105] - 2026-04-09
- Wzmocniono blur tła w bootstrapowym modalu `Edytuj dane produktu`, aby wyglądał tak samo jak w modalu `Kalkulacja kosztu`.

## [0.7.104] - 2026-04-09
- Na przycisku aktualizacji dodano oznaczenie `Beta` przy wersji, gdy dostępna aktualizacja pochodzi z kanału beta.

## [0.7.103] - 2026-04-09
- Poprawiono blur backdropu w bootstrapowym modalu `Edytuj dane produktu`, także dla wariantu klas `.modal-backdrop.in`.

## [0.7.102] - 2026-04-09
- Dodano wybór kanału aktualizacji `Public` / `Beta` w ustawieniach modułu oraz obsługę osobnych manifestów release.
- Ujednolicono modale w zamówieniach: blur tła, zamykanie przez `X`, `ESC` i klik w tło oraz kolorowy pasek na górnej krawędzi.

## [0.7.101] - 2026-04-08
- W sekcji `Dokumenty` na widoku zamówienia dodano przycisk `Wyślij do księgowania` z popupem wyboru plików i adresem e-mail do księgowania konfigurowanym w ustawieniach modułu.

## [0.7.100] - 2026-04-07
- Naprawiono układ sekcji notatek w zamówieniach towaru po wdrożeniu multiuploadu plików: przycisk `Dodaj notatkę` i kafelki notatek wracają do właściwego miejsca pod sekcją dokumentów.

## [0.7.99] - 2026-04-07
- W zamówieniach towaru upload plików obsługuje teraz multiupload: można przeciągnąć lub wybrać kilka plików naraz, a formularz pokazuje osobne pola opisu i rodzaju dokumentu dla każdego pliku.

## [0.7.79] - 2026-04-02
- W PDF `Tłumaczenie Faktury` naprawiono renderowanie plakietek `EN` / `PL`: styl tła i paddingu przeniesiony na `<td>` zamiast `<span display:inline-block>`, co jest wymagane przez mPDF.

## [0.7.78] - 2026-04-02
- W PDF `Tłumaczenie Faktury` dopracowano wygląd plakietek `EN` / `PL`: większy padding wewnętrzny, mniejsze odstępy wokół i delikatne zaokrąglenie.

## [0.7.77] - 2026-04-02
- W PDF `Tłumaczenie Faktury` poprawiono render plakietek `EN` / `PL`, aby tło i padding dotyczyły tylko samej plakietki, bez rozciągania na całą komórkę.

## [0.7.76] - 2026-04-02
- W PDF `Tłumaczenie Faktury` plakietki `EN` i `PL` są teraz renderowane jako komórki tabeli z twardym stylem inline, co stabilizuje padding i eliminuje pustą przestrzeń obok.

## [0.7.75] - 2026-04-02
- W PDF `Tłumaczenie Faktury` przebudowano układ linii `EN` / `PL`, żeby plakietki miały własny, bardziej przewidywalny render bez sztucznej pustej przestrzeni obok.

## [0.7.74] - 2026-04-02
- W widoku zamówienia sekcję `Adres dostawy` zmieniono na `Nabywca` i pokazuje ona teraz dokładnie bieżący tekst zapisany w ustawieniach modułu.
- W ustawieniach zamówień etykietę, placeholder i przycisk zmieniono z `Adres dostawy` na `Nabywca`.

## [0.7.73] - 2026-04-02
- W PDF `Tłumaczenie Faktury` dopracowano padding i odstępy plakietek `EN` / `PL` oraz dodano `Warunki dostawy` do sekcji `Szczegóły`.

## [0.7.72] - 2026-04-02
- PDF-y zamówienia i `Tłumaczenie Faktury` używają teraz pełniejszego adresu dostawy z ustawień modułu, jeśli w zamówieniu była zapisana krótsza wersja bez EORI.

## [0.7.71] - 2026-04-02
- Poprawiono render plakietek `EN` i `PL` w PDF `Tłumaczenie Faktury`, tak aby były wyraźnie oddzielone od nazwy produktu.

## [0.7.70] - 2026-04-02
- Dokument `Tłumaczenie Faktury` ma teraz czytelniejsze plakietki `EN` i `PL`, a `Materiał` został wydzielony do osobnej kolumny.

## [0.7.69] - 2026-04-02
- Dokumenty PDF zamówienia i `Tłumaczenie Faktury` pokazują teraz cały adres dostawy z ustawień modułu, bez ucinania dłuższych wpisów.
- W `Tłumaczeniu Faktury` połączono nazwę produktu EN i PL w jedną komórkę z plakietkami językowymi.

## [0.7.68] - 2026-04-02
- Narzut w modalu `Kalkulacja kosztu` zapisuje się teraz osobno dla każdej kombinacji produktu.
- W panelu produktów zamówienia dodano dokument `Tłumaczenie Faktury` z nazwą produktu PL/EN, HS Code i opisem produktu z danych modułu.

## [0.7.67] - 2026-04-02
- Modal `Historia ceny` w zakładce Produkty ma teraz niższy wykres, bardziej kompaktowe kafelki statystyk, listowy układ zamówień i przewijanie zawartości przy dłuższym widoku.

## [0.7.66] - 2026-04-02
- Modal `Historia ceny` w zakładce Produkty korzysta teraz z tego samego stylu obramowania co pozostałe okna modalne, pokazuje wyłącznie cenę zakupu netto w PLN i ma polskie tłumaczenia.

## [0.7.65] - 2026-04-02
- W zakładce Produkty dodano nową akcję `Historia ceny` z osobnym oknem modalnym i wykresem historii cen zakupu na podstawie pozycji z zamówień towaru.

## [0.7.64] - 2026-04-02
- Modale `Wykres sprzedaży` i `Rentowność` w zakładce Produkty korzystają teraz z tego samego stylu obramowania co popup `Kalkulacja kosztu`: ten sam promień narożników, kolorowy pasek u góry i przycisk `X`.

## [0.7.63] - 2026-04-02
- Dalsze dopracowanie popupu kalkulacji kosztu: jaśniejszy zapis `Zysk netto`, bardziej elastyczne pole wyniku kosztu całkowitego, węższe pole edycji `Narzut`, fallback nazwy kombinacji w nagłówku oraz kolorowy pasek na górnej krawędzi modala.
- Skrypt release zapisuje teraz także lokalną kopię builda i manifestu do katalogu `builds-local/`, co ułatwia ręczną instalację aktualizacji.

## [0.7.62] - 2026-04-01
- Nagłówek popupu kalkulacji kosztu pokazuje teraz nazwę kombinacji w osobnym wierszu pod nazwą produktu.

## [0.7.61] - 2026-04-01
- Dalsze dopracowanie popupu kalkulacji kosztu: pogrubienie etykiet w danych produktu, przeniesienie `Marży` i `Zysku` do wiersza wyniku ceny detalicznej oraz korekta odstępów między nagłówkami, wartościami i separatorem.

## [0.7.60] - 2026-04-01
- Dalsze dopracowanie popupu kalkulacji kosztu: przeniesienie `Marży` i `Zysku` bliżej wyniku ceny detalicznej oraz lekkie pogrubienie strzałki `→`.

## [0.7.59] - 2026-04-01
- Pierwszy wiersz kalkulacji kosztu został uproszczony do opisowych nagłówków pól bez widocznych plakietek i operatorów, przy zachowaniu wyrównania względem rzędu z wartościami.

## [0.7.58] - 2026-04-01
- Popup i lista pozycji zamówienia korzystają teraz z aktualnego tytułu produktu z PrestaShop jako głównej nazwy produktu, z zachowaniem osobnej nazwy kombinacji.

## [0.7.57] - 2026-04-01
- Usunięcie przykładowej podpowiedzi z pola `HS Code` w formularzu danych produktu, aby puste pole nie sugerowało domyślnej wartości.

## [0.7.56] - 2026-04-01
- Dalsze dopracowanie popupu kalkulacji kosztu: jaśniejszy granat plakietek oraz dodanie stawki celnej do sekcji danych produktu.

## [0.7.55] - 2026-04-01
- Drobne dopracowanie popupu kalkulacji kosztu: dodanie `HS Code` do danych produktu oraz wzmocnienie wizualne strzałki `→`, żeby była spójna z pozostałymi operatorami.

## [0.7.54] - 2026-04-01
- Jaśniejsza plakietka i pole edycji dla `Narzut` w popupie kalkulacji kosztu, tak aby wyróżniały się od ciemnych pól, ale nadal pozostawały spójne z układem wzoru.

## [0.7.53] - 2026-04-01
- Aktualizacja wyglądu wzorów w popupie kalkulacji kosztu: ciemno-granatowe plakietki z jasnym tekstem, niebieskie plakietki wyników po `=`, zwężone sloty mieszczące się w jednym rzędzie oraz wyrównane szerokości dla ceny zakupu, kursu waluty, ceny w PLN i transportu 1 szt.

## [0.7.52] - 2026-04-01
- Dopracowanie czytelności wzorów w popupie kalkulacji kosztu: mocniejszy kontrast etykiet i operatorów oraz ujednolicenie stylu symboli `×`, `→`, `+`, `=`, żeby nie rozsuwały wyrównania między wierszem wzoru i obliczeń.

## [0.7.51] - 2026-04-01
- Korekta szerokości slotów i odstępów w popupie kalkulacji kosztu, tak aby wzory i wartości mieściły się w jednym rzędzie bez wychodzenia poza modal.

## [0.7.50] - 2026-04-01
- Dopracowanie popupu kalkulacji kosztu: czytelniejsze nagłówki sekcji, wyższy kontrast etykiet, stałe wyrównanie slotów etykieta/wartość we wzorach, przeniesienie kosztu transportu 1 szt. do danych produktu oraz zmiana etykiety na `Ilość w kartonie`.

## [0.7.49] - 2026-04-01
- Poszerzenie modala kalkulacji kosztu, skrócenie formatu kursu waluty do 2 miejsc po przecinku oraz usunięcie mylącej podpowiedzi `6.5` z pola stawki celnej, gdy produkt nie ma ustawionej wartości.

## [0.7.48] - 2026-04-01
- Przebudowa prezentacji kalkulacji kosztu w produktach zamówienia: układ danych produktu w 2 kolumnach, widoczny koszt transportu 1 szt., czytelne wzory z podstawionymi wartościami oraz wyliczenia marży i czystego zysku.

## [0.7.47] - 2026-04-01
- Naprawa modala kalkulacji kosztu w produktach zamówienia po poprawce liczenia transportu według wagi, tak aby popup znów otwierał się poprawnie.

## [0.7.46] - 2026-04-01
- Uporządkowanie popupu kalkulacji kosztu w produktach zamówienia: listy z liniami między wierszami, szybkiej edycji narzutu i czytelniejszego nagłówka produktu oraz kombinacji.
- Zmiana liczenia kosztu transportu 1 szt. w kalkulacji kosztu na udział według wagi produktu względem łącznej wagi zamówienia.

## [0.7.45] - 2026-04-01
- Stabilizacja ładowania stylów w zakładce Produkty w nowoczesnym layoucie przez przeniesienie legacy CSS do sekcji `stylesheets`.
- Odświeżanie miniaturek produktów na liście pozycji zamówienia z aktualnego obrazka kombinacji albo produktu.
- Dodanie powiększenia zdjęcia produktu po najechaniu w liście pozycji zamówienia.
- Dodanie automatycznego czyszczenia starych ZIP-ów w skrypcie release, z domyślnym limitem 5 najnowszych buildów.

## [0.7.44] - 2026-04-01
- Odświeżanie EAN na liście produktów w zamówieniu z fallbackiem do aktualnego EAN kombinacji albo produktu, także dla starszych pozycji zamówień.
- Dodanie konfiguracji remote'ów git oraz skryptów do ustawiania i wypychania repo źródłowego i repo buildów.

## [0.7.43] - 2026-04-01
- Poprawa podglądu i pobierania plików PDF w zamówieniach po migracji ścieżek modułu.

## [0.7.42] - 2026-04-01
- Ujednolicenie geometrii pól i przycisków w formularzu dodawania plików do zamówienia przez wspólny grid form-group, identyczny wiersz kontrolki 54px i wymuszone centrowanie treści przycisków.

## [0.7.41] - 2026-04-01
- Ostateczne wyrównanie przycisków Dodaj i Anuluj w formularzu dodawania plików do zamówienia przez nadanie im tego samego wrappera form-group i pustej etykiety-placeholdera co polom po lewej.

## [0.7.40] - 2026-03-31
- Dalsze wyrównanie przycisków Dodaj i Anuluj w formularzu dodawania plików do zamówienia przez usunięcie sztucznego labela i ustawienie czystego offsetu CSS zgodnego z wysokością etykiet pól.

## [0.7.39] - 2026-03-31
- Wyrównanie przycisków Dodaj i Anuluj w formularzu dodawania plików do zamówienia do wysokości pól tekstowych oraz do wspólnej linii bazowej formularza.

## [0.7.38] - 2026-03-31
- Uproszczenie podglądu PDF w zamówieniach przez osadzenie pliku bezpośrednio w iframe zamiast pobierania go przez fetch do blob, co poprawia zgodność i stabilność podglądu w BO.

## [0.7.37] - 2026-03-31
- Dodanie krótkiego, przyjemnego dźwięku potwierdzenia po poprawnym zeskanowaniu produktu.
- Dodanie testowego pola EAN13 w badge skanera z obsługą Enter, żeby łatwo testować skaner bez urządzenia.

## [0.7.36] - 2026-03-31
- Zastąpienie ikon `barcode` i `barcode_reader` własnymi inline SVG, żeby przycisk skanera i aktywny badge wyglądały poprawnie także w PrestaShop 8.

## [0.7.35] - 2026-03-31
- Naprawa pustego ekranu Produkty w nowoczesnym layoucie przez centralne przekazywanie `licenseStatus` do wszystkich widoków Twig z `AbstractInventoryController`.
- Ujednolicenie obsługi statusu licencji między Produktami, Dostawcami, Zamówieniami i Ustawieniami.

## [0.7.34] - 2026-03-31
- Uspójnienie ładowania listy Produktów między PS 8 i 9 przez zdjęcie wtórnej blokady licencji z endpointu AJAX FetchProducts, gdy ekran już uznał licencję za poprawną.
- Dodanie zwracania i pokazywania realnego błędu backendu w tabeli Produktów zamiast ogólnego komunikatu "Błąd ładowania danych".

## [0.7.33] - 2026-03-31
- - Przeniesienie komunikatu o braku licencji w legacy zakładce Produkty na PS 8 nad panel, żeby brak ładowania tabeli był czytelny zamiast wyglądać jak awaria.

## [0.7.32] - 2026-03-31
- - Uspokojenie aktywnego stylu przycisku skanera w PS 8, żeby nie wyglądał jak drugi pływający badge po włączeniu skanera.

## [0.7.31] - 2026-03-31
- - Przeniesienie komunikatu o braku licencji nad panele we wszystkich nowoczesnych zakładkach modułu.
- - Zablokowanie renderowania paneli Produkty, Dostawcy i Zamówienia bez ważnej licencji, zamiast ładowania części danych mimo błędu.

## [0.7.30] - 2026-03-31
- - Zamiana $(document).ready(...) na $(...) w JS modułu, żeby usunąć warning JQMIGRATE o deprecated ready event.

## [0.7.29] - 2026-03-31
- - Przywrócenie realnego fallbacku legacy dla ekranów Produkty, Dostawcy i Zamówienia na PrestaShop 8, zamiast bezwarunkowego redirectu do Symfony.
- - Ujednolicenie _legacy_link dla Dostawców i Zamówień, żeby menu, breadcrumbs i mapowanie uprawnień były spójne między PS 8 i 9.
- - Usunięcie twardego AccessDenied z bazy kontrolerów Symfony na rzecz jednej miękkiej ścieżki sprawdzania licencji.

## [0.7.28] - 2026-03-31
- - Przywrócenie własnego stylu zakładek modułu po nieudanej próbie użycia natywnych tabów BO na PS 8.

## [0.7.27] - 2026-03-31
- - Miękka obsługa braku licencji w BO na PS 8/9: moduł pokazuje komunikat zamiast rzucać AccessDenied przy wejściu do Ustawień, Dostawców i Zamówień.

## [0.7.26] - 2026-03-31
- Próba przepięcia nowoczesnych zakładek modułu na natywny komponent nav-tabs PrestaShop z ograniczeniem własnego CSS do ikon i odstępów.

## [0.7.25] - 2026-03-31
- Zmniejszenie wysokości paska zakładek BO o 6 px w nowoczesnym layoucie modułu.

## [0.7.24] - 2026-03-31
- Naprawa błędu ładowania tabeli Produkty spowodowanego brakującą zmienną carton_gross_weight w renderze wierszy.

## [0.7.23] - 2026-03-31
- Pełne usunięcie zależności od Tools::link_rewrite() przy slugowaniu statusów zamówień, co naprawia ekrany Ustawień i Zamówień w PS9.

## [0.7.22] - 2026-03-31
- Naprawa błędu PS9 przy zmianie kolorów statusów zamówień przez usunięcie zależności od Tools::link_rewrite().

## [0.7.21] - 2026-03-31
- Ujednolicenie stylu głównego panelu Produkty z kartami używanymi w Dostawcach i Zamówieniach.

## [0.7.20] - 2026-03-31
- Zmiana ikon skanera: przycisk używa teraz ikony barcode, a aktywny badge migającej ikony barcode_reader.

## [0.7.19] - 2026-03-31
- Ujednolicenie styli zakładek BO i spacingu Ustawień z pozostałymi sekcjami modułu.
- Przeniesienie wspólnego stylu kart i tabów do nowoczesnego layoutu modułu.

## [0.7.18] - 2026-03-31
- Przepięcie zakładki Ustawienia i konfiguracji modułu z AdminModules na dedykowany kontroler AdminCargoStockManagerSettings.

## [0.7.17] - 2026-03-31
- Ujednolicenie kart i motywu zakładki Ustawienia z pozostałymi zakładkami modułu.

## [0.7.16] - 2026-03-31
- Poprawa resetu top spacingu kontenera Ustawień w nowoczesnym BO.

## [0.7.15] - 2026-03-31
- Dodanie efektu hover wiersza w tabeli dostawców jak w tabeli zamówień.

## [0.7.14] - 2026-03-31
- Ujednolicenie wysokości wierszy na listach dostawców, zamówień i tabelach ustawień.

## [0.7.13] - 2026-03-31
- Ukrycie listy dostawców podczas edycji lub dodawania dostawcy.

## [0.7.12] - 2026-03-31
- Wyrównanie górnego położenia pierwszego panelu w zakładce Ustawienia w nowoczesnym BO.

## [0.7.11] - 2026-03-31
- Zmiana ikony zakładki Produkty na category.

## [0.7.10] - 2026-03-31
- Dodanie demo dostawców Apple, Xiaomi i Samsung z publicznymi adresami firm przy czystej instalacji.

## [0.7.9] - 2026-03-31
- Zmiana ikony zakładki Dostawcy na factory.

## [0.7.8] - 2026-03-31
- Usunięcie zduplikowanego przewoźnika UPS z danych demo.

## [0.7.7] - 2026-03-31
- Zmiana ikony głównego wpisu BO i zakładki produktów na statek.

## [0.7.6] - 2026-03-31
- Naprawa etykiety menu BO: klucz inventory_menu jest teraz poprawnie mapowany na tekst CargoStock.

## [0.7.5] - 2026-03-31
- Skrócenie etykiety głównego wpisu BO z CargoStock Manager do CargoStock, aby nazwa nie zawijała się w bocznym menu.

## [0.7.4] - 2026-03-31
- Przeniesienie demo przewoźników i rodzajów dokumentów do jednej sekcji stałych w serwisie modułu dla łatwiejszego zarządzania.

## [0.7.3] - 2026-03-31
- Nowa instalacja seeduje również demo dane ustawień: przewoźników i rodzaje dokumentów dla zamówień.

## [0.7.2] - 2026-03-31
- Poprawa styli paneli w PrestaShop 9: karty modułu mają teraz jawne tło, obramowanie i cień zamiast przezroczystych paneli.

## [0.7.1] - 2026-03-31
- Naprawa klasy głównej modułu: usunięty konflikt nazw CargoStockManager/cargostockmanager powodujący fatal error przy instalacji.

## [0.7.0] - 2026-03-31
- Moduł został przełączony na czystą instalację pod techniczną nazwą `cargostockmanager`, bez wrappera dla starej nazwy.
- Usunięta została warstwa migracji danych i kompatybilności wstecznej dla wcześniejszej technicznej nazwy modułu.
- Kontrolery Symfony, widoki Twig i konfiguracja modułu odwołują się już wyłącznie do katalogu `cargostockmanager`.

## [0.6.12] - 2026-03-31
- Naprawiona zgodność instalacji z nowszym schematem `ps_access` w PrestaShop. Synchronizacja uprawnień child tabów BO wykonuje się tylko wtedy, gdy tabela ma legacy kolumny `view/add/edit/delete`, dzięki czemu aktualizacja nie wybucha błędem SQL `Unknown column 'view'`.

## [0.6.11] - 2026-03-31
- Linki zakładek i breadcrumbów w nowoczesnym layoucie BO są teraz budowane przez `Link::getAdminLink(...)` zamiast `generateUrl(...)`, co eliminuje błędne względne ścieżki typu `admin_domain`.

## [0.6.10] - 2026-03-31
- Dodana synchronizacja praw dostępu `ps_access` z głównego taba modułu na child taby `Produkty`, `Dostawcy`, `Zamówienia`, `Ustawienia`, aby wpisy były widoczne w bocznym menu także po aktualizacji istniejącej instalacji.

## [0.6.9] - 2026-03-31
- Włączone aktywne podmenu BO dla `Produkty`, `Dostawcy`, `Zamówienia`, `Ustawienia`, aby wpisy były widoczne w bocznym menu po aktualizacji.

## [0.6.8] - 2026-03-31
- Produkty w BO znów używają sprawdzonych uprawnień legacy `AdminCargoStockManager` dla routingu i AJAX, co usuwa komunikat `Access Denied` po dodaniu child taba `Produkty`.

## [0.6.7] - 2026-03-31
- Uzupełnione dane przekazywane do `configure.tpl`: konfiguracja modułu dostaje teraz komplet wymaganych zmiennych Smarty, w tym komunikaty, URL AJAX, przewoźników, typy dokumentów i opcje Incoterms.

## [0.6.6] - 2026-03-31
- Naprawiony kolejny błąd SQL przy wyszukiwaniu tabów BO. Helper `findTabIdByClassName()` nie dokleja już własnego `LIMIT 1`, bo PrestaShop robi to sam w `getValue()`.

## [0.6.5] - 2026-03-31
- Naprawiony błąd SQL na MariaDB podczas sprawdzania istnienia tabel modułu. Moduł nie używa już `SHOW TABLES LIKE ...` w miejscu, gdzie PrestaShop dopisuje `LIMIT 1`.

## [0.6.4] - 2026-03-31
- Utwardzona instalacja i aktualizacja tabów BO: moduł sprawdza teraz taby także bezpośrednio w bazie, co zapobiega duplikatom i błędom SQL przy częściowo zaktualizowanym stanie menu.
- Zachowane podmenu `Produkty`, `Dostawcy`, `Zamówienia`, `Ustawienia`.

## [0.6.3] - 2026-03-31
- Dodane podmenu BO pod `CargoStock Manager`: `Produkty`, `Dostawcy`, `Zamówienia`, `Ustawienia`.
- Widok produktów został przepięty na osobny child tab `AdminCargoStockManagerProducts`, dzięki czemu struktura menu jest pełna i spójna.

## [0.6.2] - 2026-03-31
- Poprawione ścieżki ładowania szablonów modułu po hotfixie kompatybilności, aby konfiguracja nie szukała widoków w katalogu nowej wersji technicznej modułu.
- Legacy konfiguracja modułu i nowoczesne widoki Twig odwołują się teraz do właściwego katalogu technicznego dla ówczesnej wersji kompatybilności.

## [0.6.1] - 2026-03-31
- Hotfix kompatybilności aktualizacji: paczka znów używa ówczesnej technicznej nazwy modułu, aby aktualizacja z BO nie kończyła się błędem 500.
- Zachowany branding `CargoStock Manager` w interfejsie oraz migracja danych do nowych tabel `cargostockmanager_*`.
- Poprawione ścieżki uploadów plików zamówień, aby działały poprawnie po aktualizacji kompatybilnej.

## [0.6.0] - 2026-03-31
- Pełny technical rename modułu do `cargostockmanager` w plikach, klasach, namespace'ach, trasach, tłumaczeniach i identyfikatorach pomocniczych.
- Dodana automatyczna migracja danych legacy: konfiguracji, rekordów modułu i tabów BO, tabel legacy, nazw wybranych kolumn oraz ścieżek plików zapisanych w bazie.
- Zachowana zgodność z istniejącymi licencjami wystawionymi jeszcze dla legacy nazwy modułu.

## [0.5.133] - 2026-03-31
- Przeniesiony link modułu z `Katalog` poziom wyżej do sekcji `SELL`, aby był widoczny od razu po wejściu do BO.
- Zmieniona nazwa modułu i głównego wpisu BO na `CargoStock Manager` oraz ustawiona ikona `train`.

## [0.5.132] - 2026-03-30
- Zmiana kolejności ikon w akacjach listy zamówień tak, aby śledzenie było na drugim miejscu.

## [0.5.131] - 2026-03-30
- Przeniesienie wersji modułu w stopce na lewą stronę.
- Usunięcie efektu obramowania po najechaniu na skrajne numery stron w paginacji.

## [0.5.130] - 2026-03-30
- Poprawa wyrównania sekcji Sprzedawca, Nabywca i Szczegóły w PDF zamówienia.

## [0.5.129] - 2026-03-30
- Zmiana kolejności ikon w kolumnie akcji zamówień, tak aby Usuń było pierwsze.

## [0.5.128] - 2026-03-29
- Poprawa potwierdzenia usuwania zamówień na liście zamówień.

## [0.5.127] - 2026-03-29
- Dodanie ikony usuwania dostawców z potwierdzeniem oraz blokadą usuwania dostawców powiązanych z zamówieniami.

## [0.5.126] - 2026-03-29
- Usunięcie ikon udostępniania i podglądu z listy zamówień oraz wyczyszczenie powiązanego kodu.
- Dodanie potwierdzenia usuwania zamówień także w legacy widoku listy.
- Poprawa zapisu jednostki objętości na m³ w tabelach.

## [0.5.125] - 2026-03-29
- Naprawione ładowanie listy produktów przez przeniesienie sprawdzania zamówień poza główne zapytanie tabeli.

## [0.5.124] - 2026-03-29
- Naprawione ładowanie listy produktów po dodaniu sprawdzania zamówień w kolumnie akcji.

## [0.5.123] - 2026-03-29
- Ukryta ikonka listy zamówień w produktach, gdy produkt nie występuje w żadnym zamówieniu.
- Ujednolicony styl ikonek akcji w produktach, zamówieniach, dostawcach i ustawieniach do stylu BO PrestaShop.
- Notatki w zamówieniach przeniesione do popupu i pokazane jako karteczki bez tła panelu.

## [0.5.122] - 2026-03-29
- Dodane notatki do zamówień jako żółte karteczki w widoku zamówienia.
- Dopasowany styl ikonki listy zamówień w akcjach produktów do pozostałych ikon.

## [0.5.121] - 2026-03-29
- Dodana kolumna z ilością zamówień na liście dostawców.
- Dodane skróty do listy zamówień z poziomu dostawców i produktów.
- Usunięty efekt przyciemnienia tła i ramki w hoverze paginacji produktów i zamówień.

## [0.5.120] - 2026-03-29
- Dodana paginacja na liście zamówień w tym samym stylu co na liście produktów.

## [0.5.119] - 2026-03-29
- Usunięte obramowanie nieaktywnej skrajnej strony w paginacji listy produktów.

## [0.5.118] - 2026-03-29
- Poprawione linki śledzenia przesyłek dla DHL i UPS oraz dodana obsługa FedEx.
- Usunięte obramowanie strzałek w paginacji listy produktów.

## [0.5.117] - 2026-03-29
- Lista produktów: paginacja na dole dopasowana bliżej domyślnych styli BO PrestaShop.

## [0.5.116] - 2026-03-29
- Lista produktów: paginacja na dole ma spokojniejsze odstępy i cyfry w rozmiarze dopasowanym do tekstu statusu.
- Dostawcy: usunięta funkcja Aktywny z widoku, formularza, zapisu i tabeli modułu.

## [0.5.115] - 2026-03-29
- Lista produktów: odchudzone i zmniejszone strzałki paginacji na dole tabeli.

## [0.5.114] - 2026-03-29
- Lista zamówień: w kolumnie akcji dodana ikona śledzenia przesyłki dla zamówień z numerem śledzenia.

## [0.5.113] - 2026-03-29
- Lista zamówień: w kolumnie akcji dodana ikona ostrzeżenia dla zamówień zawierających niepowiązane produkty.

## [0.5.112] - 2026-03-29
- Widok zamówienia: usunięte duplikaty produktów w wynikach wyszukiwania przy ponownym łączeniu pozycji z katalogiem PrestaShop.

## [0.5.111] - 2026-03-29
- Widok zamówienia: ponowne połączenie produktu podmienia istniejącą pozycję zamiast dodawać nową i zachowuje jej ilość oraz cenę.

## [0.5.110] - 2026-03-29
- Widok zamówienia: pole wagi w popupie edycji produktu jest połączone ze standardową wagą produktu i kombinacji w PrestaShop.
- Widok zamówienia: dla niepowiązanych pozycji dodana ikonka ponownego połączenia produktu z katalogiem PrestaShop.
- Widok zamówienia: dodane potwierdzenia usuwania dla zamówień, plików i produktów w zamówieniu.

## [0.5.109] - 2026-03-29
- Lista zamówień: dodana wyszukiwarka po numerze zamówienia, dostawcy, numerze przesyłki i numerze faktury.
- Lista zamówień: sortowanie według ID malejąco, najnowsze zamówienia na górze.
- Podgląd zamówienia: nawigacja poprzednie/następne działa po najbliższym niższym i wyższym ID, także przy lukach w numeracji.
- Tabela produktów w zamówieniu: waga pozycji jest pobierana z aktualnej wagi produktu i kombinacji zamiast z pustej lub nieaktualnej wartości rekordu zamówienia.

## [0.5.108] - 2026-03-29
- Nowe zamówienia zakupowe są tworzone bez przykładowych produktów.
- Nawigacja w podglądzie zamówienia pozwala przechodzić do starszego i nowszego zamówienia przyciskami obok powrotu do listy.

## [0.5.107] - 2026-03-29
- Podgląd zamówienia otrzymał przyciski poprzednie/następne obok przycisku Powrót do listy.

## [0.5.106] - 2026-03-29
- Dostawcy w module są teraz niezależni od dostawców PrestaShop i używają własnej tabeli modułu.
- Zamówienia zakupowe korzystają z listy dostawców modułu zamiast z danych `ps_supplier`.

## [0.5.105] - 2026-03-29
- Wyrównane przyciski w formularzu dodawania plików do zamówienia.
- Zmniejszona domyślna wysokość przycisków w formularzu dodawania plików dla lżejszego wyglądu.

## [0.5.104] - 2026-03-29
- Poprawiony podgląd PDF w zamówieniach przez ładowanie dokumentu do modala z użyciem blob URL.
- Ujednolicony układ formularza dodawania plików: pola i przyciski w jednej linii oraz spójna wysokość inputa i selecta.
- Bardziej czytelna, wypełniona ikona PDF w widoku produktów.

## [0.5.103] - 2026-03-29
- Naprawiony podgląd PDF w zamówieniach zakupowych bez błędu 404 w modalu.
- Poprawiony układ formularza dodawania plików w zamówieniach.
- Przyciski Dodaj i Anuluj przy wybranym pliku ustawione w jednej linii.

## [0.5.102] - 2026-03-29
- Powiększone nagłówki sekcji w menu filtrów.
- Etykiety filtrów kolumn i opcji skrócone oraz ujednolicone z nazwami w interfejsie.
- Miniatury produktów na liście nie są już ściskane przy wąskim oknie i dużej liczbie kolumn.

# Changelog

## [0.5.101] - 2026-03-28
- Modal „Edytuj” na stronie Produkty: zawartość przebudowana wizualnie w stylu modala „Rentowność”.
- Dane produktu, logistyki i pola dodatkowe pokazują się teraz w kartach z liniowym układem wartości, zachowując szybką edycję po kliknięciu.

## [0.5.100] - 2026-03-28
- Poprawka regresji ikony „Edytuj” (Safari): usunięty błąd `setSharedScannerState is not defined`.
- Dodane stabilne aliasy `window.cargoStockManagerSetScannerState` i `window.cargoStockManagerGetScannerState`, aby wyeliminować problemy z zakresem funkcji między blokami skryptu.

## [0.5.99] - 2026-03-28
- Paginacja na stronie „Produkty”: skorygowano rozmiar numerów skrajnych stron (pierwsza/ostatnia), aby nie były przeskalowane.
- Duży rozmiar pozostawiono tylko dla strzałek nawigacji, zgodnie z docelowym stylem.

## [0.5.98] - 2026-03-28
- Modal „Edytuj” na stronie Produkty: poprawione wczytywanie sekcji danych i szybkiej edycji (nie tylko nagłówek/obrazek).
- Stan danych modala ujednolicony przez współdzielony storage (`window.cargoStockManagerScannerState`), aby uniknąć rozjazdów między scope skryptów.

## [0.5.97] - 2026-03-28
- Poprawka ikony „Edytuj” na stronie Produkty: usunięty błąd `renderScannerState is not defined` w Safari.
- Funkcje modala skanera (`openScannerModal`, `renderScannerState`, `renderScannerEan`) wystawione przez bezpieczne aliasy na `window`, aby uniknąć problemów z zakresem funkcji.

## [0.5.96] - 2026-03-28
- Poprawka ikony edycji produktu w Safari: usunięty błąd `toInt is not defined` blokujący otwieranie popupu.
- Parsery liczb dla danych przycisku edycji przeniesione lokalnie do handlera kliknięcia, niezależnie od zasięgu funkcji pomocniczych.

## [0.5.95] - 2026-03-28
- Poprawka ikony edycji produktu w tabeli „Produkty”: usunięty błąd JS `renderScannerEan is not defined`, który blokował otwieranie popupu.
- Dodano bezpieczny fallback renderowania EAN w popupie, gdy funkcja renderująca kod kreskowy nie jest dostępna.

## [0.5.94] - 2026-03-28
- Strona „Produkty”: dopracowane style strzałek paginacji (`<` i `>`) — większe, wycentrowane, zgodne z docelowym wyglądem.
- Ujednolicony styl przycisków paginacji (hover/disabled) dla spójnego wyglądu paska pod tabelą produktów.

## [0.5.93] - 2026-03-28
- Strona „Produkty”: poprawione style paginacji pod tabelą.
- Usunięto efekt podwójnych strzałek przy przyciskach poprzednia/następna (konflikt globalnych pseudo-elementów).
- Pasek paginacji wyśrodkowany.

## [0.5.92] - 2026-03-28
- Tabela produktów: w kolumnie „Akcje” dodano ikonę edycji (`edit`) otwierającą popup „Dane modułowe produktu”.
- Popup edycji z akcji produktu korzysta z tych samych pól i mechanizmu zapisu co modal skanera (dane dodatkowe produktu).
- Lista produktów: zapytanie rozszerzone o `module_model` i `logistics_description`, aby popup z akcji był wypełniany pełnymi danymi.

## [0.5.91] - 2026-03-28
- Naprawa błędu ładowania tabeli Produkty po aktualizacji fallbacków wymiarów.
- Odczyt wymiarów oparty o standardowe pola produktu (`product.width`, `product.height`, `product.depth`) z fallbackiem do danych modułu dla starszych rekordów.

## [0.5.90] - 2026-03-28
- Modal „Produkty w zamówieniu -> Edycja produktu”: poprawione wczytywanie wymiarów z danych standardowych produktu.
- Ujednolicony fallback odczytu wymiarów między listą produktów, skanerem i pozycjami zamówienia.

## [0.5.89] - 2026-03-28
- Tabela produktów: nagłówek kolumny „Cło %” zmieniony na „Cło” (wartość procentowa pozostaje w komórkach).
- Szybka edycja wymiarów: kolejność pól zgodna z PrestaShop (S/W/G).

## [0.5.88] - 2026-03-28
- Wymiary produktu/kartonu podpięte pod standardowe pola PrestaShop (`depth`, `width`, `height`) zamiast osobnej tabeli dla tego zakresu danych.
- Ujednolicenie nazewnictwa w UI: „Wymiary kartonu” -> „Wymiary”.

## [0.5.87] - 2026-03-28
- Skaner: poprawka odczytu statusu baterii „Dump Energy” (np. 42%) — znak % nie jest już zamieniany na cyfrę 5, więc poziom nie zawyża się do 100%.

## [0.5.19] - 2026-03-27
- Tabela produktów: kolumna „Szt. / karton" przemianowana na „Ilość w kartonie"

## [0.5.18] - 2026-03-27
- Tabela produktów: szybka edycja inline dla kolumn Materiał, HS Code, Cło % (klik → input, Enter=zapis, Esc=anuluj)

## [0.5.17] - 2026-03-27
- Tabela produktów: ikony akcji (bar_chart, calculate, visibility_off) bez gradientu — styl identyczny jak w tabeli zamówień
- Filtry: badge liczy tylko aktywne filtry „Pokaż tylko", nie ukryte kolumny
- Nagłówki grup filtrów: kolor PS BO, linia separatora, lepiej czytelne

## [0.5.16] - 2026-03-27
- Tabela produktów: nowe kolumny Materiał, HS Code, Cło % (toggleowalne, domyślnie widoczne)
- Filtry podzielone na 2 kolumny: „Pokaż kolumny" i „Pokaż tylko"
- Ikony akcji w tabeli produktów: bar_chart, calculate, visibility_off (Material Icons)
- Ikona kalkulatora kosztów w zamówieniu zmieniona na calculate (Material Icons)
- Naprawa licznika filtrów: badge zlicza dynamicznie przez data-filter-type

## [0.5.15] - 2026-03-27
- PDF zamówienia: nagłówki sekcji — padding renderowany poprawnie (zamiana div→table, mPDF fix)

## [0.5.14] - 2026-03-27
- PDF zamówienia: usunięto „Data dostawy" z sekcji Szczegóły
- PDF zamówienia: nagłówki sekcji — zwiększony padding (4pt 8pt)
- PDF zamówienia: etykiety pól (Data zamówienia, Przewoźnik itp.) — czarny kolor zamiast szarego

## [0.5.13] - 2026-03-27
- PDF zamówienia: „Dostawca" → „Sprzedawca", „Adres dostawy" → „Nabywca"
- PDF zamówienia: nagłówki sekcji — biały tekst na ciemnym tle (#2c2c2c), wyrównane do góry
- PDF zamówienia: usunięto pole „Status" z sekcji Szczegóły
- PDF zamówienia: obrazki produktów z miniatury (small_default) zamiast oryginału

## [0.5.12] - 2026-03-27
- Popup kalkulacji kosztów produktu: miniatura (small_default) zamiast oryginału 1600px

## [0.5.11] - 2026-03-27
- Tabela produktów: miniaturka (small_default) zamiast oryginału
- Hover preview: obrazek medium (home_default ~250px) zamiast oryginału 1600px
- Karta hover: position:fixed + z-index:99999 — nie chodzi pod żaden element PS BO
- Pozycja karty hover obliczana przez JS (getBoundingClientRect) — działa poprawnie dla pierwszego i ostatniego wiersza

## [0.5.10] - 2026-03-27
- Tabela produktów zamówienia: miniatury (small_default, ~98×98px) zamiast oryginałów 1600×1600
- Modal dodawania produktu: miniatury zamiast oryginałów
- Popup kosztu produktu nadal używa oryginalnego obrazka (wyświetlany w większym rozmiarze)

## [0.5.9] - 2026-03-27
- Modal danych modułowych: grid 4-kolumnowy zamiast 2-kolumnowego
- Pole Materiał i Stawka celna przeniesione do wiersza Objętości (obok wymiarów)
- HS Code i Szt. w kartonie w kolejnym wierszu (po pół szerokości)
- Wymiary: usunięto „cm" z placeholderów, dodano jeden wspólny suffix „cm" po trzecim wymiarze

## [0.5.8] - 2026-03-27
- PDF zamówienia: ujednolicony rozmiar czcionki 8pt dla całego dokumentu (poza tytułem h1)
- PDF zamówienia: zmniejszona czcionka tabeli produktów (8pt nagłówki i komórki, 7pt model)
- PDF zamówienia: poprawione formatowanie sekcji między tytułem a tabelą (sec-title z podkreśleniem, wyrównane kolumny meta)
- PDF zamówienia: usunięta górna linia hr pod h1, divider tylko przed tabelą produktów

## [0.5.7] - 2026-03-27
- Poprawka ikony „i" w tabeli produktów zamówienia: kolor dopasowany do pozostałych ikon
- Poprawka ikony PDF: zmiana `<i>` na `<span>` z `color:inherit` — kolor zgodny z przyciskiem
- Podgląd PDF: szerokość dopasowana do dokumentu (860px, wycentrowany), blur tła widoczny po bokach
- Podgląd PDF: zajmuje prawie całą wysokość okna przeglądarki (inset 2vh)

## [0.5.6] - 2026-03-27
- Panel Szczegóły zamówienia: pole „Waluta" (kod waluty, edycja inline AJAX)
- Panel Szczegóły zamówienia: pole „Kurs waluty" (edycja inline AJAX, walidacja > 0)
- Wartości obu pól odświeżają się dynamicznie po zapisaniu

## [0.5.5] - 2026-03-27
- Poprawka mechanizmu aktualizacji: wersja modułu aktualizowana w bazie danych (ps_module) po auto-aktualizacji
- Poprawka: OPcache resetowany po skopiowaniu nowych plików modułu
- Poprawka: porównanie wersji przy sprawdzaniu aktualizacji oparte na wersji z bazy danych (odporna na stały OPcache)
- Dodano katalog upgrade/ z wymaganymi skryptami dla aktualizacji przez Menedżer Modułów PrestaShop

## [0.5.4] - 2026-03-27
- Kalkulacja kosztu produktu: przycisk „i" w kolumnie akcji tabeli pozycji zamówienia
- Popup z danymi produktu (model, EAN, HS Code, materiał, opis, waga, szt. w kartonie, objętość)
- Kalkulacja krok po kroku: cena × kurs → koszt całkowity → narzut → cena detaliczna netto/brutto
- Narzut edytowalny inline, zapisywany w localStorage
- Marża obliczana dynamicznie

## [0.5.3] - 2026-03-27
- Poprawka: paczka ZIP zawiera teraz folder `cargostockmanager/` (był błędny `cargostockmanager-source/`)
- Przycisk aktualizacji: zmieniono tekst na „Dostępna aktualizacja X.Y.Z"

## [0.5.2] - 2026-03-27
- Breadcrumb ujednolicony we wszystkich zakładkach: „Raport magazynowy > [sekcja]"

## [0.5.1] - 2026-03-27
- Panel „Pliki" przemianowany na „Dokumenty"
- Kolumna „Plik" w tabeli zmieniona na „Nazwa pliku"
- Lista plików wyświetlana przed uploaderem
- Ikona podglądu tylko dla PDF i obrazów (ukryta dla xls, zip itp.)
- Podgląd fullscreen z rozmyciem tła (backdrop-filter blur)
- Poprawka Safari: iframe PDF odtwarzany od zera przy każdym otwarciu (brak artefaktu zoomowania)
- Podgląd zamknięty klawiszem Escape lub kliknięciem tła

## [0.5.0] - 2026-03-26
- Modal dodawania produktu do zamówienia: domyślna ilość = szt. w kartonie (fallback 1)
- Modal dodawania produktu: usunięto kolumnę „Cena domyślna"
- Modal dodawania produktu: pole ceny zakupu wstępnie wypełnione ostatnią ceną z poprzednich zamówień

## [0.4.9] - 2026-03-27
- Poprawka: tooltip incoterm zakotwiczony do prawej krawędzi — nie wychodzi poza ekran

## [0.4.8] - 2026-03-27
- Tabela Incoterms w ustawieniach: kompaktowy dwukolumnowy grid, kody jako szare plakietki
- Tooltip incoterm: CSS-only (ciemne tło, biały tekst), pojawia się nad kodem po najechaniu

## [0.4.7] - 2026-03-27
- Opisy Incoterms 2020 dodane do każdego kodu warunków dostawy
- Ustawienia: tabela referencyjna Incoterms z opisami
- Zamówienie: tooltip z opisem po najechaniu na kod warunków dostawy
- Tooltip aktualizuje się dynamicznie po zmianie warunków przez edycję inline

## [0.4.6] - 2026-03-27
- Pole „Nr śledzenia" w sekcji Szczegóły zamówienia (edycja inline AJAX)
- Link śledzenia przesyłki: UPS i DHL Express podlinkowane automatycznie po wykryciu nazwy przewoźnika
- Kolorowe plakietki przewoźnika przy polu Przewoźnik (UPS brązowo-złoty, DHL żółto-czerwony, inne szare)
- Badge i link aktualizują się dynamicznie po zmianie przewoźnika lub numeru śledzenia

## [0.4.5] - 2026-03-27
- Przywrócono tekst „Wartość zamówienia:" przy czerwonej plakietce; wartość pogrubiona
- Przycisk PDF bardziej widoczny (btn-outline-secondary z ikoną i napisem „PDF")

## [0.4.4] - 2026-03-26
- Ustawienia > Informacje o module: uproszczony widok — zwykły tekst w tabeli zamiast kafelków
- Przycisk „Przywróć" w liście ukrytych produktów zastąpiony ikoną `replay` (styl jak ikona usuń)
- Przyciski „Dodaj przewoźnika", „Dodaj rodzaj", „Dodaj status" w stylu niebieskiego przycisku BO (`btn-primary` + ikona `add`)
- Podgląd pliku (PDF/obraz): pełnoekranowy modal bez paddingu, uproszczony (tylko przycisk zamknij)
- Suma kolumny Waga w tabeli produktów zamówienia: 1 miejsce po przecinku
- Suma kolumny Objętość w tabeli produktów zamówienia: 3 miejsca po przecinku
- Sekcja „Podsumowanie" w podglądzie zamówienia przemianowana na „Szczegóły"
- Wartość zamówienia wyświetlana jako czerwona plakietka w nagłówku sekcji Produkty
- Generowanie PDF zamówienia: ikona `picture_as_pdf` obok wartości, pobiera PDF z nr zamówienia, dostawcą, adresem dostawy, szczegółami i tabelą produktów

## [0.4.3] - 2026-03-26
- Cofnięto zmianę palety kolorów — przywrócono chromatic (czerwony→pomarańczowy→żółty→zielony→turkus→niebieski→fioletowy→szary→ciemny)

## [0.4.2] - 2026-03-26
- Paleta kolorów statusów dopasowana do kolorów plakietek z BO PrestaShop (wyciągnięte ze screenshotów)

## [0.4.1] - 2026-03-26
- Styl plakietek statusów oparty na natywnej klasie Bootstrap `.badge` (jak w BO PrestaShop)
- `background-color !important` zapewnia poprawny kolor bez konfliktu z motywem PS
- Paleta kolorów statusów odświeżona i ułożona chromatycznie (czerwony→pomarańczowy→żółty→zielony→turkus→niebieski→fioletowy→szary→ciemny)
- Usunięto martwy kod starego formularza statusów

## [0.4.0] - 2026-03-26
- Statusy zamówień: szybka edycja nazwy inline (klik → input, Enter=zapisz AJAX, Esc=anuluj)
- Statusy zamówień: zmiana koloru przez kliknięcie w swatch → zapis AJAX
- Usunięto przycisk „Zapisz" z sekcji statusów; adres dostawy ma własny przycisk zapisu
- Poprawka: plakietki statusów w kolumnie Podgląd mają teraz poprawny kolor (usunięto klasę `badge`)
- Ikona kosza w kolumnie Akcje statusów ujednolicona z poprzednimi tabelami

## [0.3.99] - 2026-03-26
- Poprawka: ponowna edycja numeru faktury wczytywała stare dane (błąd cache jQuery `.data()`)
- Poprawka: pole Przewoźnik używa teraz select z listy zdefiniowanych przewoźników
- Styl sekcji Dostawca ujednolicony z sekcją Adres dostawy (zwykły tekst, bez bold)
- Opis pliku skrócony w tabeli (ellipsis), pełna treść widoczna w tooltipie po najechaniu

## [0.3.98] - 2026-03-26
- Zmniejszone odstępy między wierszami w sekcji podsumowania podglądu zamówienia

## [0.3.97] - 2026-03-26
- Katalogi plików zamówień nazwane referencją zamówienia (np. `ZAK-001`) zamiast numerycznym ID

## [0.3.96] - 2026-03-26
- Szybka edycja opisu pliku inline w tabeli plików zamówienia (klik → input, Enter = zapis, Esc = anuluj)

# Changelog

## [0.3.95] - 2026-03-26
- Ikony podglądu i pobierania pliku w tabeli plików zamówienia
- Podgląd obrazów w oknie modalnym; PDF i inne pliki w iframe modalnym
- Pobieranie bezpośrednio na dysk (atrybut `download`)
- Szybka edycja typu dokumentu inline w tabeli plików (klik → select → zmiana = zapis AJAX)
- Edycja inline nazw przewoźników i rodzajów dokumentów w ustawieniach (klik → input, Enter = zapis, Esc = anuluj)
- Usunięto przycisk „Zapisz" z wierszy listy przewoźników i rodzajów dokumentów

## [0.3.94] - 2026-03-26
- Pliki zamówień zapisywane w katalogu modułu (`uploads/purchase_orders/`) zamiast w `upload/` PrestaShop, który blokuje dostęp HTTP
- Poprawka pobierania / podglądu pliku po uploadzie

## [0.3.93] - 2026-03-26
- Poprawka: JS zarządzania przewoźnikami i rodzajami dokumentów nie ładował się w nowoczesnym layoucie (blok w warunkowym `{if}`)

## [0.3.92] - 2026-03-26
- Poprawka: bindowanie paneli CRUD nie działało gdy DOMContentLoaded już wystąpił

## [0.3.91] - 2026-03-26
- Drag & drop upload plików w zamówieniu
- Selektor rodzaju dokumentu przy uploadzie
- Pole przewoźnika zmienione z tekstowego na select (lista z ustawień)
- Zarządzanie przewoźnikami i rodzajami dokumentów w ustawieniach (dodaj / edytuj / usuń, AJAX)
- Poprawka kolorów plakietek statusów (usunięto klasę `badge` kolidującą z Bootstrap)

## [0.3.90] - 2026-03-26
- Kod waluty wyświetlany w podsumowaniu wartości tabeli pozycji zamówienia

## [0.3.89] - 2026-03-26
- Usunięto kolumnę „Waga kartonu brutto" z tabeli
- Poprawka kolorów etykiet statusów zamówień (pełne tło + biały tekst)
- Ikona kosza z domyślnego zestawu PS w ustawieniach

## [0.3.88] - 2026-03-26
- Zmiana etykiety kolumny objętości jednostkowej na „Objętość"

## [0.3.87] - 2026-03-26
- Dodano pole „Sztuk w kartonie" w formularzu danych logistycznych produktu

## [0.3.86] - 2026-03-26
- Poprawka stylu pola stawki celnej (%)
- Formatowanie liczb z separatorem tysięcy w podsumowaniu

## [0.3.85] - 2026-03-26
- Wymiary w cm, pole masy brutto, stawka celna %, dwuwierszowa nazwa produktu, wiersz podsumowania pozycji

## [0.3.84] - 2026-03-26
- Hover i link na wierszach listy zamówień
- Hover na tabeli pozycji
- Kompaktowy układ wiersza objętości

## [0.3.72] – [0.3.83]
- Kolejne poprawki i usprawnienia UI zamówień zakupu, tabeli produktów i panelu ustawień
