# Projekt: World Happiness Report

Repozytorium zawiera projekt zespołowy z przedmiotu Statystyczna analiza danych. Analizujemy dane z raportu World Happiness Report.

## Struktura
- `data/` – dane źródłowe (CSV z Kaggle)
- `notebooks/` – notebooki robocze:
  - `01_wprowadzenie_i_czyszczenie.ipynb` – wczytanie i czyszczenie danych
  - `02_wizualizacje.ipynb` – wizualizacja danych
  - `03_analiza_statystyczna_i_wnioski.ipynb` – analiza opisowa i wnioski
  - `final_project.ipynb` – scalony notebook, który uruchamia wszystkie powyższe

## Skład zespołu
- Karolina Kornacka
- Karol Drobniewski
- Łukasz Kortals

# Każdy członek zespołu odpowiada za osobny notebook. Do scalania używamy komendy:
`nbmerge notebooks/01_wprowadzenie_i_czyszczenie.ipynb notebooks/02_wizualizacja.ipynb notebooks/03_analiza_statystyczna_i_wnioski.ipynb --output final_project.ipynb .`


<!-- dodałem 
pip install nbformat
ip install nbmerge -->

# wygląda na to, że za każdym razem to nadpisuje. czyli najpierw czyści plik docelowy, a później kopuje. czy jakoś tak, w każdym razie działa
<!-- nbmerge notebooks/01_wprowadzenie_i_czyszczenie.ipynb notebooks/02_wizualizacja.ipynb notebooks/03_analiza_statystyczna_i_wnioski.ipynb --output final_project.ipynb -->