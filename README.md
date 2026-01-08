Mall Customer Segmentation Using K-Means Clustering
Objective

The objective of this project is to segment mall customers into meaningful groups based on their annual income and spending behavior. The purpose of this segmentation is to support data-driven marketing strategies, improve customer targeting, and enhance customer retention.

Methodology

K-Means clustering was applied to identify distinct customer segments. The dataset includes customer demographics such as age, gender, annual income, and spending score.

The project followed these steps:

Data loading and inspection

Exploratory data analysis

Feature selection

Determining the optimal number of clusters using the Elbow Method

Applying K-Means clustering

Visualizing and interpreting customer segments

Data Exploration & Preprocessing

The dataset contains 200 customer records

No missing values were detected

Columns were renamed for clarity and consistency

Descriptive statistics were analyzed to understand feature distributions

Data Visualization

Pair plots were used to explore relationships between variables

Scatter plots were created to visualize income vs. spending behavior

Cluster visualizations highlighted distinct customer groups and centroids

Key Findings

The analysis identified five customer segments:

Low Income – Low Spending: Price-sensitive customers

Low Income – High Spending: Younger or impulsive spenders

Moderate Income – Moderate Spending: Average customers

High Income – Low Spending: Conservative high-income customers

High Income – High Spending: Premium and loyal customers

These segments provide actionable insights for targeted marketing and personalized offers.

Summary

This project demonstrates the application of unsupervised machine learning techniques for customer segmentation. Using Python, data preprocessing, clustering, and visualization, customers were grouped into five meaningful segments to support strategic marketing decisions.

Tools & Technologies

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Next Steps

Future improvements could include incorporating purchase history data, testing alternative clustering algorithms, and applying the model to real-world marketing scenarios.
