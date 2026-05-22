# Ecommerce Customer Segmentation System

Developed an end-to-end unsupervised Machine Learning system to intelligently segment e-commerce customers based on purchasing behaviour, engagement activity, and demographic patterns. The project focuses on discovering hidden customer groups to support personalized marketing strategies, customer retention, and business-driven decision making.

---

## Project Overview

SmartCart is a growing e-commerce platform that serves customers across multiple regions. The company collected customer demographic information, purchase history, website interaction data, and engagement metrics. However, the platform was using generic marketing strategies for all customers without understanding different customer behaviour patterns.

To solve this problem, an AI-driven customer segmentation system was developed using clustering algorithms to group similar customers into meaningful categories based on spending behaviour, income, engagement, and purchasing activity.

The system helps businesses:
- Identify high-value customers
- Improve targeted marketing campaigns
- Understand customer purchasing behaviour
- Detect low-engagement customers
- Support personalized recommendations
- Improve customer retention strategies

---

# Dataset Description

The dataset contains customer-related information including:
- Demographic details
- Household income
- Education level
- Marital status
- Product spending behaviour
- Purchase frequency
- Website activity
- Customer engagement metrics

The dataset includes over 2200 customer records and multiple behavioural attributes used for customer analysis and segmentation.

---

# Project Workflow

## Data Preprocessing

Performed extensive data cleaning and preprocessing to prepare the dataset for clustering analysis. Missing values were handled using statistical imputation techniques, and unnecessary attributes were removed to improve model efficiency.

Outlier detection and removal techniques were applied to eliminate abnormal customer records that could negatively affect clustering performance.

---

## Feature Engineering

Created meaningful business-driven features to improve clustering quality and behavioural analysis. New features were engineered to capture:
- Total customer spending
- Customer age
- Household composition
- Customer engagement behaviour

These engineered features helped in identifying meaningful behavioural patterns among customers.

---

## Exploratory Data Analysis (EDA)

Performed detailed exploratory data analysis to understand customer behaviour and identify trends in spending patterns, income distribution, and purchasing habits.

Various visualizations were used to analyze:
- Correlations between features
- Income and spending behaviour
- Customer activity distribution
- Purchase behaviour trends

EDA helped in identifying important behavioural insights before clustering.

---

## Data Encoding and Scaling

Categorical variables such as education level and relationship status were transformed into numerical representations using encoding techniques.

Feature scaling was applied to normalize numerical attributes and ensure that all features contributed equally during clustering.

---

## Dimensionality Reduction

Applied Principal Component Analysis (PCA) to reduce feature dimensionality and improve visualization of customer clusters. PCA helped simplify the dataset while preserving important behavioural information.

Both 2D and 3D visualizations were generated to better understand customer group separation.

---

# Clustering Techniques Used

## K-Means Clustering

Implemented K-Means clustering to divide customers into distinct behavioural groups based on similarities in purchasing patterns and engagement metrics.

The optimal number of clusters was determined using:
- Elbow Method
- Silhouette Score Analysis

---

## Agglomerative Clustering

Applied hierarchical clustering techniques using Agglomerative Clustering to compare clustering performance and analyze hierarchical relationships between customer groups.

---

# Cluster Analysis

Performed detailed analysis of generated customer clusters to understand:
- Spending behaviour
- Income patterns
- Customer engagement
- Purchase frequency
- Loyalty indicators

Clusters were visualized using multiple plotting techniques to identify high-value and low-engagement customer segments.

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# Key Features

- Intelligent customer segmentation
- Behavioural pattern analysis
- Feature engineering pipeline
- Outlier handling
- PCA dimensionality reduction
- K-Means clustering
- Agglomerative clustering
- Cluster visualization
- Marketing insight generation

---

# Project Outcome

Successfully developed an AI-powered customer segmentation system capable of discovering hidden customer behaviour patterns and grouping similar customers into meaningful clusters. The project supports personalized marketing strategies, customer retention analysis, and business-driven decision making through data-driven customer insights.

---

# Future Enhancements

- Real-time customer segmentation
- Customer recommendation system
- Customer churn prediction
- Deployment as a web application
- Integration with marketing automation systems

---


AI/ML Enthusiast | Machine Learning | Data Science | Python Developer