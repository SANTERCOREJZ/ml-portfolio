# ML Portfolio

I'm a 3rd-year Applied Data Analysis student at HSE, learning machine learning. This repository collects my ML projects: a Kaggle competition and three projects from my ML course covering data analysis, supervised classification and clustering.

## Projects

| Project | Task | Methods | Main result |
|---|---|---|---|
| [Titanic (Kaggle)](titanic-kaggle/) | Binary classification | Feature engineering, sklearn Pipeline, Logistic Regression, KNN, SVM, Decision Tree, error analysis | SVM: 0.838 CV accuracy, 0.77751 on Kaggle |
| [Telco Customer Churn](telco-churn/) | Binary classification | Decision Tree, Random Forest, AdaBoost, Gradient Boosting, GridSearchCV | Decision Tree chosen for recall 0.78 on churners (F1 0.53-0.55 for all models) |
| [Country Clustering](country-clustering/) | Clustering | StandardScaler, K-Means, elbow method, silhouette score, plotly maps | K=3 splits countries into developed / developing / least developed |
| [Fandango Ratings](fandango-ratings/) | Exploratory data analysis | pandas, seaborn, score normalization | Fandango averages 4.09/5 vs. 2.93-3.36 on other sites |

## Structure

Each project folder contains a `README.md`, the notebook, the data in `data/` and the charts in `images/`. The Titanic data is not included (Kaggle competition rules); its README explains how to download it.

## Setup

```bash
pip install -r requirements.txt
jupyter notebook
```

Tested with Python 3.11.
