# nadgranica.pl — aplikacja na Androida (wydania)

To repozytorium zawiera **wyłącznie pliki wydań** aplikacji mobilnej [nadgranica.pl](https://www.nadgranica.pl) (APK i sumy SHA-256). Nie ma tu kodu źródłowego.

**Status: wersja testowa.** Aplikacja pojawi się w Google Play, gdy zakończą się testy.

## Co to jest

Nieoficjalny monitor zagrożeń nad wschodnią granicą, w wersji na telefon: poziom w wybranym województwie (lubelskie, podkarpackie, podlaskie), mapa z alarmami i obiektami z serwisu NEPTUN oraz opcjonalne powiadomienia. Bez kont, reklam i analityki.

**Nieoficjalne dane — nie zastępują Alertu RCB ani oficjalnych komunikatów.** To projekt osoby prywatnej, niezwiązany z Rządowym Centrum Bezpieczeństwa ani żadną instytucją państwa.

## Pobieranie i instalacja

1. Pobierz najnowszy plik `nadgranica.pl-<wersja>-arm64-v8a.apk` z [najnowszego wydania](https://github.com/marcinzygmunt-pl/nadgranica-android/releases/latest). Plik jest dla telefonów z procesorem arm64 (większość nowszych telefonów).
2. Zezwól przeglądarce albo menedżerowi plików na instalowanie aplikacji z nieznanych źródeł (Android pokaże to ustawienie przy pierwszej próbie).
3. Jeśli Google Play Protect zapyta o aplikację spoza sklepu, wybierz „Zainstaluj mimo to”. Na telefonach Samsung funkcja Auto Blocker blokuje takie instalacje, dopóki jej nie wyłączysz.
4. Aplikacja z pliku APK **nie aktualizuje się automatycznie**: gdy pojawi się nowa wersja, pobierz nowy plik i zainstaluj go ręcznie.

Wymagany Android 7.0 (API 24) lub nowszy. Szczegółowa instrukcja i opis testów: <https://www.nadgranica.pl/aplikacja.html>.

## Sprawdzenie pliku

Suma SHA-256 każdego pliku jest w opisie wydania i w pliku `.sha256` obok APK. Podpis aplikacji: certyfikat o skrócie SHA-256 podanym w opisie wydania.

## Prywatność i kontakt

[Polityka prywatności](https://www.nadgranica.pl/polityka-prywatnosci.html). Pytania i zgłoszenia błędów: hello@marcinzygmunt.pl. Projekt tworzy Marcin Zygmunt, osoba prywatna.

Wszelkie prawa zastrzeżone. Android i Google Play są znakami towarowymi Google LLC.
