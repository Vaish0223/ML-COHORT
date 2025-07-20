# ML-COHORT
**WEEK 1 PROJECT: Perform EDA on a dataset + write insights(Jupyter/Collab Notebook)**

**🧭 Objective**
The primary goal of this project is to implement an unsupervised learning model—KMeans Clustering—to segment mall customers based on purchasing behavior and demographic characteristics. This segmentation aims to empower retailers with actionable insights for targeted marketing, inventory planning, and enhanced customer engagement.
**Dataset Description**
Source: Mall Customers Dataset
Size: 200 entries with 5 columns: CustomerID, Gender, Age, Annual Income, Spending Score
Missing Values: None
Preprocessing:
Dropped CustomerID
Encoded Gender
Scaled Income and Spending Score using StandardScaler

***EDA Highlights***
(1)Age and spending scores vary widely across genders
(2)Annual income is skewed towards the middle class
(3)Spending habits aren't always correlated with income
(4)Used histograms, boxplots, and scatter plots to identify trends and outliers

***🔍 Exploratory Data Analysis (EDA)***

-EDA was performed to uncover hidden patterns and prepare the dataset for clustering:
-Distribution Analysis: Age and income showed multi-modal distributions.
-Gender Trends: No major spending discrepancies, but slightly different spread in income.
-Spending Score Insight: Non-linear relationship with income and age.
-Scaling: Applied StandardScaler to normalize Annual Income and Spending Score.
-Visualizations: Boxplots, histograms, scatter plots, and pair plots helped uncover segment candidates.

**📈 Results & Insights**
The clustering algorithm identified five distinct customer segments, including:

Luxury Enthusiasts: High income, high spending score

Frugal Young Adults: Low income, moderate spending

Mid-income Savers: Moderate income, low spending

Impulsive Shoppers: Varied income, high spending score

Low Engagement Group: Low income, low spending score

These insights can help mall managers tailor experiences, discounts, and product recommendations based on customer behavior.
**Tech Stack**

Python, Pandas, NumPy
Scikit-learn
Matplotlib, Seaborn
Jupyter Notebook / Google Colab

**Key Learnings**

Importance of feature scaling in unsupervised models
Using elbow method and silhouette score effectively
Translating clustering output into actionable business strategies
Visual storytelling in ML projects

***By Mentee- Vaishnavi Dixit- Amazon Summer School ML Cohort***
