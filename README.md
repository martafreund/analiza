# Analiza danych Netflix
 
## Opis projektu
Celem projektu jest analiza zbioru danych zawierającego filmy i seriale dostępne na platformie Netflix. W ramach projektu wykonano przygotowanie danych, ich oczyszczenie, analizę opisową oraz wizualizację wyników.
## Zakres projektu
 
Projekt obejmuje następujące etapy:
 
- wczytanie danych,
- wstępną analizę zbioru,
- czyszczenie i porządkowanie danych,
- usunięcie brakujących oraz błędnych wartości,
- analizę opisową,
- przygotowanie wykresów,
- wyciągnięcie wniosków.
## Wykorzystane technologie
 
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
 ## Struktura projektu
 
```
.
├── netflix_cleaning.ipynb   # główny notebook z analizą danych
├── netflix_titles.csv       # zbiór danych
└── README.md                # opis projektu
```
## Przeprowadzone analizy
 
W projekcie wykonano następujące analizy:
 
1. Analiza liczby filmów i seriali.
2. Analiza kategorii wiekowych.
3. Analiza krajów produkcji.
4. Analiza roku produkcji.
## Czyszczenie danych
 
W ramach przygotowania danych wykonano:
 
- usunięcie duplikatów,
- uzupełnienie brakujących wartości (`Unknown`),
- konwersję odpowiednich typów danych,
- usunięcie trzech błędnych rekordów z kolumny `rating`, które zawierały czas trwania filmu zamiast kategorii wiekowej.

## Wizualizacje
 
Projekt zawiera wykresy przedstawiające:
 
- liczbę filmów i seriali,
- rozkład kategorii wiekowych,
- liczbę produkcji według krajów,
- liczbę produkcji według roku wydania.

## Wnioski
 
Na podstawie przeprowadzonej analizy stwierdzono, że:
 
- większość produkcji stanowią filmy,
- najczęściej występującą kategorią wiekową jest **TV-MA**,
- największa liczba produkcji pochodzi ze Stanów Zjednoczonych,
- większość produkcji została wyprodukowana po 2010 roku.

## Autorzy
 
Projekt został wykonany w ramach zajęć z analizy danych.
 
Marta Freund 
Magdalena Bałys
Mateusz Strzeszak
Julia Giers
