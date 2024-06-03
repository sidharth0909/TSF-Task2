# TSF-Task2

This project aims to identify the optimal number of clusters in the famous Iris dataset using the K-Means clustering algorithm. The Iris dataset consists of 150 samples of iris flowers with four features: sepal length, sepal width, petal length, and petal width. By applying the K-Means clustering algorithm, we can group similar data points together. The Elbow method is used to determine the optimal number of clusters, and the results are visualized for better understanding.

1. Libraries Import: The necessary libraries for data manipulation, clustering, and visualization are imported.
2. Data Loading: The Iris dataset is loaded using load_iris() from sklearn.datasets and stored in a DataFrame.
3. Data Standardization: The features are standardized using StandardScaler for better clustering performance.
4. Elbow Method: The Within-Cluster Sum of Squares (WCSS) is calculated for different numbers of clusters (1 to 10) to find the optimal number of clusters using the Elbow method.
5. K-Means Clustering: K-Means is applied to the dataset with the determined optimal number of clusters.
6. Visualization: The clusters and their centroids are visualized using scatter plots for two features of the dataset.
