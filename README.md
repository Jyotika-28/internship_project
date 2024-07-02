# Online-Retail-Customer-Segmentation



## Project Overview
The Online Retail Project involves analyzing customer data to identify distinct customer segments and profile them. The goal is to better understand customer behavior and provide insights for targeted marketing strategies.
## Features
Applied K-means clustering with the elbow method to identify the ideal number of clusters using within-cluster sum of squares (WCSS).
## Dataset
The dataset used for this project contains transactions from an online retail store. The data includes the following features:
**InvoiceNo**: Invoice number   
**StockCode**: Product (item) code   
**Description**: Product (item) name   
**Quantity**: The quantity of each product (item) per transaction   
**InvoiceDate**: Invoice date and time   
**UnitPrice**: Unit price (Product price per unit)   
**CustomerID**: Customer number   
**Country**: Country name   
## Project Steps
####  1. Data Preprocessing
+ Load the dataset and handle missing values.   
+ Clean and preprocess the data.   
+ Select relevant features for clustering.   

#### 2. Customer Segmentation
+ Standardize the features.   
+ Apply the KMeans clustering algorithm to segment the customers.   
+ Determine the optimal number of clusters using the elbow method.   

#### 3. Cluster Analysis
+ Assign cluster labels to the original dataset.   
+ Visualize the clusters using scatter plots.   
+ Calculate summary statistics (mean, median, standard deviation) for each cluster.   

#### 4. Customer Profiling
+ Create profiles for each customer segment based on the analysis.   
+ Describe the typical customer in each segment (e.g., demographics, purchasing behavior).   
+ Use box plots to illustrate the differences between segments.   
## Visualizations
The project includes various visualizations to understand and illustrate customer segments:   
+ Scatter plots colored by cluster labels to visualize the grouping of data points.   
+ Box plots to compare the distribution of features across clusters.   
## Results
The analysis provides insights into different customer segments, highlighting unique purchasing behaviors and characteristics of each segment. These insights can be used for targeted marketing and improving customer engagement strategies.
## Conclusion
The Online Retail Project demonstrates how clustering techniques can be applied to segment customers based on their purchasing behavior. By understanding different customer segments, businesses can tailor their marketing efforts to meet the specific needs of each segment.
## Authors
Jyotika Phalswal
