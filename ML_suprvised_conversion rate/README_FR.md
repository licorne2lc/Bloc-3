# 📊 Prédiction du Taux de Conversion

## Description du projet

Ce projet de data science a pour objectif de **prédire si un utilisateur convertira** (achètera un produit) après avoir cliqué sur une publicité.
Les données utilisées sont issues de la plateforme d'apprentissage [Analytics Vidhya](https://datahack.analyticsvidhya.com/) et comprennent des informations utilisateur (âge, source, pays...) et des données de campagne.

## 🔍 Étapes réalisées

1. Chargement des données
2. Contrôle des valeurs manquantes
3. Analyse exploratoire (EDA)
4. Feature Engineering
5. Séparation en jeu d'entraînement et de test
6. Entraînement de modèles :
   - Régression logistique
   - Arbre de décision
   - Forêt aléatoire
   - AdaBoost, Gradient Boosting, XGBoost
7. Évaluation :
   - Matrices de confusion
   - Scores : Précision, Rappel, F1
   - Visualisation interactive Plotly
8. Méthode d’ensemble par vote
9. Comparaison des modèles

## 📁 Fichiers

- `conversion_rate.ipynb` : Notebook principal
- `conversion_data_train.csv` : Jeu de données
- `README_FR.md` : Présentation du projet (ce fichier)

## ▶️ Exécution

Ouvrir le notebook avec Jupyter ou VSCode et exécuter les cellules.
Librairies utilisées : `pandas`, `sklearn`, `xgboost`, `plotly`.