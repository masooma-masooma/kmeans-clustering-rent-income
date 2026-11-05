# K-Means Clustering: Rent vs Income

Grouping Swedish regions by **annual rent per m²** and **average yearly income** using a **K-means algorithm written from scratch**, with **grid search** and the **silhouette score** to choose the best number of clusters.

## 🎯 What this project does
1. **K-means from scratch:** random centroid initialization, Euclidean distance, centroid updates and a convergence check, built with NumPy
2. **Cluster visualization:** scatter plots with a colour per cluster and the centroids marked
3. **Hyperparameter optimization:** grid search over k = 2 to 10, scored with the silhouette score
4. **Prediction on new data:** assigns three unseen regions to their nearest cluster
5. **Optional task:** a general N-dimensional grid search that can tune any number of hyperparameters

## 📊 Results
- **Optimal number of clusters: k = 3**, with a best silhouette score of **0.646**
- Classification of the three new regions:

| Annual rent (SEK/m²) | Avg income (KSEK) | Assigned cluster |
|---------------------:|------------------:|:----------------:|
| 1010 | 320.12 | 1 |
| 1258 | 320.00 | 2 |
| 980  | 292.40 | 1 |

## 🛠️ Tech Stack
Python · NumPy · pandas · Matplotlib · scikit-learn · Jupyter

## 🚀 How to Run
```bash
pip install -r requirements.txt
jupyter notebook kmeans_clustering.ipynb
```

## 📂 Data
The dataset (`inc_vs_rent.csv`) was provided through the course and is **not included** in this repository. All outputs and graphs are saved in the notebook, so the results can be viewed without running it.

## 📁 Files
```
├── kmeans_clustering.ipynb   # Main notebook
├── requirements.txt
└── README.md
```

## 👤 Author
Masooma, MSc Applied AI, Year 1
