# 05 — Recommendation System in Python

Project summary
- Item-based movie recommendation demo using user rating data. Builds a sparse user–item matrix and finds similar movies via k-nearest neighbors with cosine similarity.

Notebook
- `anaconda_projects/db/Recommendation System in Python.ipynb` — end-to-end data load, matrix creation, and similarity-based recommendations.

Data
- `anaconda_projects/db/ratings.csv` — user ratings with columns like `userId`, `movieId`, `rating`, `title`.
- Keep data files out of Git history; they are ignored via `.gitignore`.

Core steps
- Load ratings and inspect head of the dataset.
- Build a sparse movie–user matrix with `scipy.sparse.csr_matrix`.
- Map movie IDs to matrix indices and invert mappings for lookups.
- Compute nearest neighbors with `sklearn.neighbors.NearestNeighbors` (cosine, brute force).
- Provide a helper to print top-k similar movies for a given title.

Dependencies
- Python 3.8+
- `pandas`, `numpy`, `scikit-learn`, `scipy`, `matplotlib`, `seaborn`, `jupyter`

Quick start
1) Create and activate an environment (example):
```powershell
conda create -n recommender_env python=3.8 -y
conda activate recommender_env
```
2) Install packages:
```powershell
pip install pandas numpy scikit-learn scipy matplotlib seaborn jupyter
```
3) Launch the notebook:
```powershell
jupyter notebook "anaconda_projects/db/Recommendation System in Python.ipynb"
```
4) Run cells top to bottom. Update `movie_title` in the `recommend_similar` call to get recommendations for another movie title present in the dataset.

Outputs
- Printed top-k similar movie titles for a given input movie based on cosine similarity of user-rating vectors.

Notes
- Ensure `ratings.csv` stays alongside the notebook (or adjust the read path).
- Data files remain ignored in version control; add a small sample if sharing the project publicly.

Contact
- Maintainer: Project owner. Contributions and suggestions are welcome.
