🚀 Customer Segmentation using K-Means Clustering
📌 Overview

This project focuses on analyzing customer data to understand purchasing behavior and segment customers into meaningful groups using Machine Learning (K-Means Clustering).

The goal is to help businesses identify customer types and apply targeted marketing strategies.

🎯 Objective
Analyze customer demographics, income, and spending behavior
Identify similarities between customers
Segment customers into distinct groups
Provide business insights for better decision-making

As described in your project document, the system groups customers based on behavioral and demographic patterns to improve marketing efficiency

📊 Dataset Description

The dataset contains detailed customer information including:

👤 Demographics: Age, Education, Marital Status
💰 Financial Data: Annual Income
🏠 Household Info: Children, Teenagers
🛒 Spending Data: Wine, Fruits, Meat, Fish, Sweets, Gold
📢 Marketing Response: Campaign acceptance
🛍️ Purchase Channels: Web, Store, Catalog
🔍 Exploratory Data Analysis (EDA)

Key insights discovered:

📈 Income vs Spending → Strong positive correlation
👶 Customers with no children spend more
💑 Marital status has no impact on spending
🔄 Recency does not predict spending behavior
⚠️ Outliers removed for better model performance
⚙️ Feature Engineering

Created important features:

TotalSpent → Sum of all product category spending
TotalPurchases → Web + Store + Catalog purchases

These features significantly improved clustering performance.

🤖 Machine Learning Model
Algorithm Used:
K-Means Clustering (Unsupervised Learning)
Model Optimization:
Used Elbow Method to find optimal clusters
Optimal number of clusters: K = 4
👥 Customer Segments

The model identified 4 distinct customer groups:

🟣 Budget Customers
Low income, low spending
🔵 Conservative Customers
Moderate income, low engagement
🟢 Premium Customers (High Value)
High income, high spending
🟡 High-Potential Customers
Good income, moderate spending
📈 Model Performance
Clearly separated clusters
Strong similarity within groups
Silhouette Score improved after feature engineering (~0.48)

This confirms the model is reliable and effective.

💡 Business Impact
Identified 4 customer segments
Enabled targeted marketing strategies
Helped businesses:
Focus on high-value customers
Convert potential customers into premium buyers
Optimize marketing budget
🛠️ Tech Stack
Python
Pandas, NumPy
Scikit-learn
Matplotlib, Seaborn
Streamlit (for deployment)
🚀 Application

A Streamlit web app was developed to:

Input customer data
Predict customer segment
Visualize insights
⚠️ Challenges Faced
Data cleaning & preprocessing
Feature selection
Choosing optimal clusters
Interpreting customer behavior
Deploying ML model
📌 Conclusion

This project successfully demonstrates how unsupervised machine learning can be used to:

Understand customer behavior
Create meaningful segments
Improve business decision-making
👨‍💻 Author

Amarthya Nadh B (Amar)

Data Science Enthusiast
Machine Learning Developer
