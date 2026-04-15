# Lab 7

## Overview
This laboratory focus on the implementation and comparison of two popular unsupervised learning algorithms: **k-Means Clustering** and the **Expectation-Maximization (EM) Algorithm**. The objective is to group a set of data points into clusters based on their inherent similarities and analyze the performance differences between distance-based and probability-based clustering.


## Objectives
- Implement the k-Means clustering algorithm using Python/Scikit-Learn.
- Implement the Expectation-Maximization (EM) algorithm using Gaussian Mixture Models (GMM).
- Compare the quality of clusters produced by both algorithms on the same dataset.
- Visualize cluster assignments and centroids.

## Dataset
The lab typically utilizes a standard CSV dataset (e.g., Iris dataset or a custom synthetic dataset). 
- **Format:** .csv
- **Features:** [Mention features, e.g., Sepal Length, Sepal Width, etc.]
- **Target:** Unlabeled (for clustering purposes).

## Key Tasks
1. **Data Preprocessing:** Load the dataset and handle any missing values or scaling requirements.
2. **k-Means Implementation:** Apply the k-Means algorithm to find a predefined number of clusters ($k$).
3. **EM Implementation:** Apply the EM algorithm (Gaussian Mixture Model) to the same data.
4. **Comparison:** - Evaluate results using metrics such as Silhouette Score or visually via scatter plots.
    - Discuss why one algorithm may outperform the other for certain data distributions.

## Requirements
To run the notebooks/scripts in this lab, you will need:
- Python 3.x
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn
