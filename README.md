#  Schronisko – aplikacja do adopcji zwierząt

##  Opis projektu

Projekt przedstawia aplikację internetową wspierającą działalność schroniska dla zwierząt. Jej głównym celem jest ułatwienie procesu adopcji, prezentowanie zwierząt oczekujących na nowy dom oraz usprawnienie organizacji pracy schroniska.

Aplikacja umożliwi użytkownikom przeglądanie katalogu dostępnych zwierząt, zapoznawanie się z ich opisami, zdjęciami i historią, a także wypełnianie formularzy adopcyjnych.

Dodatkowo system będzie posiadał funkcje przeznaczone dla wolontariuszy, takie jak przeglądanie dostępnych terminów spacerów i zapisywanie się na wybrane terminy.

##  Funkcjonalności aplikacji

- **Katalog zwierząt** – przeglądanie zwierząt dostępnych do adopcji wraz ze zdjęciami, opisami i podstawowymi informacjami.
- **Karta zwierzęcia** – szczegółowe informacje o zwierzęciu, jego stanie zdrowia oraz historii pobytu w schronisku.
- **Formularz adopcyjny** – wieloetapowy formularz umożliwiający złożenie wniosku o adopcję wybranego zwierzęcia.
- **Panel wolontariusza** – możliwość przeglądania dostępnych aktywności i zarządzania swoimi zapisami.
- **Zapisy na spacery** – wybieranie dostępnych terminów spacerów z psami i zapisywanie się na nie.
- **Galeria zdjęć** – prezentowanie zdjęć zwierząt w formie interaktywnej galerii.
- **Walidacja formularzy** – sprawdzanie poprawności danych wprowadzanych przez użytkowników.

##  Wykorzystane technologie

### Frontend
- **React** – tworzenie interfejsu użytkownika, obsługa katalogu zwierząt, formularzy adopcyjnych oraz panelu wolontariusza.
- **HTML5** – tworzenie struktury stron internetowych.
- **CSS3** – stylowanie i projektowanie wyglądu aplikacji.
- **TypeScript** – implementacja logiki aplikacji.
- **jQuery** – wykorzystanie efektów wizualnych i animacji w galerii zdjęć.

### Baza danych
- **PostgreSQL** – relacyjna baza danych przechowująca informacje o zwierzętach, użytkownikach, wolontariuszach, wnioskach adopcyjnych, terminach spacerów oraz historii zdrowia zwierząt.

##  Struktura bazy danych PostgreSQL

Baza danych będzie przechowywać między innymi:

- **Zwierzęta** – nazwa, gatunek, rasa, wiek, opis i status adopcji.
- **Użytkownicy** – dane osób korzystających z aplikacji.
- **Wnioski adopcyjne** – dane dotyczące zgłoszeń i ich statusów.
- **Wolontariusze** – informacje o wolontariuszach.
- **Spacery** – dostępne terminy, zapisy i przypisane zwierzęta.
- **Historia zdrowia** – informacje o stanie zdrowia, szczepieniach i leczeniu zwierząt.
- **Galerie** – zdjęcia przypisane do poszczególnych zwierząt.

## Struktura plików

schronisko/

  public/
  
    images/             # Zdjęcia zwierząt
    
  src/
  
    components/         # Wspólne elementy strony
    
    pages/              # Strony aplikacji
    assets/             # Obrazy i style
    App.tsx             # Główny komponent
    main.tsx            # Uruchomienie aplikacji
  database/
      schema.sql          # Struktura bazy danych
  package.json            # Zależności projektu
  README.md               # Opis projektu

Krótki opis folderów:
- public – zdjęcia zwierząt.
- components – przyciski, formularze i menu.
- pages – poszczególne strony aplikacji.
- assets – grafiki i pliki CSS.
- services – komunikacja z bazą danych pobieranie informacji.
- database – pliki związane z bazą PostgreSQL.
  
##  Ciekawostki techniczne

- Wieloetapowy formularz adopcyjny w Angularze z walidacją danych.
- Interaktywna galeria zdjęć z efektami wykorzystującymi jQuery.
- Relacyjna baza danych PostgreSQL z powiązaniami pomiędzy tabelami.
- Możliwość filtrowania i wyszukiwania zwierząt według wybranych kategorii.

##  Cel projektu

Celem projektu jest stworzenie funkcjonalnej i przejrzystej aplikacji, która ułatwi znalezienie domu dla zwierząt, usprawni proces adopcyjny oraz pomoże w organizacji pracy schroniska i wolontariuszy.
