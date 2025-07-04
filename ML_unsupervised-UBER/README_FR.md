# Analyse des trajets Uber à New York - 2014

Ce projet propose une analyse des trajets Uber réalisés à New York en 2014. Il repose sur un ensemble de données publiques et a pour but d’explorer les dynamiques spatiales et temporelles des trajets à l’aide de techniques de visualisation et de clustering.

## Objectifs

- Analyser la distribution des trajets selon l’heure et le jour.
- Identifier des patterns entre semaine et week-end.
- Appliquer des algorithmes de clustering (DBSCAN, KMeans).
- Visualiser les clusters géographiques sur une carte interactive.
- Générer des animations pour suivre l’évolution des trajets dans le temps.

## Contenu

- **UBER.ipynb** : Notebook principal avec traitement des données, clustering, visualisations interactives et animations.
- **01-Uber_Pickups.ipynb** : Notebook de référence initial (source).

## Données utilisées

Les données proviennent de trajets Uber géolocalisés en 2014 à New York, incluant :
- Horodatage des trajets
- Coordonnées GPS (Latitude, Longitude)
- Jour de la semaine, heure
- Variable `weekend` (True/False)

## Librairies principales

- `pandas`, `numpy`
- `scikit-learn` (DBSCAN, KMeans)
- `plotly` pour la cartographie et les animations
- `matplotlib` pour les analyses descriptives

## Résultat

Des visualisations interactives permettent d’observer :
- L’évolution horaire des trajets
- La différence semaine / week-end
- Les clusters spatiaux sur la carte de New York

## Auteur

Projet réalisé dans le cadre d’un exercice de data science – 2024.
