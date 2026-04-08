# 🎵🔍 Music & Crime Correlation Explorer

Investigating statistical relationships between dominant music genres and crime patterns across 25 U.S. cities.

## Key Finding
Raw correlations between music audio features and crime rates (r=0.47) **collapse by 76%** when controlling for poverty and unemployment — proving that correlation ≠ causation.

## What This Project Does
- Collects Spotify audio features (energy, valence, danceability, tempo) for 25 cities
- Merges with FBI crime data and Census socioeconomic data
- Runs 6 statistical tests: Pearson, Spearman, ANOVA, Regression, Partial Correlation, Cohen's d
- Generates 6 publication-ready visualizations

## Tech Stack
Python | Pandas | NumPy | SciPy | Matplotlib | Seaborn | Statsmodels | Spotify API | FBI UCR API

## Quick Start
```bash
git clone https://github.com/shlok2018/music-crime-correlation-explorer.git
cd music-crime-correlation-explorer
python3 -m venv venv && source venv/bin/activate
pip install pandas numpy scipy matplotlib seaborn statsmodels openpyxl
python3 music_crime_pipeline.py
```

## Sample Visualizations
Check the `output/` folder for all charts including correlation heatmaps, scatter analysis, and confounding variable comparisons.

## Author
Shlok Sharma
