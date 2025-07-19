# Task Manager - Graficzny menedżer zadań
Aplikacja umożliwia dodawanie zadań z priorytetem, filtrowanie, sortowanie, usuwanie, a także zapis i odczyt listy zadań z pliku tekstowego.

**Projekt na zaliczenie z przedmiotu Python** na Zachodniopomorskim Uniwersytecie Technologicznym w roku akademickim 2023/2024.

## Autor
Martyna Kowieska

## Funkcjonalności
- Prosty interfejs graficzny z przyciskami i rozwijanymi menu.
- Dodawanie zadania z wybranym priorytetem (Low, Medium, High).
- Automatyczne nadawanie znacznika czasu (dd-mm-YYYY HH:MM:SS).
- Wyświetlanie listy ponumerowanych zadań.
- Filtrowanie zadań po priorytecie (All / Low / Medium / High).
- Sortowanie zadań według czasu dodania lub priorytetu.
- Usuwanie zadania po numerze z listy.
- Zapis wszystkich zadań do pliku tekstowego.
- Odczyt zadań z pliku i odtworzenie listy.

## Technologie

|   Technologia   |                   Zastosowanie                  |
|:---------------:|:-----------------------------------------------:|
| Python (3.9.13) | Logika aplikacji                                |
| tkinter         | Podstawowy GUI                                  |
| customtkinter   | Ulepszony wygląd widżetów                       |
| Pillow (PIL)    | Wczytywanie i skalowanie obrazów (logo / ikony) |

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


## Struktura plików
Python_1/
│
├─ Task.py               # Definicje klas Task i TaskManager
├─ main.py               # Główny punkt wejścia aplikacji
├─ images/               # Katalog na obrazy (logo, ikony)
│   ├─ img_star.jpg
│   ├─ img_save.jpg
│   └─ img_read.jpg
├─ screenshots/          # Zdjęcia menadżera zadań
│   ├─ before_deleting.png
│   ├─ deleting.png
│   ├─ filters.png
│   ├─ filters_medium.png
│   ├─ priorities.png
│   ├─ save_to_file.png
│   ├─ sorting.png
│   └─ task_manager.png 
├─ laboratoria/          # Pliki z ćwiczeń laboratoryjnych
│   ├─ lab1-Python.py 
│   ├─ lab2-Python.py 
│   ├─ lab3-Python.py
│   ├─ lab4-Python.py 
│   ├─ lab5-Python.py 
│   ├─ lab6-Python.py  
│   └─ lab7-Python.py 
└─ README.md