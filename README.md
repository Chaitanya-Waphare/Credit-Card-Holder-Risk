# Credit-Card-Holder-Risk
# Credit Card Fraud Detection Project

## Overview
This project focuses on detecting fraudulent activities in a credit card dataset using Principal Component Analysis (PCA) and various clustering techniques. By applying unsupervised learning methods, we aim to uncover hidden patterns and identify anomalies that may indicate potential fraud.

## Project Structure
- `PCA`: A Notebook to Understand the PCA Algorithm
- `CreditCardFraudDetection_PCA_Clustering.py`: Main Python script for data preprocessing, PCA, and clustering analysis.
- `Customer_Data.csv`: Dataset used for the project (not included in the repository for privacy reasons).

## Data Preprocessing

  -`Loading Data`: The dataset is loaded from a CSV file.
  
  -`Handling Missing Values`: Missing values are replaced with the respective column means.
  
  -`Standardization: Data is` standardized to ensure each feature contributes equally to the analysis.

## Principal Component Analysis (PCA)

  -`Dimensionality Reduction`: PCA is performed to reduce the dimensionality of the dataset.
  
  -`Explained Variance`: The explained variance ratio is calculated to determine the number of principal components to retain.
  
  -`Biplot`: A biplot is created to visualize the relationship between the principal components and the original features.

## Clustering Analysis
# KMeans Clustering

  -`Optimal Number of Clusters`: The Elbow method and Silhouette method are used to determine the optimal number of clusters.
  
  -`Clustering`: KMeans clustering is performed, and the results are visualized.

# Density-Based Clustering (DBSCAN)

  -`k-distance Graph`: The optimal eps value is identified using the k-distance graph.
  
  -`Clustering`: DBSCAN is applied to the dataset to identify core samples and noise.

# Model-Based Clustering (Gaussian Mixture Model)

  -`Probabilistic Clustering`: The Gaussian Mixture Model is used for probabilistic clustering, estimating the distribution of the data and classifying observations into clusters.

# Visualizations

  -`Scatter Plots`: Visualizations are created to show the clustering results for each method, helping in understanding the distribution of the data and identifying potential fraud clusters.

## Conclusion

The combination of PCA and various clustering techniques provided a comprehensive approach to understanding and detecting potential fraudulent activities in the credit card dataset. The insights gained from the clustering analysis can be used to develop targeted strategies for fraud prevention and enhance the overall security of credit card transactions.
Key Insights

  -PCA reduced the dimensionality of the data while retaining the most important features.
  
  -KMeans Clustering provided clear partitioning of the dataset into distinct clusters.
  
  -DBSCAN effectively identified outliers and anomalies, crucial for fraud detection.
  
  -The Gaussian Mixture Model added a probabilistic perspective to clustering, offering a flexible and nuanced classification of the data.
