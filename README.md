# About the Project: Segmentation-and-Recommender-System-for-Clients

![1685441742313](https://github.com/3liodeh/Segmentation-and-Recommender-System-for-Clients/assets/109085886/b828e828-9396-40bd-bc55-9f3dc373a0a2)

Problem: In this project, we delve deep into the thriving sector of online retail by analyzing a transactional dataset from a UK-based retailer, available at the UCI Machine Learning Repository. This dataset documents all transactions between 2010 and 2011. Our primary objective is to amplify the efficiency of marketing strategies and boost sales through customer segmentation. We aim to transform the transactional data into a customer-centric dataset by creating new features that will facilitate the segmentation of customers into distinct groups using the K-means clustering algorithm. This segmentation will allow us to understand the distinct profiles and preferences of different customer groups. Building upon this, we intend to develop a recommendation system that will suggest top-selling products to customers within each segment who haven't purchased those items yet, ultimately enhancing marketing efficacy and fostering increased sales.

Objectives: Data Cleaning & Transformation: Clean the dataset by handling missing values, duplicates, and outliers, preparing it for effective clustering. Feature Engineering: Develop new features based on the transactional data to create a customer-centric dataset, setting the foundation for customer segmentation. Data Preprocessing: Undertake feature scaling and dimensionality reduction to streamline the data, enhancing the efficiency of the clustering process. Customer Segmentation using K-Means Clustering: Segment customers into distinct groups using K-means, facilitating targeted marketing and personalized strategies. Cluster Analysis & Evaluation: Analyze and profile each cluster to develop targeted marketing strategies and assess the quality of the clusters formed. Recommendation System: Implement a system to recommend best-selling products to customers within the same cluster who haven't purchased those products, aiming to boost sales and marketing effectiveness.

- Step 1 | Setup and Initialization
    - Step 1.1 | Importing Necessary Libraries
    - Step 1.2 | Loading the Dataset (load_dataset)
- Step 2 | Initial Data Analysis (initial_analysis)
    - Step 2.1 | Dataset Overview (overview)
    - Step 2.2 | Summary Statistics (statistics)
- Step 3 | Data Cleaning & Transformation (data_cleaning)
    - Step 3.1 | Handling Missing Values (missing_values)
    - Step 3.2 | Handling Duplicates (duplicates)
    - Step 3.3 | Treating Cancelled Transactions (InvoiceNo_cleaning)
    - Step 3.4 | Correcting StockCode Anomalies (StockCode_cleaning)
    - Step 3.5 | Cleaning Description Column (Description_cleaning)
    - Step 3.6 | Treating Zero Unit Prices (UnitPrice_cleaning)
    - Step 3.7 | Outlier Treatment (outlier_cleaning)
- Step 4 | Feature Engineering (feature_engineering)
    - Step 4.1 | RFM Features (rfm_features)
        - Step 4.1.1 | Recency (R) (recency)
        - Step 4.1.2 | Frequency (F) (frequency)
        - Step 4.1.3 | Monetary (M) (monetary)
    - Step 4.2 | Product Diversity (product_diversity)
    - Step 4.3 | Behavioral Features (behavioral_features)
    - Step 4.4 | Geographic Features (geographical_features)
    - Step 4.5 | Cancellation Insights (cancellation_insights)
    - Step 4.6 | Seasonality & Trends (seasonality_trends)
- Step 5 | Outlier Detection and Treatment (outlier_detection)
- Step 6 | Correlation Analysis (correlation)
- Step 7 | Feature Scaling (scaling)
- Step 8 | Dimensionality Reduction (pca)
- Step 9 | K-Means Clustering (kmeans)
    - Step 9.1 | Determining the Optimal Number of Clusters (optimal_k)
        - Step 9.1.1 | Elbow Method (elbow)
        - Step 9.1.2 | Silhouette Method
    - Step 9.2 | Clustering Model - K-means
- Step 10 | Clustering Evaluation
    - Step 10.1 | 3D Visualization of Top Principal Components
    - Step 10.2 | Cluster Distribution Visualization
    - Step 10.3 | Evaluation Metrics
- Step 11 | Cluster Analysis and Profiling
    - Step 11.1 | Radar Chart Approach
    - Step 11.2 | Histogram Chart Approach
- Step 12 | Recommendation System
