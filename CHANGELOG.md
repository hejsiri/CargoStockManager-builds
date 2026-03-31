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

