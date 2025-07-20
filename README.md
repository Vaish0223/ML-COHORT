# ML-COHORT
**WEEK 1 PROJECT: Perform EDA on a dataset + write insights(Jupyter/Collab Notebook)**
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

***Modeling***
(1)Applied KMeans Clustering after feature scaling
(2)Used Elbow Method and Silhouette Score to determine optimal clusters
(3)Final clusters revealed distinct purchasing behaviors among groups

**Results & Insights**
5 clusters identified: High spenders, average spenders, low-income frugal, etc.
Visualized clusters using 2D and 3D scatter plots
Insights help mall managers target each segment with tailored offers

**Tech Stack**
Python, Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn

Jupyter Notebook / Google Colab

***By Mentee- Vaishnavi Dixit- Amazon Summer School ML Cohort***
