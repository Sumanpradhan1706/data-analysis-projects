# 04 — Titanic Dataset Analysis and Survival Predictions

Project summary
- Exploratory analysis and predictive modeling on the Titanic passenger dataset to predict survival using feature engineering and classic ML models.

Notebooks
- `anaconda_projects/db/Titanic_Dataset_Analysis_and_Survival_Predictions.ipynb` — full analysis, model training, and evaluation.

Data
- `anaconda_projects/db/train.csv`, `anaconda_projects/db/test.csv`, `anaconda_projects/db/gender_submission.csv` — original Kaggle-format dataset files.

Key analyses
- Feature engineering (age imputation, titles, family size)
- Model building: Logistic Regression, Random Forest, Gradient Boosting
- Cross-validation and submission generation

Dependencies
- Python 3.8+; recommended: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`, `xgboost`.

Quick start
1. `conda create -n titanic_analysis python=3.8 -y`
2. `conda activate titanic_analysis`
3. `pip install pandas numpy scikit-learn matplotlib seaborn xgboost`
4. `jupyter notebook anaconda_projects/db/Titanic_Dataset_Analysis_and_Survival_Predictions.ipynb`

Results
- The notebook contains model scores, confusion matrices, and a reproducible pipeline for generating submissions.

Contact
- Maintainer: Project owner. Suggestions and improvements are welcome.
