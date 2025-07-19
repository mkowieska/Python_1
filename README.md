# Task Manager
Graficzny menedżer zadań napisany w Pythonie z użyciem bibliotek: 
- tkinter, 
- customtkinter,
- Pillow (PIL). 

Aplikacja umożliwia dodawanie zadań z priorytetem, filtrowanie, sortowanie, usuwanie, a także zapis i odczyt listy zadań z pliku tekstowego.

**Projekt na zaliczenie z przedmiotu Python** na Zachodniopomorskim Uniwersytecie Technologicznym w roku akademickim 2023/2024.

## Autor
Martyna Kowieska

# Funkcjonalności
- Prosty interfejs graficzny z przyciskami i rozwijanymi menu.
- Dodawanie zadania z wybranym priorytetem (Low, Medium, High).
- Automatyczne nadawanie znacznika czasu (dd-mm-YYYY HH:MM:SS).
- Wyświetlanie listy zadań w oknie tekstowym (ponumerowane).
- Filtrowanie zadań po priorytecie (All / Low / Medium / High).
- Sortowanie zadań według czasu dodania lub priorytetu.
- Usuwanie zadania po numerze z listy.
- Zapis wszystkich zadań do pliku tekstowego.
- Odczyt zadań z pliku i odtworzenie listy.

## Instalacja i uruchomienie

1. Sklonuj repozytorium:
   ```bash
   git clone https://github.com/mkowieska/Python_1
   cd nazwa-repozytorium
   ```

## Wygląd aplikacji
1. Panel startowy

![Panel startowy](screenshots/Task_manager.png)

2. Priorytetyzowanie

![Priorytetyzowanie](screenshots/priorities.png)

3. Filtrowanie

![Filtrowanie](screenshots/filters.png)
![Filtrowanie](screenshots/filters_medium.png)

4. Sortowanie

![Sortowanie](screenshots/sorting.png)

5. Zapis do pliku

![Zapis do pliku](screenshots/save_to_file.png)

6. Usuwanie

![Usuwanie](screenshots/before_deleting.png)
![Usuwanie](screenshots/deleting.png)
