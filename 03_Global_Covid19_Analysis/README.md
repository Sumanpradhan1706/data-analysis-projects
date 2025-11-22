# 03 — Global Covid-19 Data Analysis and Visualizations

Project summary
- A collection of analyses and visualizations exploring global COVID-19 case and mortality trends over time and across countries.

Notebooks
- `anaconda_projects/db/Global_Covid19_Analysis.ipynb` — data cleaning, time series analysis, and visual dashboards.

Data
- `anaconda_projects/db/covid.csv`, `anaconda_projects/db/covid_grouped.csv`, `anaconda_projects/db/coviddeath.csv` — datasets used for visuals and aggregation.

Key analyses
- Time series of confirmed cases and deaths
- Country-level comparisons and growth rates
- Choropleth and trend visualizations

Dependencies
- Python 3.8+; recommended: `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`, `geopandas` (optional for maps).

Quick start
1. `conda create -n covid_analysis python=3.8 -y`
2. `conda activate covid_analysis`
3. `pip install pandas numpy matplotlib seaborn plotly geopandas`
4. `jupyter notebook anaconda_projects/db/Global_Covid19_Analysis.ipynb`

Notes
- Datasets are included in `anaconda_projects/db/`. Verify column names before reusing scripts.

Contact
- Maintainer: Project owner.
