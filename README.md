# Spotify Music Analysis

## Project Overview
End-to-end Music Analytics project analyzing 113,549 Spotify tracks 
across 125 genres, uncovering audio patterns, mood profiles, 
and popularity drivers.

## Tools Used
* Python (pandas, matplotlib, seaborn, scikit-learn)
* SQL (PostgreSQL / pgAdmin)
* Power BI

## Project Phases
1. Data Cleaning — Loaded and cleaned 113,549 tracks, 
   converted duration, removed duplicates and nulls
2. SQL Analysis — 13 business queries including window 
   functions, CTEs, subqueries and CASE statements
3. EDA — 6 visualizations uncovering audio trends, 
   genre patterns and popularity distributions
4. ML Modeling — Predicted track popularity using 
   Random Forest (R²: 0.53, MAE: 10.92)
5. Clustering — Identified 5 mood profiles using K-Means
6. Power BI Dashboard — Interactive dashboard with 
   slicers, KPIs and mood explorer

## Key Insights
* Party/Feel Good is the most common mood (41,018 tracks)
* Acousticness is the #1 predictor of track popularity
* Explicit tracks have slightly higher average popularity
* Reggaeton is the most danceable genre (0.76)
* Gym Hype tracks have the highest energy (0.81)
* 5 distinct mood profiles identified: Party/Feel Good, 
  Gym Hype, Sad/Chill Acoustic, Live Performance, 
  Instrumental/Classical

## Files
* `spotify_analysis.ipynb` — Full Python code
* `spotify_dashboard.pbix` — Power BI dashboard
* `spotify_final.csv` — Final cleaned dataset with 
  clusters and mood labels

## How to Run
1. Clone this repository
2. Open `spotify_analysis.ipynb` in Jupyter Notebook
3. Run all cells from top to bottom
4. Open `spotify_dashboard.pbix` in Power BI Desktop
