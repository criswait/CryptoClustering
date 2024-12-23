# Cryptocurrency Clustering with K-Means and PCA

This project involves clustering cryptocurrencies based on their performance metrics using K-Means clustering and Principal Component Analysis (PCA). The analysis contrasts results from the original dataset and the PCA-transformed dataset to explore the impact of dimensionality reduction.

# Project Workflow
1. Data Preparation
- Dataset: Cryptocurrency market data.
- Preprocessing:
  - Standardized the data using StandardScaler to normalize features.
  - Prepared the dataset for clustering analysis.

2. Elbow Method (Original Data)
- Generated inertia values for K values ranging from 1 to 11.
- Plotted the Elbow Curve to determine the optimal number of clusters (“K”).
- Identified K = 4 as the optimal number of clusters.

3. K-Means Clustering (Original Data)
- Applied K-Means with K = 4 to the original scaled data.
- Added cluster labels to the dataset.
- Visualized the clusters using a scatter plot.

4. Principal Component Analysis (PCA)
- Reduced the original dataset to 3 principal components.
- Retained 89.5% of the total variance.

5. Elbow Method (PCA Data)
- Repeated the Elbow Method for the PCA-transformed data.
- Plotted the Elbow Curve and confirmed K = 4 as the optimal number of clusters.

6. K-Means Clustering (PCA Data)
- Applied K-Means with K = 4 to the PCA-transformed data.
- Added cluster labels to the PCA dataset.
- Visualized the clusters using a scatter plot.

7. Comparison
- Created composite plots to contrast the Elbow Curves and scatter plots from the original and PCA data.
- Observed similar clustering results with both datasets, highlighting the effectiveness of PCA in dimensionality reduction.


# Key Findings

# Optimal Number of Clusters: Using the Elbow Method, K = 4 was identified as the best choice for both datasets.

PCA Impact:
- PCA significantly reduced dimensionality while retaining most information.
- Results were computationally efficient and visually interpretable.
- Cluster assignments were consistent with the original data.

Clustering Insights:
- Cryptocurrencies were grouped based on similarities in their price change metrics over various timeframes.


## Conclusion

Using PCA to reduce dimensionality enhanced computational efficiency and maintained clustering accuracy. This project demonstrates the effectiveness of combining K-Means with PCA for clustering high-dimensional data in a real-world cryptocurrency dataset.

