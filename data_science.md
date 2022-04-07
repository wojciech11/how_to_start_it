# Kierunek - Data Science & BI

Kilka słów na start, patrz [prezentacja](https://github.com/wojciech11/how_to_start_your_it_career/blob/master/tester_pl.pdf) jak zacząć - **patrz slajdy "Czas nauki"**.

## Iteracja podstawy

### Ubuntu

Recomendowane [Ubuntu LTS](https://wiki.ubuntu.com/Releases) - 20.04.3.

1. Zainstaluj:
   
    - [VSCode](https://code.visualstudio.com/)
    - [Miniconda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/linux.html)

2. Jupyterlab:

   ```bash
   conda create -n ds-first
   conda activate ds-first

   conda install --channel conda-forge jupyterlab
   conda install --channel conda-forge ipywidgets
   ```

   ```bash
   # uruchom jupyther
   jupyter lab
   ```

3. Załóż konto na kaggle.com i zrób tutorial Python w przeglądarce z użyciem notebooków - https://www.kaggle.com/learn/python

3. Zrób instrukcję jak uruchomić "Hello World tutorial for Flask" z https://docs.microsoft.com/en-us/windows/python/web-frameworks

5. Czas na klasyczny tutorial, wykonaj na swoim komputerze:

   - https://www.edx.org/course/introduction-to-computer-science-and-programming-7
   - [Automate boring staff with Python](https://automatetheboringstuff.com)

### Windows 

Zauważ rekomendowane jest Ubuntu, ale możesz później przesiąść się z Windowsa na Ubuntu, na razie skup się na Pythonie i poznaniu środowiska Jupyther notebook.

1. Przygotowanie swojego lokalnego środowiska, zainstaluj (uczenie się traktowania swojego komputera jako narzędzia):

   1. WSL - ubuntu 20.04 - [instrukcja](https://docs.microsoft.com/en-us/windows/wsl/install).

   2. Python3 i VSCode - [instrukcja](https://docs.microsoft.com/en-us/windows/python/web-frameworks) - bez Flaska, później do tego wrócisz, wystarczy, żebyś na razie uruchomił:
      ```python
      print("hello world")
      ```

   3. Miniconda i Jupytherlab - [instrukcja](https://www.gerritjandebruin.nl/jupyter.html)

2. Załóż konto na kaggle.com i zrób tutorial Python w przeglądarce z użyciem notebooków - https://www.kaggle.com/learn/python

3. Zrób instrukcję jak uruchomić "Hello World tutorial for Flask" z https://docs.microsoft.com/en-us/windows/python/web-frameworks

4. Czas na klasyczny tutorial, wykonaj na swoim komputerze:

   - https://www.edx.org/course/introduction-to-computer-science-and-programming-7
   - [Automate boring staff with Python](https://automatetheboringstuff.com)

## Iteracja 2

1. Wyszukać jakiś tutorial zbudowania prostej aplikacji flask, drugi raz. Coś bardziej skomplikowanego, nie koniecznie z baza danych.

2. Wracamy do Kaggle:

   - Pandas: https://www.kaggle.com/learn/pandas
   - Data Vizualization: https://www.kaggle.com/learn/data-visualization
   - SQL: https://www.kaggle.com/learn/intro-to-sql

3. Wybierz jakąś aplikację z tutoriali do rozbudowy, pomyśl jak można ją rozbudować. Na przykład, pandas i problem wyliczania wartości koszyka - http://codekata.com/kata/kata01-supermarket-pricing/

## Iteracja 3 - TBA

1. Załóż konto na github, naucz się jak umieszczać pliki:

   1. Zainstaluj git na WSL2 - https://docs.microsoft.com/en-us/windows/wsl/tutorials/wsl-git
   2. Tutorial, 2x mantra GIT - https://github.com/wojciech11/se_software_build_automation_tools/blob/master/01_exercise/README_pl.md
   3. [Tutorial Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

2. TBA

## Dodatkowe

- https://automatetheboringstuff.com - many ideas for Python programs
- https://missing.csail.mit.edu - 2 pierwsze części - shell tools and scripting
