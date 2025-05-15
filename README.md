# TIME_SERIE_PROJECT
Prévision de la tendance boursière de Microsoft (MSFT) en utilisant des modèles de séries temporelles (AR, ARIMA, SARIMA), avec visualisation des performances (MSE, RMSE) et comparaison des résultats.

# 📈 Time Series Forecasting - Microsoft Stock Trend

Ce projet vise à prédire la tendance boursière de l'action Microsoft (MSFT) à l'aide de différents modèles de séries temporelles. Il s'agit d'un travail d'analyse, de modélisation et de visualisation basé sur les données historiques de MSFT de 1986 à 2025.

## 📌 Objectifs

- Apprendre les fondamentaux des modèles AR, ARIMA et SARIMA
- Comparer leurs performances sur des données financières réelles
- Visualiser la qualité des prédictions

## 📁 Données

Le jeu de données utilisé est :  
**MSFT_1986-03-13_2025-02-04.csv** et une extension de ce fichier pour atteindre un large dataset 
Colonnes : `Date`, `Open`, `High`, `Low`, `Close`, `Adj Close`, `Volume`

## 🧠 Modèles Testés

- ✅ **Persistence Model** (modèle de référence)
- ✅ **Autoregressive Model (AR)**  
  - Meilleur lag : `97`
- ✅ **ARIMA**  
  - Meilleurs paramètres : `(2,1,3)`
- ✅ **SARIMA**  
  - Meilleurs paramètres : `(2,1,2) × (2,1,1,5)`

## 📊 Évaluation des modèles

- **Metrics utilisées** :  
  - RMSE (Root Mean Square Error)  
  - MSE (Mean Square Error)

- **Visualisation des résultats** :  
  - Comparaison graphique des prédictions vs valeurs réelles  
  - Graphe comparatif des erreurs (MSE/RMSE) des modèles

## 📦 Contenu du dépôt

