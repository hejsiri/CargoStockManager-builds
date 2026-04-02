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

