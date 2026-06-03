# email-gender-detector

Narzędzie do wykrywania płci i uzupełniania imion na podstawie adresów email — oparte o oficjalne listy imion i nazwisk z rejestru PESEL.

**Demo:** https://just-lukasz.github.io/email-gender-firstname-detector/

---

## Co robi

- Wykrywa płeć (`men` / `female`)
- Uzupełnia brakujące imiona z adresu email
- Naprawia błędy w imionach (brak polskich znaków, brak wielkiej litery, tylko wielkie litery, literówki)
- Działa **lokalnie w przeglądarce** — żadne dane nie opuszczają Twojego komputera

## Jak używać

1. Wejdź na stronę
2. Wgraj plik CSV ze swoją bazą emailową
3. Zmapuj kolumny (email + opcjonalnie imię - dla lepszego kontekstu)
4. Kliknij "Uruchom analizę"
5. Pobierz wynik

## Format wejściowy

Plik CSV z dowolną nazwą, kodowanie UTF-8. Wymagana kolumna z adresami email. Kolumna z imieniem jest opcjonalna — jest ona dodatkową informacją dla narzędzia. Jeśli jej nie ma, nic się nie dzieje - narzędzie wyciągnie imię z adresu email.

## Technologie

- Czysty HTML + JavaScript (zero frameworków, zero serwera)

## Licencja

MIT
