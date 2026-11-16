# Emilia

**Projekt: Emilia Wąs** — interaktywna pracownia przyrodnicza **EkoOdkrywcy 1–3** (edukacja wczesnoszkolna, klasy 1–3).

Strona działa bez serwera: każda podstrona to samodzielny plik HTML z React 18 i Tailwind CSS ładowanymi z CDN.

## Adres

https://pasjonatprogramowania.github.io/Emilia/

## Moduły

| Plik | Zadanie |
| --- | --- |
| `index.html` | pulpit z listą zadań i licznikiem postępów |
| `zadanie-1.html` | „Czego brakuje w plecaku?” — pakowanie plecaka opiekuna |
| `zadanie-2.html` | „Budujemy Leśny Korytarz Życia” — ekodukty, tunele, liny, ekrany |
| `zadanie-3.html` | „Zbuduj Idealny Ekosystem” — sandbox 3 slotów (synergie i konflikty) |
| `zadanie-4.html` | „Zwierzęce Kształty i Cienie” — latarka na canvasie |
| `zadanie-5.html` | „Co je ten zwierzak?” — koło fortuny i zdrowe menu |
| `zadanie-6.html` | „Klucz Dychotomiczny Kręgowców” — oznaczanie gromad |
| `zadanie-7.html` | „Zwierzęta Gospodarcze i Surowce” — rodzina, miejsce życia, produkty |
| `memory.html` | „Memory: Egzotyczne Zwierzęta” — zdjęcie ↔ nazwa gatunku |
| `quiz.html` | quiz podsumowujący, odblokowany po ukończeniu wszystkich zadań |
| `markery.html` | karty markerów AR do druku (materiał archiwalny) |

Postęp zapisywany jest w `localStorage` pod kluczem `eko_odkrywcy_progress`.

## Uruchomienie lokalnie

Otwórz `index.html` w przeglądarce albo wystaw katalog jako stronę statyczną:

```bash
npx serve .
```

## Autor

**Emilia Wąs** — projekt i materiały dydaktyczne.

Warstwa techniczna: React 18 (UMD) + Babel Standalone + Tailwind CSS (CDN), zdjęcia i modele 3D z Wikimedia Commons i Sketchfab (autorzy wymienieni na stronach).
