## Zasady konkursu SRD
### Zespoły
Na czas konkursu należy dobrać się w zespoły. Proszę nazwać zespół (nazwa zespołu pojawi się w tabeli z wynikami). Proszę nie używać danych osobowych w nazwach.

### Zbiór danych i cel konkursu
Celem konkursu jest uzyskanie jak największej metryki celu w klasyfikacji zmiennej celu **IsIPA**. 
Metryką celu jest:
* [**F1-Score**](https://en.wikipedia.org/wiki/F-score) dla grup 11,13,15,17,
* [**Accuracy**](https://en.wikipedia.org/wiki/Accuracy_and_precision#In_classification) dla grup 12,14,16,18.

Do stworzenia i optymalizacji modelu proszę wykorzystać zbiór danych **IPA.csv**, natomiast finalną predykcję należy wykonać na zbiorze **IPA_test.csv**. Opis zbioru znajduje się w pliku **IPA_description.txt**.


### Wyniki
Wyniki należy przesłać na adres **lkrain@sgh.waw.pl** do końca zajęć danej grupy. W treści maila należy podać nazwę grupy oraz imiona i nazwiska członków - wystarczy mail od jednego członka grupy.

Jako załączniki należy zamieścić:
1. Skrypt/notatnik z wykorzystanym kodem (w dowolnym języku programowania)
2. Plik CSV o nazwie **[nazwa_grupy]_prediction.csv** zawierający jedną kolumnę z 5000 obserwacji (i opcjonalnym nagłówkiem) z wartościami 1/0 lub TRUE/FALSE oznaczających predykcję dla kolejnych wierszy ze zbioru testowego **IPA_test.csv**.

Proszę sprawdzić czy kolejność predykcji zgadza się z kolejnością obserwacji w zbiorze testowym. Proszę również zwrócić uwagę na braki danych w zbiorze testowym - należy je odpowiednio obsłużyć tak, aby otrzymać dokładnie 5000 predykcji.

Tabela z rankingiem zespołów pojawi się na GitHubie w poniższym pliku README. Najlepszy zespół w każdej grupie zajęciowej otrzyma dodatkowe 5 punktów, kolejny 4 punkty, itd.

Życzę powodzenia.

### Wyniki konkursu

**Grupa 11**

| **Zespół**          | **F1-score** | **Punkty** | **Model**           | **Język programowania** |
|---------------------|--------------|------------|---------------------|-------------------------|
| Bigos               | 0.7946       | 5          | XGBoost             | Python                  |
| Piraci z Karaibów   | 0.7862       | 4          | XGBoost             | Python                  |
| Baseline            | 0.7859       | 3          | XGBoost             | Python                  |
| Belgijskie Tygryski | 0.7849       | 2          | Random Forest       | Python                  |
| MCJG                | 0.7830       | 1          | Random Forest       | Python                  |
| MKJW                | 0.7029       | 0          | Logistic Regression | Python                  |

**Grupa 13**

| **Zespół**           | **F1-score** | **Punkty** | **Model**                         | **Język programowania** |
|----------------------|--------------|------------|-----------------------------------|-------------------------|
| Szwadron Wilków Alfa | 0.7955       | 5          | Gradient Boosting Classifier      | Python                  |
| Wojownicy Wody       | 0.7947       | 4          | Hist Gradient Boosting Classifier | Python                  |
| MB Haters Club       | 0.7895       | 3          | XGBoost                           | Python                  |
| Pogchamp Babci       | 0.7452       | 2          | Random Forest                     | Python                  |

**Grupa 15**

| **Zespół**    | **F1-score** | **Punkty** | **Model**                    | **Język programowania** |
|---------------|--------------|------------|------------------------------|-------------------------|
| Szczęśliwa 17 | 0.7915       | 5          | Gradient Boosting Classifier | Python                  |
| Mikołajki     | 0.7873       | 4          | Gradient Boosting Classifier | Python                  |
| LAM           | 0.5199       | 3          | Deep Neural Network          | Python                  |
| Top 5         | 0            | 2          | XGBoost                      | Python                  |

**Grupa 17**

| **Zespół**   | **F1-score** | **Punkty** | **Model**                    | **Język programowania** |
|--------------|--------------|------------|------------------------------|-------------------------|
| Jednoosobowy | 0.7941       | 5          | Gradient Boosting Classifier | Python                  |
| Super Kotki  | 0.7892       | 4          | XGBoost                      | Python                  |
| PT_PT        | 0.7826       | 3          | Random Forest                | Python                  |
| Smakosze     | 0.7775       | 2          | XGBoost                      | Python                  |
| MDM          | 0.7694       | 1          | Random Forest                | Python                  |
