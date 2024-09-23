# Mall-Customer-Segmentation-Data
This project focuses on customer segmentation using the DBSCAN clustering algorithm to group mall customers based on their annual income and spending behavior. The objective is to identify distinct customer segments to enable businesses to tailor their marketing strategies to each segment's characteristics.

**Project Overview**

Customer segmentation is a key strategy in marketing to target specific groups of customers more effectively. In this project, we use DBSCAN (Density-Based Spatial Clustering of Applications with Noise) to group customers from the Mall Customer Segmentation Dataset based on their Annual Income and Spending Score.


**Key Features**

*DBSCAN Clustering*: Clustering customers based on density to identify key customer segments.

*Outlier Detection*: DBSCAN automatically detects customers who don't fit into any cluster (outliers).

*Visual Representation*: Scatter plots showing clusters based on customer spending behavior.


**Dataset**

The dataset used is Mall Customer Segmentation Data from Kaggle. It contains the following features:

*CustomerID*: Unique ID for each customer.

*Gender*: Gender of the customer.

*Age*: Age of the customer.

*Annual Income (k$)*: Annual income of the customer (in thousands of dollars).

*Spending Score (1-100)*: Score assigned by the mall based on customer spending habits.


**Key Insights**

*Distinct Segments*: DBSCAN identifies key customer segments based on income and spending, helping businesses tailor marketing strategies.

*Outlier Detection*: DBSCAN naturally detects customers who don't fit into any cluster, providing insights into unique or irregular customer behavior.

*Data-Driven Decisions*: Customer segmentation using income and spending allows businesses to understand high-value customers and target them more effectively.

**Results**

The DBSCAN algorithm successfully clusters the mall customers into distinct groups:

High-income, low-spending customers.

Low-income, high-spending customers.

Moderate spenders across all income levels.

Outliers representing customers who don't follow typical spending patterns.

**Visualization**

A sample scatter plot showing Annual Income vs. Spending Score for mall customers, color-coded by cluster, is included to help visualize the results.
