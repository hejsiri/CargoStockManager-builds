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
- Build ZIP dodany bez aktualizacji `latest.json`, bo manifest wymaga podpisu prywatnym kluczem release.

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
- Uproszczenie podglądu PDF w zamówieniach przez osadzenie pliku bezpośrednio w iframe zamiast pobierania go przez fetch do blob.

## [0.7.37] - 2026-03-31
- Dodanie krótkiego, przyjemnego dźwięku potwierdzenia po poprawnym zeskanowaniu produktu.
- Dodanie testowego pola EAN13 w badge skanera z obsługą Enter, żeby łatwo testować skaner bez urządzenia.

## [0.7.36] - 2026-03-31
- Zastąpienie ikon barcode i barcode_reader własnymi inline SVG, żeby przycisk skanera i aktywny badge wyglądały poprawnie także w PrestaShop 8.

## [0.7.35] - 2026-03-31
- Naprawa pustego ekranu Produkty w nowoczesnym layoucie przez centralne przekazywanie licenseStatus do wszystkich widoków Twig z AbstractInventoryController.
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
- Pełne przełączenie modułu na techniczną nazwę `cargostockmanager` bez migracji danych ze starej instalacji.

# Changelog
<<<<<<< HEAD
## [0.7.45] - 2026-04-01
- Stabilizacja ładowania stylów w zakładce Produkty w nowoczesnym layoucie przez przeniesienie legacy CSS do sekcji `stylesheets`.
- Odświeżanie miniaturek produktów na liście pozycji zamówienia z aktualnego obrazka kombinacji albo produktu.
- Dodanie powiększenia zdjęcia produktu po najechaniu w liście pozycji zamówienia.
- Dodanie automatycznego czyszczenia starych ZIP-ów w skrypcie release, z domyślnym limitem 5 najnowszych buildów.

## [0.7.46] - 2026-04-01
- Uporządkowanie popupu kalkulacji kosztu w produktach zamówienia: listy z liniami między wierszami, szybkiej edycji narzutu i czytelniejszego nagłówka produktu oraz kombinacji.
- Zmiana liczenia kosztu transportu 1 szt. w kalkulacji kosztu na udział według wagi produktu względem łącznej wagi zamówienia.

## [0.7.47] - 2026-04-01
- Naprawa modala kalkulacji kosztu w produktach zamówienia po poprawce liczenia transportu według wagi, tak aby popup znów otwierał się poprawnie.

## [0.7.48] - 2026-04-01
- Przebudowa prezentacji kalkulacji kosztu w produktach zamówienia: układ danych produktu w 2 kolumnach, widoczny koszt transportu 1 szt., czytelne wzory z podstawionymi wartościami oraz wyliczenia marży i czystego zysku.

## [0.7.49] - 2026-04-01
- Poszerzenie modala kalkulacji kosztu, skrócenie formatu kursu waluty do 2 miejsc po przecinku oraz usunięcie mylącej podpowiedzi `6.5` z pola stawki celnej, gdy produkt nie ma ustawionej wartości.

## [0.7.50] - 2026-04-01
- Dopracowanie popupu kalkulacji kosztu: czytelniejsze nagłówki sekcji, wyższy kontrast etykiet, stałe wyrównanie slotów etykieta/wartość we wzorach, przeniesienie kosztu transportu 1 szt. do danych produktu oraz zmiana etykiety na `Ilość w kartonie`.

## [0.7.51] - 2026-04-01
- Korekta szerokości slotów i odstępów w popupie kalkulacji kosztu, tak aby wzory i wartości mieściły się w jednym rzędzie bez wychodzenia poza modal.

## [0.7.52] - 2026-04-01
- Dopracowanie czytelności wzorów w popupie kalkulacji kosztu: mocniejszy kontrast etykiet i operatorów oraz ujednolicenie stylu symboli `×`, `→`, `+`, `=`, żeby nie rozsuwały wyrównania między wierszem wzoru i obliczeń.

## [0.7.53] - 2026-04-01
- Aktualizacja wyglądu wzorów w popupie kalkulacji kosztu: ciemno-granatowe plakietki z jasnym tekstem, niebieskie plakietki wyników po `=`, zwężone sloty mieszczące się w jednym rzędzie oraz wyrównane szerokości dla ceny zakupu, kursu waluty, ceny w PLN i transportu 1 szt.

## [0.7.54] - 2026-04-01
- Jaśniejsza plakietka i pole edycji dla `Narzut` w popupie kalkulacji kosztu, tak aby wyróżniały się od ciemnych pól, ale nadal pozostawały spójne z układem wzoru.

## [0.7.55] - 2026-04-01
- Drobne dopracowanie popupu kalkulacji kosztu: dodanie `HS Code` do danych produktu oraz wzmocnienie wizualne strzałki `→`, żeby była spójna z pozostałymi operatorami.

## [0.7.56] - 2026-04-01
- Dalsze dopracowanie popupu kalkulacji kosztu: jaśniejszy granat plakietek oraz dodanie stawki celnej do sekcji danych produktu.

## [0.7.57] - 2026-04-01
- Usunięcie przykładowej podpowiedzi z pola `HS Code` w formularzu danych produktu, aby puste pole nie sugerowało domyślnej wartości.

## [0.7.58] - 2026-04-01
- Popup i lista pozycji zamówienia korzystają teraz z aktualnego tytułu produktu z PrestaShop jako głównej nazwy produktu, z zachowaniem osobnej nazwy kombinacji.

## [0.7.59] - 2026-04-01
- Pierwszy wiersz kalkulacji kosztu został uproszczony do opisowych nagłówków pól bez widocznych plakietek i operatorów, przy zachowaniu wyrównania względem rzędu z wartościami.

## [0.7.60] - 2026-04-01
- Dalsze dopracowanie popupu kalkulacji kosztu: przeniesienie `Marży` i `Zysku` bliżej wyniku ceny detalicznej oraz lekkie pogrubienie strzałki `→`.

## [0.7.61] - 2026-04-01
- Dalsze dopracowanie popupu kalkulacji kosztu: pogrubienie etykiet w danych produktu, przeniesienie `Marży` i `Zysku` do wiersza wyniku ceny detalicznej oraz korekta odstępów między nagłówkami, wartościami i separatorem.

## [0.7.62] - 2026-04-01
- Nagłówek popupu kalkulacji kosztu pokazuje teraz nazwę kombinacji w osobnym wierszu pod nazwą produktu.

## [0.7.63] - 2026-04-02
- Dalsze dopracowanie popupu kalkulacji kosztu: jaśniejszy zapis `Zysk netto`, bardziej elastyczne pole wyniku kosztu całkowitego, węższe pole edycji `Narzut`, fallback nazwy kombinacji w nagłówku oraz kolorowy pasek na górnej krawędzi modala.
- Skrypt release zapisuje teraz także lokalną kopię builda i manifestu do katalogu `builds-local/`, co ułatwia ręczną instalację aktualizacji.

## [0.7.64] - 2026-04-02
- Modale `Wykres sprzedaży` i `Rentowność` w zakładce Produkty korzystają teraz z tego samego stylu obramowania co popup `Kalkulacja kosztu`: ten sam promień narożników, kolorowy pasek u góry i przycisk `X`.

## [0.7.65] - 2026-04-02
- W zakładce Produkty dodano nową akcję `Historia ceny` z osobnym oknem modalnym i wykresem historii cen zakupu na podstawie pozycji z zamówień towaru.

## [0.7.66] - 2026-04-02
- Modal `Historia ceny` w zakładce Produkty korzysta teraz z tego samego stylu obramowania co pozostałe okna modalne, pokazuje wyłącznie cenę zakupu netto w PLN i ma polskie tłumaczenia.

## [0.7.67] - 2026-04-02
- Modal `Historia ceny` w zakładce Produkty ma teraz niższy wykres, bardziej kompaktowe kafelki statystyk, listowy układ zamówień i przewijanie zawartości przy dłuższym widoku.

=======
>>>>>>> 0f06d89 (Update builds changelog)
## [0.7.68] - 2026-04-02
- Narzut w modalu `Kalkulacja kosztu` zapisuje się teraz osobno dla każdej kombinacji produktu.
- W panelu produktów zamówienia dodano dokument `Tłumaczenie Faktury` z nazwą produktu PL/EN, HS Code i opisem produktu z danych modułu.

## [0.7.69] - 2026-04-02
- Dokumenty PDF zamówienia i `Tłumaczenie Faktury` pokazują teraz cały adres dostawy z ustawień modułu, bez ucinania dłuższych wpisów.
- W `Tłumaczeniu Faktury` połączono nazwę produktu EN i PL w jedną komórkę z plakietkami językowymi.

## [0.7.70] - 2026-04-02
- Dokument `Tłumaczenie Faktury` ma teraz czytelniejsze plakietki `EN` i `PL`, a `Materiał` został wydzielony do osobnej kolumny.

## [0.7.71] - 2026-04-02
- Poprawiono render plakietek `EN` i `PL` w PDF `Tłumaczenie Faktury`, tak aby były wyraźnie oddzielone od nazwy produktu.

## [0.7.72] - 2026-04-02
- PDF-y zamówienia i `Tłumaczenie Faktury` używają teraz pełniejszego adresu dostawy z ustawień modułu, jeśli w zamówieniu była zapisana krótsza wersja bez EORI.

## [0.7.73] - 2026-04-02
- W PDF `Tłumaczenie Faktury` dopracowano padding i odstępy plakietek `EN` / `PL` oraz dodano `Warunki dostawy` do sekcji `Szczegóły`.

## [0.7.74] - 2026-04-02
- W widoku zamówienia sekcję `Adres dostawy` zmieniono na `Nabywca` i pokazuje ona teraz dokładnie bieżący tekst zapisany w ustawieniach modułu.
- W ustawieniach zamówień etykietę, placeholder i przycisk zmieniono z `Adres dostawy` na `Nabywca`.

## [0.7.75] - 2026-04-02
- W PDF `Tłumaczenie Faktury` przebudowano układ linii `EN` / `PL`, żeby plakietki miały własny, bardziej przewidywalny render bez sztucznej pustej przestrzeni obok.

## [0.7.76] - 2026-04-02
- W PDF `Tłumaczenie Faktury` plakietki `EN` i `PL` są teraz renderowane jako komórki tabeli z twardym stylem inline, co stabilizuje padding i eliminuje pustą przestrzeń obok.

## [0.7.77] - 2026-04-02
- W PDF `Tłumaczenie Faktury` poprawiono render plakietek `EN` / `PL`, aby tło i padding dotyczyły tylko samej plakietki, bez rozciągania na całą komórkę.

## [0.7.78] - 2026-04-02
- W PDF `Tłumaczenie Faktury` dopracowano wygląd plakietek `EN` / `PL`: większy padding wewnętrzny, mniejsze odstępy wokół i delikatne zaokrąglenie.

## [0.7.80] - 2026-04-02
- Uporządkowano wersjonowanie release i opublikowano build spójny z kodem źródłowym.
- W obu dokumentach PDF (`Zamówienie` i `Tłumaczenie faktury`) dodano stopkę: `Wygenerowano w CargoStock Manager v.X.Y.Z`.

## [0.7.81] - 2026-04-02
- W PDF `Tłumaczenie Faktury` usunięto plakietki i zastąpiono je prostym formatem tekstowym `(EN) ...` i `(PL) ...`.

## [0.7.82] - 2026-04-02
- W stawce celnej dopuszczono i utrwalono wartość `0`; interfejs pokazuje teraz `0 %` zamiast `—`.

## [0.7.83] - 2026-04-02
- Pole stawki celnej obsługuje trzy stany: puste (`—`), `0` (`0 %`) oraz wartość dodatnią (`x %`) z poprawnym zapisem i odczytem.

## [0.7.84] - 2026-04-02
- Inline edycja stawki celnej w tabeli produktów akceptuje teraz puste pole bez błędu i poprawnie rozróżnia stany: puste (`—`), `0` (`0 %`) i wartość dodatnią (`x %`).

## [0.7.84] - 2026-04-02
- Inline edycja stawki celnej w tabeli produktów akceptuje teraz puste pole bez błędu i poprawnie rozróżnia stany: puste (`—`), `0` (`0 %`) i wartość dodatnią (`x %`).

## [0.7.85] - 2026-04-02
- W `Zamówienia towaru > Produkty w zamówieniu` dodano nowy przycisk `Kalkulacja zamówienia` (po lewej od `PDF`) z popupem zbiorczej kalkulacji całego zamówienia.
- Popup pokazuje tabelę pozycji z kosztami i sprzedażą (`Ilość`, `Cena zakupu`, `Cena w PLN`, `Cło`, `Transport 1 szt.`, `Koszt całkowity netto | brutto`, `Narzut`, `Cena detaliczna netto | brutto`, `Wartość netto/brutto zakupu`, `Zysk netto`, `Marża`) oraz podsumowanie na dole.
- W tabeli działa szybka edycja `Narzutu` per pozycja (zapis do bazy dla produktu/kombinacji) i natychmiastowe przeliczenie wartości w popupie.

## [0.7.86] - 2026-04-02
- W tabeli popupu `Kalkulacja zamówienia` uproszczono układ kolumn: usunięto `Cena zakupu`, `Cena w PLN`, `Cło` i `Transport 1 szt.`.
- Zmieniono prezentację wartości zakupu na jedną kolumnę `Wartość zakupu` z zapisem `netto | brutto`.
- Uporządkowano kolejność kolumn zgodnie z aktualnym układem kalkulacji.

## [0.7.87] - 2026-04-02
- W popupie `Kalkulacja zamówienia` dopracowano układ tabeli: etykiety `Koszt całkowity` i `Cena detaliczna` przeniesiono do układu 2-liniowego (`netto | brutto`), dodano kolumnę `Wartość detaliczna netto | brutto`, a nazwa kombinacji jest zawsze w nowym wierszu pod nazwą produktu.
- Usunięto dolny blok oddzielnych etykiet podsumowania; sumowanie pozostaje wyłącznie w tabeli (`wiersz Suma`) dla wartości detalicznych i zakupu.

## [0.7.88] - 2026-04-02
- Ujednolicono formatowanie liczb w popupach kalkulacji: separator tysięcy to zwykła spacja, a separator dziesiętny to przecinek.

## [0.7.89] - 2026-04-02
- W popupie `Kalkulacja zamówienia` poprawiono czytelność tabeli: wyśrodkowano nagłówki kolumn i dopracowano format wartości liczbowych (`6 633,47` zamiast `6633,47`).
- Uzupełniono wiersz `Suma` o podsumowanie kolumny `Zysk netto`.

## [0.7.90] - 2026-04-02
- W popupie `Kalkulacja zamówienia` dodano kolumnę `Zdjęcie` (po `LP`).
- W kolumnie `Produkt` nazwa kombinacji jest teraz zawsze wyświetlana w nowym wierszu pod nazwą produktu (z fallbackiem do danych wiersza tabeli).
- Uporządkowano kolejność kolumn: `Wartość zakupu netto | brutto` przeniesiono zaraz za `Koszt całkowity netto | brutto`.

## [0.7.90] - 2026-04-02
- W popupie `Kalkulacja zamówienia` dodano kolumnę `Zdjęcie` (po `LP`).
- W kolumnie `Produkt` nazwa kombinacji jest teraz zawsze wyświetlana w nowym wierszu pod nazwą produktu (z fallbackiem do danych wiersza tabeli).
- Uporządkowano kolejność kolumn: `Wartość zakupu netto | brutto` przeniesiono zaraz za `Koszt całkowity netto | brutto`.

## [0.7.91] - 2026-04-04
- Naprawiono losowe pomijanie stylów CSS w zakładce `Produkty` w nowym layoucie administracyjnym.
- Zmieniono ikonę przycisku skanera na `qr_code_2` (`material-icons-outlined`) dla lepszej czytelności funkcji skanowania kodów.

## [0.7.92] - 2026-04-04
- Poprawiono ikonę przycisku skanera (`qr_code_2`), aby renderowała się poprawnie zarówno w PrestaShop 8.2, jak i 9.

## [0.7.93] - 2026-04-04
- Naprawiono błąd w `Ustawieniach`: zapis pola `Nabywca` nie nadpisuje już konfiguracji statusów zamówień i ich kolorów.
- Przycisk skanera ma teraz bazowy styl spójny z przyciskiem `Filtry`, a po aktywacji przechodzi w niebieski stan zgodny z kolorystyką BO.
- Powiększono ikonę `qr_code_2` w przycisku skanera (2x) bez zmiany wysokości przycisku oraz dodano ikonę do przycisku `Filtry`.

## [0.7.94] - 2026-04-04
- Dopracowano przycisk skanera: dodano etykietę tekstową `Skaner`.
- Poprawiono styl ikony `qr_code_2`, aby wymuszone powiększenie było widoczne (bez zmiany wysokości przycisku).

## [0.7.95] - 2026-04-04
- Dopracowano proporcje przycisku `Skaner` względem `Filtry`: zmniejszono ikonę `qr_code_2` i wyrównano szerokość oraz padding przycisku.

## [0.7.79] - 2026-04-02
- W PDF `Tłumaczenie Faktury` naprawiono renderowanie plakietek `EN` / `PL`: styl tła i paddingu przeniesiony na `<td>` zamiast `<span display:inline-block>`, co jest wymagane przez mPDF.

## [0.7.79] - 2026-04-02
- W PDF `Tłumaczenie Faktury` naprawiono renderowanie plakietek `EN` / `PL`: styl tła i paddingu przeniesiony na `<td>` zamiast `<span display:inline-block>`, co jest wymagane przez mPDF.

## [0.7.79] - 2026-04-02
- W PDF `Tłumaczenie Faktury` naprawiono renderowanie plakietek `EN` / `PL`: styl tła i paddingu przeniesiony na `<td>` zamiast `<span display:inline-block>`, co jest wymagane przez mPDF.

## [0.7.79] - 2026-04-02
- W PDF `Tłumaczenie Faktury` naprawiono renderowanie plakietek `EN` / `PL`: styl tła i paddingu przeniesiony na `<td>` zamiast `<span display:inline-block>`, co jest wymagane przez mPDF.

## [0.7.79] - 2026-04-02
- W PDF `Tłumaczenie Faktury` naprawiono renderowanie plakietek `EN` / `PL`: styl tła i paddingu przeniesiony na `<td>` zamiast `<span display:inline-block>`, co jest wymagane przez mPDF.

## [0.7.99] - 2026-04-07
- W zamówieniach towaru upload plików obsługuje teraz multiupload: można przeciągnąć lub wybrać kilka plików naraz, a formularz pokazuje osobne pola opisu i rodzaju dokumentu dla każdego pliku.

## [0.7.100] - 2026-04-07
- Naprawiono układ sekcji notatek w zamówieniach towaru po wdrożeniu multiuploadu plików: przycisk `Dodaj notatkę` i kafelki notatek wracają do właściwego miejsca pod sekcją dokumentów.

## [0.7.101] - 2026-04-08
- W sekcji `Dokumenty` na widoku zamówienia dodano przycisk `Wyślij do księgowania` z popupem wyboru plików i adresem e-mail do księgowania konfigurowanym w ustawieniach modułu.

## [0.7.102] - 2026-04-09
- Dodano wybór kanału aktualizacji `Public` / `Beta` w ustawieniach modułu oraz obsługę osobnych manifestów release.
- Ujednolicono modale w zamówieniach: blur tła, zamykanie przez `X`, `ESC` i klik w tło oraz kolorowy pasek na górnej krawędzi.

## [0.7.103] - 2026-04-09
- Poprawiono blur backdropu w bootstrapowym modalu `Edytuj dane produktu`, także dla wariantu klas `.modal-backdrop.in`.

## [0.7.104] - 2026-04-09
- Na przycisku aktualizacji dodano oznaczenie `Beta` przy wersji, gdy dostępna aktualizacja pochodzi z kanału beta.

## [0.7.105] - 2026-04-09
- Wzmocniono blur tła w bootstrapowym modalu `Edytuj dane produktu`, aby wyglądał tak samo jak w modalu `Kalkulacja kosztu`.

## [0.7.106] - 2026-04-09
- Ujednolicono animacje i tło modalów w module do stylu `Kalkulacja kosztu`: wspólny blur, górny pasek i wejście `fade + translateY`.

## [0.7.107] - 2026-04-10
- Poprawiono pozycjonowanie modali formularzy po ujednoliceniu animacji: okna są znów centrowane pionowo i nie zjeżdżają w dół.

## [0.7.108] - 2026-04-10
- Doprecyzowano centrowanie modalów formularzy po migracji animacji: dialogi korzystają z `modal-dialog-centered` i nie osiadają zbyt nisko.

## [0.7.109] - 2026-04-10
- Formularzowe modale w zamówieniach towaru (`Dodaj produkt`, `Edytuj dane produktu`, `Dodaj notatkę`, `Wyślij do księgowania`) korzystają teraz z tego samego customowego mechanizmu co `Kalkulacja kosztu`.
- Ujednolicono blur, animację, obsługę klawisza `ESC`, kliknięcia w tło i zamykania przez `X` we wszystkich tych modalach.
- Usunięto bootstrapowe sterowanie pozycją formularzowych modalów, co naprawia zbyt niskie położenie okna `Edytuj dane produktu`.

## [0.7.110] - 2026-04-10
- W modalu `Wyślij do księgowania` lista plików została przebudowana do układu tabeli spójnego z sekcją `Dokumenty` na widoku zamówienia.
- Pierwsza kolumna używa zwykłych checkboxów w domyślnym stylu Back Office zamiast własnego układu listy.

## [0.7.111] - 2026-04-10
- Checkboxy w pierwszej kolumnie tabeli modala `Wyślij do księgowania` korzystają teraz z klas `form-check` i `form-check-input`, aby łapały standardowy wygląd Back Office.

## [0.7.112] - 2026-04-10
- Checkboxy w modalu `Wyślij do księgowania` dostały lokalny styl wizualnie zgodny z turkusowymi checkboxami Back Office, niezależny od globalnych styli formularzy.

## [0.7.113] - 2026-04-10
- W modalu `Wyślij do księgowania` checkboxy wróciły do natywnego renderowania przeglądarki z `form-check-input`, a kolor zaznaczenia opiera się o zmienne Back Office (`--bs-primary` / `--primary`), co poprawia zgodność z motywami PrestaShop 8 i 9.

## [0.7.114] - 2026-04-10
- Poprawiono zamykanie modala `Połącz z produktem` dla niepowiązanych pozycji w zamówieniu: po udanym relinku stan requestu jest zapamiętywany lokalnie, a modal dostaje pewny reset i zamknięcie bez losowego „przywieszania”.

## [0.7.115] - 2026-04-10
- W `Produkty > Historia ceny` ceny zakupu są teraz wyświetlane z groszami w statystykach, liście zakupów, tooltipach i osi wykresu.

## [0.7.116] - 2026-04-10
- Modal `Produkty > Edytuj dane modułowe` dostał spójny styl z pozostałymi modalami modułu: biały dialog, wspólny cień, pasek górny, przycisk zamknięcia i header.
- Zachowano osobny pełnoekranowy wygląd trybu baterii skanera.

## [0.7.117] - 2026-04-10
- W modalu `Dane modułowe produktu` pola nad opisem zostały przełożone do dwóch rzędów na desktopie: pierwszy rząd zawiera model, wagę i ilość w kartonie, a drugi objętość, materiał, stawkę celną i HS Code.

## [0.7.118] - 2026-04-10
- Do modala `Dane modułowe produktu` dodano miniaturkę produktu w nagłówku z fallbackiem dla produktów bez zdjęcia.
- W tym samym modalu `HS Code` został dopasowany do drugiego wiersza obok `Stawka celna`.

## [0.7.119] - 2026-04-10
- W modalu `Dane modułowe produktu` nagłówek pokazuje nazwę produktu, a pod spodem pełną nazwę kombinacji.
- W modalu `Kalkulacja kosztu` kombinacja produktu korzysta z pełnej etykiety wariantu, np. `Zapach: lawendowy`.

## [0.7.120] - 2026-04-10
- W `Ustawienia > Lista ukrytych produktów` usunięto kolumnę `Wyświetlany`.
- Pod nazwą produktu na liście ukrytych produktów dodano nazwę kombinacji, np. `Zapach: lawendowy`.

## [0.7.121] - 2026-04-10
- Ujednolicono nagłówek modala `Produkty > Edytuj dane modułowe` ze stylem modalów `Wykres sprzedaży`, `Historia ceny` i `Rentowność`: miniatura, nazwa produktu i kombinacja mają ten sam układ.
- W modalu edycji danych modułowych ukryto EAN w nagłówku otwieranym z przycisku edycji produktu.

## [0.7.122] - 2026-04-10
- Po instalacji aktualizacji moduł czyści cache Smarty, XML, Media i wewnętrzny cache PrestaShop, żeby zmiany w szablonach `.tpl` były widoczne od razu po aktualizacji.

## [0.7.123] - 2026-04-10
- Nagłówki modalów produktowych `Edytuj dane modułowe`, `Wykres sprzedaży`, `Historia ceny` i `Rentowność` dopasowano do stylu modala `Kalkulacja kosztu` z zamówień: mniejsza miniatura, prosty border, tytuł i kombinacja w tym samym układzie.

## [0.7.124] - 2026-04-10
- Zawartość popupa `Produkty > Edytuj dane modułowe` przebudowano na układ i style z modala `Kalkulacja kosztu`: sekcje, grid danych produktu, wiersze etykieta/wartość i uporządkowany opis.

## [0.7.125] - 2026-04-11
- Zakładka Produkty, Akcje: popup „Wykres sprzedaży".
- Poprawka: modal „Edytuj dane modułowe" nie otwierał się po kliknięciu (błąd zakresu funkcji formatowania waluty między blokami IIFE).

## [0.7.126] - 2026-04-10
- Zawartość popupów „Wykres sprzedaży", „Historia ceny" i „Rentowność" przepisana na układ i style `csmgr-cost-*` zgodne z „Kalkulacja kosztu" z zamówień: sekcje z tytułami, grid wierszy etykieta/wartość, stany kolorystyczne dla wartości dodatnich/ujemnych.

## [0.7.127] - 2026-04-11
- Popup „Wykres sprzedaży": statystyki 3 lat pokazane w 3 kolumnach obok siebie; rok jako plakietka w kolorze linii na wykresie (złoty / błękitny / zielony).

## [0.7.128] - 2026-04-11
- Popup „Wykres sprzedaży": każdy rok w osobnym panelu z zaokrąglonymi narożnikami i kolorowym paskiem u góry; szerokość okna powiększona do 1520 px (jak „Kalkulacja kosztu" w zamówieniach).

## [0.7.128] - 2026-04-11
- Popup „Wykres sprzedaży": każdy rok w osobnym panelu z zaokrąglonymi narożnikami i kolorowym paskiem u góry; szerokość okna powiększona do 1520 px (jak „Kalkulacja kosztu" w zamówieniach).

## [0.7.129] - 2026-04-11
- Popup „Wykres sprzedaży": wartość sprzedaży netto/brutto, szacowany zysk netto/brutto oraz wartość miesięczna netto/brutto — każda para w jednym wierszu.

## [0.7.130] - 2026-04-11
- Popup „Wykres sprzedaży": szacowany zysk pokazuje Sklep i Marketplace osobno, każde z wartością netto i brutto w jednym wierszu.

## [0.7.131] - 2026-04-11
- Popup „Wykres sprzedaży": wiersz MIN/MAX/ŚRED. pokazuje trzy wartości inline z etykietami zamiast w formacie x / y / z.

## [0.7.132] - 2026-04-11
- Popup „Wykres sprzedaży": wartości w kolumnach rocznych pogrubione.

