# CSRec-Customer-Segmentation-Recommendation-Engine
This project aims to create a pipeline for customer segmentation and recommendation systems using Python's data science tools like pandas and scikit-learn. It involves data cleaning, feature engineering, K-means clustering, and implementing a recommendation system. 
CSRec Aim:
Data Cleaning & Transformation: Clean the dataset by handling missing values, duplicates, and outliers, preparing it for effective clustering.

Feature Engineering: Develop new features based on the transactional data to create a customer-centric dataset, setting the foundation for customer segmentation.

Data Preprocessing: Undertake feature scaling and dimensionality reduction to streamline the data, enhancing the efficiency of the clustering process.

Customer Segmentation using K-Means Clustering: Segment customers into distinct groups using K-means, facilitating targeted marketing and personalized strategies.

Cluster Analysis & Evaluation: Analyze and profile each cluster to develop targeted marketing strategies and assess the quality of the clusters formed.

Recommendation System: Implement a system to recommend best-selling products to customers within the same cluster who haven't purchased those products, aiming to boost sales and marketing effectiveness.

They have Several Step::
Step 1 | Setup and Initialization

Step 1.1 | Importing Necessary Libraries
Step 1.2 | Loading the Dataset
Step 2 | Initial Data Analysis

Step 2.1 | Dataset Overview
Step 2.2 | Summary Statistics
![image](https://github.com/manishkk34/CSRec-Customer-Segmentation-Recommendation-Engine/assets/122711968/87ecfd7f-fc4d-4bbc-9e97-83222fd10606)


Step 3 | Data Cleaning & Transformation

Step 3.1 | Handling Missing Values
![image](https://github.com/manishkk34/CSRec-Customer-Segmentation-Recommendation-Engine/assets/122711968/224559a0-d36b-44f4-af84-de5c4e9eabb7)

Step 3.2 | Handling Duplicates
![image](https://github.com/manishkk34/CSRec-Customer-Segmentation-Recommendation-Engine/assets/122711968/ac3875f7-b53e-4bf1-821d-fc376194502b)

Step 3.3 | Treating Cancelled Transactions
Step 3.4 | Correcting StockCode Anomalies
Step 3.5 | Cleaning Description Column
Step 3.6 | Treating Zero Unit Prices
Step 3.7 | Outlier Treatment
Step 3.8 | Filter year > 2019
Step 3.9 | Question 2
Step 3.10 | Question 3
Step 4 | Feature Engineering

Step 4.1 | RFM Features
Step 4.1.1 | Recency (R)
Step 4.1.2 | Frequency (F)
Step 4.1.3 | Monetary (M)
Step 4.2 | Product Diversity
Step 4.3 | Behavioral Features
Step 4.4 | Geographic Features
Step 4.5 | Cancellation Insights
Step 4.6 | Seasonality & Trends
Step 5 | Outlier Detection and Treatment

Step 6 | Correlation Analysis

Step 7 | Feature Scaling

Step 8 | Dimensionality Reduction

Step 9 | K-Means Clustering

Step 9.1 | Determining the Optimal Number of Clusters
Step 9.1.1 | Elbow Method
Step 9.1.2 | Silhouette Method
Step 9.2 | Clustering Model - K-means
Step 10 | Clustering Evaluation

Step 10.1 | 3D Visualization of Top Principal Components
Step 10.2 | Cluster Distribution Visualization
Step 10.3 | Evaluation Metrics
Step 11 | Cluster Analysis and Profiling

Step 11.1 | Radar Chart Approach
Step 11.2 | Histogram Chart Approach
Step 12 | Recommendation System
