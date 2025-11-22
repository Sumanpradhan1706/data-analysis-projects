# data-analysis-portfolio-projects

Overview
- This repository is a portfolio of small-to-medium data analysis projects implemented as Jupyter notebooks. Each project contains exploratory data analysis (EDA), visualizations, and (where applicable) baseline models. Use the per-project README files for more details.

Projects

1. 01_Zomato_Data_Analysis
- Summary: Exploration and visualization of restaurant data (ratings, cuisines, locations, pricing).
- Notebook: `01_Zomato_Data_Analysis/anaconda_projects/db/01_Zomato_Data_Analysis.ipynb`
- Data: `01_Zomato_Data_Analysis/anaconda_projects/db/Zomato-data-.csv`
- Project README: `01_Zomato_Data_Analysis/README.md`

2. 02_Customer_Churn_Analysis
- Summary: EDA and predictive modeling for customer churn using the Telco dataset. Demonstrates feature engineering and baseline classifiers.
- Notebook: `02_Customer_Churn_Analysis/anaconda_projects/db/Customer_Churn_Analysis.ipynb`
- Data: `02_Customer_Churn_Analysis/anaconda_projects/db/Telco-Customer-Churn.csv`
- Project README: `02_Customer_Churn_Analysis/README.md`

3. 03_Global_Covid19_Analysis
- Summary: Time-series analysis and visualizations of global COVID-19 case and death trends.
- Notebook: `03_Global_Covid19_Analysis/anaconda_projects/db/Global_Covid19_Analysis.ipynb`
- Data: `03_Global_Covid19_Analysis/anaconda_projects/db/covid.csv`, `covid_grouped.csv`, `coviddeath.csv`
- Project README: `03_Global_Covid19_Analysis/README.md`

4. 04_Titanic Dataset Analysis and Survival Predictions
- Summary: Titanic EDA and supervised learning pipeline for survival prediction (Kaggle format datasets included).
- Notebook: `04_Titanic Dataset Analysis and Survival Predictions/anaconda_projects/db/Titanic_Dataset_Analysis_and_Survival_Predictions.ipynb`
- Data: `04_Titanic Dataset Analysis and Survival Predictions/anaconda_projects/db/train.csv`, `test.csv`, `gender_submission.csv`
- Project README: `04_Titanic Dataset Analysis and Survival Predictions/README.md`

Getting started (recommended per-project)
1. Open a PowerShell terminal and change to the repository root.

2. Create and activate a project-specific Conda environment (example):

```powershell
conda create -n <env_name> python=3.8 -y
conda activate <env_name>
```

3. Install common dependencies (adjust per project as needed):

```powershell
pip install pandas numpy matplotlib seaborn plotly scikit-learn jupyter
```

4. Launch the notebook for the project you want to inspect, for example:

```powershell
jupyter notebook 02_Customer_Churn_Analysis/anaconda_projects/db/Customer_Churn_Analysis.ipynb
```

Notes
- Each project folder contains a project-level `README.md` with more detailed instructions and recommended packages. If you plan to reproduce results, pin package versions in a `requirements.txt` or export the Conda environment.
- File paths in this README are relative to the repository root.

Contributing
- Suggestions and improvements are welcome — open an issue or submit a pull request. Keep notebooks runnable and document any environment changes.

Contact
- Repository owner / maintainer: Project owner.
