# ML-Clustering-Algorithms
# Clustering Algorithms: Iris Dataset

# Objective

This project demonstrates the application of clustering algorithms on the Iris dataset. The goal is to evaluate understanding and ability to apply clustering techniques, including KMeans and Hierarchical clustering, to real-world datasets.

# Dataset

The Iris dataset is a widely used dataset for machine learning and statistical analysis, comprising 150 samples of iris flowers, each described by four features:

Sepal Length

Sepal Width

Petal Length

Petal Width

For this project, the species column is excluded since clustering is an unsupervised learning task.

# Key Components

# 1. Loading and Preprocessing

The dataset is loaded from the sklearn library.

The target column (species) is excluded from the clustering task as this is an unsupervised learning problem.

# 2. Clustering Algorithms

# A. KMeans Clustering

Description: KMeans divides the dataset into k clusters by iteratively assigning points to the nearest cluster center and updating centers based on the mean of cluster points.

Why Suitable: The Iris dataset is well-structured and numeric, making it ideal for partition-based clustering.

# Implementation:

Applied KMeans with k=3 (based on known structure of Iris).

Visualized clusters using PCA for dimensionality reduction.

 # B. Hierarchical Clustering

Description: Hierarchical clustering builds a tree of clusters (dendrogram) by successively merging (or splitting) clusters based on distance.

Why Suitable: Provides interpretable and hierarchical cluster structures, effective for smaller datasets like Iris.

# Implementation:

Applied agglomerative clustering with ward linkage.

Visualized dendrogram and clusters using PCA.


Results

# KMeans Clustering:

Successfully grouped the dataset into 3 clusters.

Visualization using PCA confirmed distinct separations between clusters.

# Hierarchical Clustering:

Created a dendrogram illustrating hierarchical relationships.

Cluster visualization validated the clustering quality.

# Visualization

Clusters are visualized in 2D space using PCA for better interpretability.

Dendrogram displays hierarchical cluster relationships.

