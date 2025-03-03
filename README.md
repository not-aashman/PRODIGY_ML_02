# PRODIGY_ML_02: K-Means Clustering for Customer Segmentation

## Task Overview
This repository contains the implementation of the **K-Means clustering algorithm** to segment customers of a retail store based on their **purchase history**. The task was performed as part of the **Machine Learning Internship Program** at **Prodigy InfoTech**.

## Dataset
The dataset used for this task is the **Customer Segmentation Dataset** from Kaggle. The dataset can be found [here](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python).

### Dataset Features:
- **Gender**: Gender of the customer (encoded as 0 for Male and 1 for Female).
- **Age**: Age of the customer.
- **Annual Income (k$)**: The annual income of the customer in thousands of dollars.
- **Spending Score (1-100)**: A score assigned to the customer based on their purchase behavior.

## Task Description
The task involved implementing the **K-means clustering algorithm** to group customers based on the input features:
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

### Steps Performed:
1. **Data Preprocessing**:
   - Loaded and cleaned the dataset.
   - Encoded the **Gender** feature and handled missing data.
   - Scaled the features to normalize the values for better clustering.

2. **K-Means Clustering**:
   - Implemented the **K-means algorithm** using scikit-learn.
   - Used the **Elbow method** to determine the optimal number of clusters.

3. **Cluster Analysis**:
   - Analyzed the resulting clusters and understood the characteristics of each group.
   - Visualized the clusters using a 2D scatter plot to interpret the customer segments.

## Results:
The dataset was successfully segmented into distinct customer groups based on their purchasing behaviors. The clusters provided valuable insights into different customer profiles, which can be used for targeted marketing or customer service optimization.

### Cluster Analysis:
- **Cluster 0**: Customers with higher spending scores and higher income.
- **Cluster 1**: Customers with low income but high spending scores.
- **Cluster 2**: Customers with low spending scores and lower income.
- **Cluster 3**: Customers with medium spending scores and medium income.

## Model Performance:
The clustering analysis was successful in identifying meaningful customer segments. No specific performance metrics like accuracy or MSE are applicable to unsupervised learning problems such as clustering.
