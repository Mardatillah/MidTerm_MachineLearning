# Midterm Machine Learning - Customer Clustering

## Name
Jihan Nur Mardatillah

## NIM
1103223129

## Project Overview
This project aims to build an end-to-end machine learning pipeline for customer segmentation using clustering techniques. The project analyzes customer credit card usage behavior to group customers based on their purchasing activity, payment patterns, cash advance usage, and credit utilization.

## Dataset
- clusteringmidterm.csv

## Clustering Method Used
- K-Means Clustering

## Workflow
1. Data Loading
2. Exploratory Data Analysis (EDA)
3. Handling Missing Values
4. Removing Unnecessary Features
5. Feature Scaling using StandardScaler
6. Elbow Method for Optimal Cluster Selection
7. K-Means Clustering
8. PCA Visualization
9. Cluster Evaluation
10. Correlation Heatmap Analysis
11. Customer Cluster Interpretation

## Evaluation Metrics
- Silhouette Score
- Davies-Bouldin Index (DBI)

## Best Result
- Number of Clusters: 4
- Silhouette Score: 0.2485
- Davies-Bouldin Index: 1.4382

## Cluster Insights
- Cluster 0: Customers with high cash advance activity
- Cluster 1: Passive customers with low transaction activity
- Cluster 2: Premium customers with very high purchase activity
- Cluster 3: Active installment-based customers

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Google Colab
- GitHub

## Visualization
This project includes:
- Elbow Method Visualization
- PCA-based Cluster Visualization
- Correlation Heatmap

## Conclusion
The clustering model successfully segmented customers into four distinct groups based on their financial behavior. The evaluation results indicate that the clustering quality is reasonably good for customer behavioral data, with visually distinguishable customer segments and meaningful business insights.
