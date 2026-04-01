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
## [0.7.45] - 2026-04-01
- Stabilizacja ładowania stylów w zakładce Produkty w nowoczesnym layoucie przez przeniesienie legacy CSS do sekcji `stylesheets`.
- Odświeżanie miniaturek produktów na liście pozycji zamówienia z aktualnego obrazka kombinacji albo produktu.
- Dodanie powiększenia zdjęcia produktu po najechaniu w liście pozycji zamówienia.
- Dodanie automatycznego czyszczenia starych ZIP-ów w skrypcie release, z domyślnym limitem 5 najnowszych buildów.

## [0.7.46] - 2026-04-01
- Uporządkowanie popupu kalkulacji kosztu w produktach zamówienia: listy z liniami między wierszami, szybkiej edycji narzutu i czytelniejszego nagłówka produktu oraz kombinacji.
- Zmiana liczenia kosztu transportu 1 szt. w kalkulacji kosztu na udział według wagi produktu względem łącznej wagi zamówienia.

