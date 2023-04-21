# README File: Customer Segmentation using K-Means Clustering

## Introduction:
This project aims to perform customer segmentation on the given dataset using the K-Means clustering algorithm. The main goal of this analysis is to understand the different types of customers based on their spending patterns and income. This README file will guide you through the steps to be followed to complete this project.

## Dataset:
The dataset used for this project is 'Mall_Customers.csv', which can be found at the following link: https://github.com/ArinB/MSBA-CA-Data/raw/main/CA06/Mall_Customers.csv. The dataset contains information about customers, including customer ID, gender, age, annual income, and spending score.

## Tasks:
###1. Exploratory Data Analysis (EDA):
   a. Import the necessary libraries (pandas, numpy, matplotlib, seaborn)
   b. Load the dataset using pandas and display the first few rows
   c. Check for missing values and handle them appropriately
   d. Visualize the distribution of features using histograms or boxplots
### 2. Data Preparation:
   a. Perform any necessary feature scaling (StandardScaler or MinMaxScaler)
   b. Choose the appropriate features for clustering (you may start with 'Annual Income' and 'Spending Score')
   c. Create a new DataFrame with only the selected features
### 3. K-Means Clustering:
   a. Import the KMeans class from the sklearn.cluster module
   b. Use the Silhouette Method to determine the optimal number of clusters
   c. Train the KMeans model with the optimal number of clusters
   d. Obtain the cluster assignments for each data point
### 4. Visualize and Analyze the Clusters:
   a. Create a scatter plot of the selected features, colored by cluster assignment
   b. Interpret the clusters and provide a brief description of each cluster
   c. (Optional) Perform the same analysis with different sets of features and compare the results
### 5. Write a report summarizing your findings:
   a. Describe the dataset and its attributes
   b. Detail the steps taken for data preprocessing, feature selection, and scaling
   c. Explain the process of determining the optimal number of clusters
   d. Describe the clusters and their characteristics
   e. Discuss any insights or recommendations based on your analysis
