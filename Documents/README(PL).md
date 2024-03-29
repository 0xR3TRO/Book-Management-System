## Opis projektu

### Cel:

Projekt "System zarządzania książkami" ma na celu dostarczenie użytkownikom narzędzia do monitorowania postępu czytania książek, przechowywania notatek oraz plików związanych z książkami oraz wprowadzania danych na temat książek i ich autorów. Aplikacja umożliwia efektywne zarządzanie czytanymi pozycjami oraz ułatwia organizację informacji na temat książek i ich twórców.

### Opis funkcji:

- **Monitorowanie postępu czytania:** Użytkownicy mają możliwość śledzenia postępu czytania poszczególnych książek, określając aktualnie przeczytane strony lub rozdziały.
- **Przechowywanie notatek i plików:** Możliwość dodawania notatek oraz przesyłania plików (np. zdjęć, dokumentów) związanych z czytanymi książkami, co ułatwia organizację informacji i zapamiętywanie ważnych treści.
- **Wprowadzanie danych na temat książki:** Użytkownicy mogą dodawać informacje na temat przeczytanych książek, takie jak tytuł, autor, gatunek, wydawnictwo itp.
- **Wprowadzanie danych na temat autorów:** Możliwość wprowadzania danych na temat autorów książek, takich jak imię, nazwisko, biografia, lista publikacji itp.

## Analiza wymagań:

### Wymagania funkcjonalne:

- **Monitorowanie postępu czytania:** Użytkownik może określić aktualnie przeczytane strony lub rozdziały książki.
- **Przechowywanie notatek i plików:** Aplikacja umożliwia użytkownikom dodawanie i przeglądanie notatek oraz plików związanych z czytanymi książkami.
- **Wprowadzanie danych na temat książki:** Użytkownik może wprowadzać informacje na temat książek, takie jak tytuł, autor, gatunek, wydawnictwo itp.
- **Wprowadzanie danych na temat autorów:** Możliwość dodawania danych na temat autorów książek, takich jak imię, nazwisko, biografia, lista publikacji itp.

### Wymagania niefunkcjonalne:

- **Poufność danych:** Zapewnienie bezpieczeństwa danych użytkowników, szczególnie w przypadku przechowywania notatek i plików.
- **Responsywność interfejsu:** Zapewnienie płynnego działania aplikacji na różnych urządzeniach i ekranach.
- **Intuicyjny interfejs użytkownika:** Stworzenie przejrzystego i łatwego w obsłudze interfejsu, który umożliwi użytkownikom szybkie znalezienie potrzebnych funkcji.

## Projekt interfejsu:

### Szkice/wizualizacje interfejsu:

- _Strona główna:_ Panel sterowania z opcjami monitorowania postępu czytania, dodawania notatek i plików, wprowadzania danych na temat książek i autorów.
- _Formularz dodawania książki:_ Miejsce do wprowadzenia danych na temat nowej książki.
- _Formularz dodawania autora:_ Miejsce do dodania danych na temat nowego autora.
- _Strona szczegółów książki:_ Przeglądanie szczegółowych informacji na temat konkretnej książki, w tym postęp czytania, notatki, pliki, dane autora.

### Mapa strony:

- _Strona główna_
  - Panel sterowania
  - Opcje monitorowania postępu czytania
  - Dodawanie notatek i plików
  - Dodawanie danych na temat książek i autorów
- _Formularz dodawania książki_
  - Pola do wprowadzenia danych książki
  - Przycisk "Dodaj książkę"
- _Formularz dodawania autora_
  - Pola do wprowadzenia danych autora
  - Przycisk "Dodaj autora"
- _Strona szczegółów książki_
  - Informacje o książce (tytuł, autor, gatunek itp.)
  - Notatki i przesłane pliki
  - Informacje o autorze

## Architektura systemu:

### Opis struktury danych:

Aplikacja przechowuje dane związane z czytanymi książkami i ich autorami, w tym:

- **Książki:** Zawiera informacje o tytule, autorze, gatunku, wydawnictwie, postępie czytania, notatkach i przesłanych plikach.
- **Autorzy:** Przechowuje dane o autorach, takie jak imię, nazwisko, biografia, lista publikacji.

### Diagramy architektury:

Architektura oparta jest na strukturze opakowanej, gdzie:

- **Model:** Odpowiada za logikę zarządzania danymi książek i autorów.
- **Widok (View):** Prezentuje interfejs użytkownika.
- **Kontroler (Controller):** Zarządza komunikacją między modelem a widokiem.

## Implementacja:

### Opis technologii:

- **Frontend:** HTML, CSS, JavaScript (React.js).
- **Backend:** Flask (Python), SQLite (baza danych).
- **Autoryzacja i uwierzytelnianie:** JWT (JSON Web Tokens) do zapewnienia bezpieczeństwa danych użytkowników.

### Struktura kodu:

- _Katalogi/pliki_: Oddzielne pliki dla logiki zarządzania danymi, interfejsu, kontroli użytkownika.
- _Style pisania kodu_: Zastosowanie modularności, czytelności i komentarzy w kodzie.

## Testowanie:

### Plan testów:

- **Testy jednostkowe:** Sprawdzenie poprawności funkcji zarządzania danymi książek i autor

ów.

- **Testy integracyjne:** Upewnienie się, że komponenty współpracują ze sobą poprawnie.
- **Testy interfejsu użytkownika:** Sprawdzenie interakcji z użytkownikiem na różnych urządzeniach.
- **Testy bezpieczeństwa:** Ocena zabezpieczeń aplikacji, szczególnie w zakresie przechowywania danych użytkowników.

### Procedury testowania:

- Opracowanie zestawu przypadków testowych dla każdej funkcji aplikacji.
- Ustalenie procedur raportowania i naprawiania znalezionych błędów.

## Wdrożenie i konserwacja:

### Plan wdrożenia:

- **Etapy wdrażania:** Testowanie, poprawki, publikacja na platformach dostępnych dla użytkowników.
- **Terminy:** Określenie dat planowanych etapów.

### Procedury konserwacji:

- **Wsparcie techniczne:** Ustanowienie kanałów komunikacji z użytkownikami w celu zgłaszania problemów.
- **Aktualizacje:** Planowanie regularnych aktualizacji w zależności od potrzeb i feedbacku użytkowników.

## Harmonogram:

### Plan projektu:

- **Etapy realizacji:** Podział prac na konkretne zadania (np. implementacja monitorowania postępu czytania, dodawania notatek i plików, wprowadzania danych na temat książek i autorów).
- **Terminy:** Określenie czasu potrzebnego na każdy etap.

## Kosztorys:

### Szacunkowe koszty:

- **Rozwój aplikacji:** Wg godzin pracy lub zespołu programistów.
- **Koszty utrzymania:** Serwery, ewentualne opłaty za usługi zewnętrzne, wsparcie techniczne.

---

[English](/README.md)
