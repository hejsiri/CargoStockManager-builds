## [0.6.12] - 2026-03-31
- Naprawa kompatybilności z nowszym schematem `ps_access` w PrestaShop podczas synchronizacji uprawnień tabów BO.

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
- Poprawione ścieżki ładowania szablonów modułu po hotfixie kompatybilności, aby konfiguracja nie szukała widoków w katalogu `cargostockmanager`.
- Legacy konfiguracja modułu i nowoczesne widoki Twig odwołują się teraz do właściwego katalogu technicznego `prestashopinventory`.

## [0.6.1] - 2026-03-31
- Hotfix kompatybilności aktualizacji: paczka znów używa technicznej nazwy modułu `prestashopinventory`, aby aktualizacja z BO nie kończyła się błędem 500.
- Zachowany branding `CargoStock Manager` w interfejsie oraz migracja danych do nowych tabel `cargostockmanager_*`.
- Poprawione ścieżki uploadów plików zamówień, aby działały poprawnie po aktualizacji kompatybilnej.

## [0.6.0] - 2026-03-31
- Pełny technical rename modułu z `prestashopinventory` do `cargostockmanager` w plikach, klasach, namespace'ach, trasach, tłumaczeniach i identyfikatorach pomocniczych.
- Dodana automatyczna migracja danych legacy: konfiguracji, rekordów modułu i tabów BO, tabel `prestashopinventory_*`, nazw wybranych kolumn oraz ścieżek plików zapisanych w bazie.
- Zachowana zgodność z istniejącymi licencjami wystawionymi jeszcze dla legacy nazwy modułu.

# Changelog

