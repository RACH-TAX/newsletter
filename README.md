# newsletter

Archiwum newslettera RACH-TAX dla klientów: https://newsletter.rach-tax.pl/

Repozytorium zawiera wyłącznie opublikowaną stronę. Każdy push na `main` publikuje ją przez GitHub Actions (`.github/workflows/deploy.yml`), dlatego trafiają tu tylko wydania zaakceptowane do publikacji.

- `index.html`: archiwum wydań, od najnowszego (generowane).
- `RRRR-MM/index.html`: strona wydania (generowana z tych samych danych co wersja e-mail).
- `assets/css/main.css`: arkusz generowany z tokenów systemu projektowego RACH-TAX Newsroom. Nie edytuj ręcznie.
- `assets/images/`: logo z paczki marki RACH-TAX, bez modyfikacji.

Wszystkie strony mają `noindex, nofollow`: są publiczne dla osób z linkiem, ale nie trafiają do wyszukiwarek. Nie dodawaj `robots.txt` blokującego indeksowanie, bo wyszukiwarka nie zobaczyłaby wtedy znacznika `noindex`.
