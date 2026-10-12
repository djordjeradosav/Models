# Machine Learning Models: Applied Notebooks

A collection of Jupyter notebooks covering the core supervised and unsupervised ML algorithms, applied to real datasets. Each notebook follows a full workflow: **data cleaning → EDA → preprocessing → model training → evaluation**.

**Python · scikit-learn · pandas · NumPy · SciPy · Matplotlib · Seaborn**

---

## Notebooks

| Topic | Notebook | Problem |
|---|---|---|
| **Linear regression** | `fastfood_protein_lr.ipynb`, `lm.ipynb` | Predicting protein content of fast-food items |
| **Decision tree** | `Stablo odlučivanja.ipynb`, `so.ipynb` | Bank customer churn prediction |
| **k-Nearest Neighbors** | `kNN.ipynb`, `kn.ipynb` | Classifying whether a Spotify track will be a hit (~90% accuracy) |
| **Neural network (MLP)** | `mlp_binary_classifier.ipynb`, `nm.ipynb` | Binary classification of breast-cancer tumours |
| **K-Means clustering** | `Primer ispitnog zadatka KMeans klasterizacija.ipynb`, `Km.ipynb` | Clustering Spotify songs by audio features (elbow method) |
| **Hierarchical clustering** | `Primer ispitnog zadatka hijerarhijska klasterizacija.ipynb`, `hk.ipynb` | Dendrogram-based song clustering |
| **All-in-one** | `vezba za sve.ipynb` | Combined practice across all methods |

## Techniques used

- Missing-value imputation chosen by distribution (Shapiro–Wilk normality test → mean vs median)
- Outlier detection and removal
- One-hot encoding of categorical variables, feature scaling
- Train/test splitting, cross-validation and hyperparameter tuning
- Evaluation: accuracy, precision/recall, confusion matrix, R², MAE/RMSE, silhouette score
- Elbow method and dendrograms to choose the number of clusters

## Run locally

```bash
pip install jupyter pandas numpy scipy scikit-learn matplotlib seaborn
jupyter notebook
```

`spotify.csv` is included; other datasets are loaded inside their notebooks.

> Coursework for a university machine-learning course. Notebook commentary is in Serbian.
