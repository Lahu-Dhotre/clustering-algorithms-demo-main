# Clustering Algorithms Demo

This repository contains a simple machine learning demo for customer segmentation using the K-means clustering algorithm.

## Overview

The project uses the `Mall_Customers.csv` dataset to cluster customers based on:

- Annual Income (k$)
- Spending Score (1-100)

The notebook walks through the end-to-end workflow:

1. Loading the dataset
2. Preparing feature data for clustering
3. Using the Elbow Method to estimate the best number of clusters
4. Training a K-Means model
5. Assigning cluster labels to customers
6. Saving the labeled output to `cluster.csv`

## Files

- `1.K-means.ipynb` — main notebook implementing the clustering workflow
- `Mall_Customers.csv` — customer dataset used for clustering
- `cluster.csv` — clustered customer data with an added `Cluster_group` column

## Requirements

Install the following Python packages:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

## Run the notebook

Open the notebook in Jupyter Notebook or JupyterLab and run all cells:

```bash
jupyter notebook "1.K-means.ipynb"
```

or

```bash
jupyter lab
```

Then open `1.K-means.ipynb` from the interface.

## Demo details

The notebook demonstrates:

- Data exploration with Pandas
- Feature selection for K-Means
- Elbow method for selecting `k`
- Cluster assignment using `sklearn.cluster.KMeans`
- Visualization of cluster results
- Exporting the labeled dataset

## Result

The project groups customers into clusters based on their annual income and spending habits, making it a practical example of unsupervised learning for market segmentation.
