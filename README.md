# email-gender-detector

Narzędzie do wykrywania płci i uzupełniania imion na podstawie adresów email — oparte o oficjalne listy imion i nazwisk z rejestru PESEL (Ministerstwo Cyfryzacji, 2026).

**Demo:** https://[twoja-nazwa].github.io/email-gender-detector

---

## Co robi

- Wykrywa płeć (`men` / `female`) dla ~75% rekordów
- Uzupełnia brakujące imiona z adresu email
- Naprawia błędy w imionach (brak polskich znaków, wielkie litery, literówki)
- Działa **lokalnie w przeglądarce** — żadne dane nie opuszczają Twojego komputera
- Listy PESEL pobierane automatycznie z api.dane.gov.pl

## Jak używać

1. Wejdź na stronę
2. Wgraj plik CSV ze swoją bazą emailową
3. Zmapuj kolumny (email + opcjonalnie imię)
4. Kliknij "Uruchom analizę"
5. Pobierz wynik

## Format wejściowy

Plik CSV z dowolną nazwą, kodowanie UTF-8. Wymagana kolumna z adresami email. Kolumna z imieniem jest opcjonalna — jeśli jej nie ma, skrypt spróbuje wyciągnąć imię z adresu email.

## Technologie

- Czysty HTML + JavaScript (zero frameworków, zero serwera)
- Dane: [dane.gov.pl](https://dane.gov.pl) — Ministerstwo Cyfryzacji

## Licencja

MIT
