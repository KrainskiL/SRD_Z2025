# SRD_Z2025
Repozytorium do przedmiotu Statystyczne Reguły Decyzyjne [223490-D] - Semestr zimowy 2025/2026

**Wymagane oprogramowanie**

W trakcie ćwiczeń będziemy korzystać z Pythona w notatniku Jupyter.
Do uruchomienia materiałów wykorzystanych w trakcie ćwiczeń potrzebne jest następujące oprogramowanie:
* [Python](https://www.python.org/downloads/) (użytkownicy Windowsa w łatwy sposób mogą pobrać Pythona z [Anacondą](https://anaconda.org/))
* [Jupyter](https://jupyter.org/install) Notebook lub Jupyter Lab
* [Git](https://git-scm.com/)

---
**Kontakt**

Imię i nazwisko: Łukasz Kraiński

Email: lkrain@sgh.waw.pl

Konsultacje przez MS Teams lub we wtorki w sali G-103, 08:00-09:40 (po wcześniejszej wiadomości na MS Teams lub przez e-mail)

---
**Prowadzący zajęcia**

* wykłady: Bogumił Kamiński
* ćwiczenia: Łukasz Kraiński

---
**Harmonogram**

* wykłady: wtorki, G-Aula I, 09:50

* ćwiczenia: wtorki, G-108:
  * 13:30 (Grupy 11 i 12)
  * 15:20 (Grupy 13 i 14),
  * 17:10 (Grupy 15 i 16),
  * 19:00 (Grupa 17 i 18)

---

**Tematy spotkań**
|     #    |     Temat                                                                                          |
|----------|----------------------------------------------------------------------------------------------------|
|     1    |     Zajęcia   organizacyjne; wprowadzenie do narzędzia Jupyter Notebook z językiem Python   |
|     2    |     Metody   oceny jakości modeli klasyfikacyjnych                                                 |
|     3    |     Regularyzacja i walidacja krzyżowa                                                            |
|     4    |     Modele oparte na drzewach (CART, Random Forest, XGBoost)                            |
|     5    |     Konkurs modelarski                                                         |
|     6    |     Prezentacje projektów                                                                          |
|     7    |     Konsultacje (dla niektórych grup)                                                                  |

---
**Literatura**

* Literatura podstawowa
  * Materiały udostępniane na wykładzie
  * Gareth J., Witten D., Hastie T., Tibshirani R. (2023), [An Introduction to Statistical Learning](https://www.statlearning.com/)
* Literatura dodatkowa
  * Hastie T., Tibshirani R., Friedman J. (2017), [The Elements of Statistical Learning](https://hastie.su.domains/ElemStatLearn/)
  * Kamiński B. (2022), [Julia for Data Analysis](https://www.manning.com/books/julia-for-data-analysis)
  * Mykel J. Kochenderfer, Tim A. Wheeler, And Kyle H. Wray (2022), [Algorithms for Decision Making](https://algorithmsbook.com/)
  * Stephen Boyd and Lieven Vandenberghe, [Introduction to Applied Linear Algebra](http://vmls-book.stanford.edu/)
  * Kamiński B., Zawisza M. (2012), [Receptury w R. Podręcznik dla ekonomisty](http://bogumilkaminski.pl/projekty/)
  * VanderPlas J. (2016), [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/)
  * Géron A. (2019), [Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow](https://github.com/ageron/handson-ml2)

---
**Zasady zaliczenia**

* Kolokwium teoretyczne na ostatnim wykładzie (50 punktów)
* Praktyczny projekt w grupach (do 3 osób) na ćwiczeniach (50 punktów)
* Punkty dodatkowe:
  * Prace domowe
  * Konkurs w trakcie laboratorium

---

#### Projekt analityczny (50 punktów)

Do stworzenia raportu proszę wykorzystać zbiór danych https://archive.ics.uci.edu/ml/datasets/Adult lub inny o podobnej charakterystyce (liczba rekordów, liczba atrybutów, konieczność zaadresowania jakości danych). Projekt można wykonywać w grupach do 3 osób.

Zadanie polega na analizie danych, przeprowadzeniu procesu modelowania i sporządzeniu raportu o następującej strukturze:

1) Wprowadzanie i opis wybranego problemu (klasyfikacja lub regresja), opis zbioru danych.

2) Czyszczenie i wstępne przetwarzanie danych - imputacja braków danych, standaryzacja, kodowanie typu one-hot, transformacja wartości odstających, itp.

3) Graficzna i opisowa analiza eksploracyjna (EDA), m.in. graficzna prezentacja zależności pomiędzy wybraną zmienną celu i zmiennymi niezależnymi, wykonanie i opisanie wyników segmentacji (klastrowania) rekordów, itp.

4) Stworzenie modeli i tuning hiperparametrów do zadania klasyfikacji lub regresji

5) Graficzna i opisowa ocena oraz wybór modelu

6) Podsumowanie wyników, dyskusja na temat napotkanych problemów, wyzwań i zastosowanych rozwiązań

Kod i opisy/komentarze powinny zawierać się w notatniku Jupyter. 

Raporty proszę przesyłać na adres _lkrain@sgh.waw.pl_ w formacie .html oraz .ipynb. Na szóstych zajęciach projekt będzie prezentowany w trakcie laboratorium ok. 15 min. Termin oddania raportów to **20.01.2026**. 

---
**Ocena końcowa**
|Od |Do|Ocena|
|-----|--|--------|
|0 |49| 2.0|
|50 |59 |3.0|
|60 |69 |3.5|
|70 |79 |4.0|
|80 |89 |4.5|
|90 |100 |5.0|
