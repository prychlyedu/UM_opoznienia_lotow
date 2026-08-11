Projekt zaliczeniowy z uczenia maszynowego przewidujący powód opóźnienia lotu. Wykorzystuje dwa modele UM, KNN(najbliższy sasiad) oraz DT(decision tree). 





Projekt został wykonany w języku Python z wykorzystaniem bibliotek:

Python
Pandas
NumPy
Matplotlib
Scikit-learn
KaggleHub
Jupyter Notebook / Google Colab

Biblioteki wykorzystane w notebooku obejmują m.in. pandas, numpy, matplotlib oraz narzędzia scikit-learn.

📁 Struktura projektu
├── README.md
└── UM_opoznienia_lotow.ipynb

Notebook zawiera cały proces analizy danych, przygotowania zmiennych oraz trenowania i oceny modeli Machine Learning.

▶️ Uruchomienie projektu
1. Sklonowanie repozytorium
git clone https://github.com/TWOJ-LOGIN/TWOJE-REPO.git
cd TWOJE-REPO
2. Instalacja bibliotek
pip install pandas numpy matplotlib scikit-learn kagglehub
3. Uruchomienie notebooka

Projekt można uruchomić za pomocą Jupyter Notebook:

jupyter notebook

lub zaimportować plik .ipynb do Google Colab.

Notebook pobiera zbiór danych za pomocą kagglehub z datasetu US Department of Transportation Flight Delays.

📈 Wyniki analizy

W zbiorze danych znajdowało się 5 819 079 rekordów lotów. Analiza zmiennej DELAY_REASON wykazała następujący rozkład:

Powód	Liczba przypadków
NO_DELAY	4 650 569
LATE_AIRCRAFT_DELAY	410 647
AIRLINE_DELAY	311 386
AIR_SYSTEM_DELAY	303 784
WEATHER_DELAY	35 711

Dane pokazują, że zdecydowana większość lotów w analizowanym zbiorze nie posiadała opóźnienia, natomiast wśród opóźnionych lotów najczęściej występowały opóźnienia związane z późniejszym samolotem.

👨‍💻 Autor

Patryk Rychły

Projekt zaliczeniowy z zakresu uczenia maszynowego.
