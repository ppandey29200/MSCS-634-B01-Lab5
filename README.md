# MSCS-634-B01-Lab5

## Purpose
The purpose of this lab is to explore and compare **Hierarchical Clustering** and **DBSCAN Clustering** techniques using the Wine dataset. The objective was to apply these unsupervised learning methods, evaluate clustering quality using various metrics, and visualize the results to understand their strengths and weaknesses.

## Key Insights
- Hierarchical Clustering successfully identified natural groupings in the data and provided a clear dendrogram for cluster selection.
- DBSCAN was highly dependent on `eps` and `min_samples` parameters and was more effective at detecting noise points.
- Hierarchical clustering generally produced better silhouette and homogeneity scores for this dataset.

## Challenges
- Choosing appropriate parameters for DBSCAN required several iterations.
- Visualizing high-dimensional data required reducing to two principal features for plotting.
- Balancing cluster interpretability and evaluation metrics required careful experimentation.

## Files
- `lab5.ipynb` - Jupyter Notebook with the full code and analysis.
- `README.md` - This file, describing the lab purpose, insights, and challenges.
