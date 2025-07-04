# Prédiction des ventes hebdomadaires Walmart

## 🎯 Objectif du projet
Ce projet vise à prédire les ventes hebdomadaires des magasins Walmart à partir de différentes variables économiques et temporelles, grâce à des modèles de régression linéaire et régularisée (Ridge, Lasso).

## 📄 Déroulement du projet
1. **Exploration et prétraitement des données**
   - Suppression des lignes avec valeurs manquantes critiques
   - Transformation de la colonne "Date" en variables année, mois, jour, etc.
   - Suppression des outliers sur les colonnes numériques
   - Séparation des variables explicatives (X) et de la cible (Y)

2. **Modèle de base : Régression Linéaire**
   - Entraînement d'un modèle LinearRegression
   - Analyse des coefficients et évaluation des performances (R2, RMSE)

3. **Régularisation avec Ridge et Lasso**
   - Recherche des meilleurs hyperparamètres avec GridSearchCV
   - Affichage et comparaison des coefficients
   - Visualisation interactive avec Plotly

## 📊 Résultats clés
- Le modèle Ridge fournit un bon compromis entre performance et stabilité.
- Lasso n'a pas réduit le nombre de variables (aucun coefficient à zéro), ce qui indique une contribution utile de toutes les features.
- Les visualisations permettent d'identifier les variables les plus influentes sur les ventes.

## 📁 Fichiers fournis
- `projet_Walmart.ipynb` : Notebook principal
- `Walmart_Store_sales.csv` : Jeu de données utilisé