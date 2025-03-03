# Customer Segmentation using K-Means Clustering

This repository implements a K-means clustering algorithm to segment retail customers based on their purchase history. The goal is to group customers into clusters with similar behaviors for targeted marketing.

## Dataset

The dataset used for this task is the [Customer Segmentation Dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python), which contains the following columns:

- **Gender**: Gender of the customer
- **Age**: Age of the customer
- **Annual Income (k$)**: Annual income of the customer in thousands
- **Spending Score (1-100)**: Spending score assigned to the customer based on their purchase behavior

## Steps

1. **Data Preprocessing**:
   - Load and clean the dataset.
   - Encode categorical variables (if applicable).
   - Normalize features to ensure uniform scale.

2. **K-means Clustering**:
   - Implement the K-means algorithm.
   - Determine the optimal number of clusters using the Elbow method.
   - Fit the model and assign customers to clusters.

3. **Cluster Analysis**:
   - Analyze the clusters based on centroids and customer characteristics (e.g., Age, Income, Spending Score).
   - Visualize the clusters using 2D plots.

## Results

The dataset was successfully segmented into distinct customer groups, providing insights into different purchasing behaviors. These insights can be used for targeted marketing campaigns or improving product offerings.
