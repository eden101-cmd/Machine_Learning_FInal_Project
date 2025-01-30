# Bus Routes Analysis in Israel - 2024

## Overview

This project analyzes bus route data in Israel for the year 2024. It focuses on both supervised and unsupervised learning methods to classify bus routes by metropolitan areas and to cluster routes based on similar characteristics. The goal is to optimize public transportation management by leveraging data-driven insights.

## Project Objectives

#### Supervised Learning:
Problem: Assign bus routes to specific metropolitan areas based on unique route attributes such as origin city, destination city, service type, operating times, and passenger traffic.    
Goal: Develop a classification model to predict the metropolitan area for each bus route and enable optimized management for each region.

#### Unsupervised Learning:
Problem: Understand bus operations under varying conditions, including peak hours, passenger traffic, and operational constraints.    
Goal: Identify clusters of bus routes with similar characteristics to improve resource allocation and operational efficiency.

## Dataset

The dataset, sourced from Data.gov.il, includes information on all bus routes in Israel for the year 2024. The dataset contains:
53 Features for each record.
10,679 Records in total.

## Methodology

#### Supervised Learning:
Implemented five classification models to predict metropolitan areas:
- Random Forest
- Gradient Boosting
- Logistic Regression
- Support Vector Classifier (SVC)
- K-Nearest Neighbors (KNN)

#### Unsupervised Learning:
Focused on clustering routes within the Gush Dan metropolitan area:
Preprocessing: Standardized numerical features and reduced dimensionality using PCA.
Clustering Models:
- K-Means with Elbow Method and Silhouette Score for evaluation.
- Gaussian Mixture Model (GMM) with BIC, AIC, and Silhouette Score.

## Files Included

data/: Cleaned dataset used for analysis.     
code/: Python scripts for data preprocessing, feature engineering, model training, and evaluation.     
Outputs/: Output files, including metrics, visualizations, and cluster summaries.     

## Contributors

Marina Nezhelsky     
Eden Cohen



