# Evaluating Unsupervised Clustering Methods
# Overview

This project explores unsupervised clustering techniques on a complex, synthetic dataset. Multiple clustering algorithms are evaluated, with careful tuning of their hyperparameters using appropriate selection methods. The resulting clusterings are compared using quantitative evaluation metrics to assess performance and determine the most effective approach for capturing the underlying structure of the data.

The notebook walks through data exploration, K-Means clustering, Guassian Mixture model, and DBSCAN, and model evaluation.

# Objectives
- Explore data clusterings using scatter-density plot
- Identify optimal number of clusters for each model: K-Means clustering, Guassian Mixture model, and DBSCAN
- Visualize clustering methods
- Compare model performance using appropriate evaluation metrics

# Dataset
**Unsupervised Clustering Data**: Synthetic 


# Dependencies
This project uses the following Python libraries:

```
pandas
numpy
matplotlib
seaborn
scikit-learn
scipy
```

Install third-party dependencies with:

```
pip install pandas numpy matplotlib seaborn scikit-learn scipy
```

# Model Evaluation

Cluster performance is evaluated using metrics such as:
- Silhouette Score
- Davies-Bouldin Score

These metrics are used to compare models and assess predictive accuracy.

# Results & Insights

Key findings include:
- For k-means, the elbow plot, silhouette score, and davies-bouldin scores all infered that three was the optimial number of clusters.
- AIC and BIC for the Gaussian Mixtures identified 5 as the optimal number of clusters.
- The DBSCAN model was optimized with 5 clusters.
- DBSCAN was the only model able to address outliers in the data.
