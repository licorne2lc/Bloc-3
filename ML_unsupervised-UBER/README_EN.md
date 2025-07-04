# Uber Trips Analysis in New York - 2014

This project analyzes Uber trips in New York City during the year 2014. Using public data, it explores spatial and temporal patterns in Uber pickups through clustering and interactive visualizations.

## Objectives

- Explore the distribution of trips by hour and day of the week.
- Compare weekday and weekend activity.
- Apply clustering algorithms (DBSCAN, KMeans).
- Visualize clusters on an interactive map.
- Create animations to observe trip evolution over time.

## Contents

- **UBER.ipynb**: Main notebook with data processing, clustering, interactive maps, and animations.
- **01-Uber_Pickups.ipynb**: Reference notebook (original source).

## Data Description

The dataset contains Uber pickups in NYC during 2014, including:
- Timestamps
- GPS coordinates (Latitude, Longitude)
- Day of week, hour
- `weekend` variable (True/False)

## Main Libraries

- `pandas`, `numpy`
- `scikit-learn` (DBSCAN, KMeans)
- `plotly` for mapping and animation
- `matplotlib` for descriptive analysis

## Output

The project includes interactive visualizations such as:
- Hour-by-hour trip evolution
- Weekday vs. weekend comparison
- Spatial clustering on NYC map

## Author

Project completed as a data science training exercise – 2024.
