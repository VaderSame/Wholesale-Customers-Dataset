# Wholesale Customers Dataset Analysis

## Table of Contents

- [Overview](#overview)
- [Exploratory Data Analysis (EDA) and Data Cleaning](#exploratory-data-analysis-eda-and-data-cleaning)
- [Feature Scaling](#feature-scaling)
- [Feature Selection using Recursive Feature Elimination with Cross-Validation (RFECV)](#feature-selection-using-recursive-feature-elimination-with-cross-validation-rfecv)
- [K-Means Clustering](#k-means-clustering)
- [Principal Component Analysis (PCA)](#principal-component-analysis-pca)
- [XGBoost Classifier with Cross-Validation](#xgboost-classifier-with-cross-validation)
- [Tools and Libraries](#tools-and-libraries)

## Overview

This project involves a comprehensive analysis of the Wholesale Customers Dataset, a dataset containing customers' annual spending on various product categories, along with categorical variables for channel and region. The project encompasses various tasks, including data cleaning, feature scaling, feature selection, K-Means clustering, Principal Component Analysis (PCA), and classification using XGBoost. Each task contributes to a thorough understanding of the dataset and prepares it for modeling and analysis.

## Exploratory Data Analysis (EDA) and Data Cleaning

- Exploratory Data Analysis (EDA) was conducted to gain insights into the dataset's structure, distribution, and potential anomalies.
- Data cleaning was performed to address missing values and data anomalies.

## Feature Scaling

- Feature scaling was applied to normalize the data, making it suitable for machine learning algorithms.
## Feature Selection using Recursive Feature Elimination with Cross-Validation (RFECV)

- RFECV was employed to identify the optimal number of features for modeling.
- A plot was generated to visualize the relationship between the number of features selected and cross-validation scores.

## K-Means Clustering

- K-Means clustering was applied across a range of K values, spanning from 2 to 15.
- The elbow method was used to determine the optimal number of clusters for the dataset.

## Principal Component Analysis (PCA)

- Principal Component Analysis (PCA) was utilized to reduce the dimensionality of the dataset.
- Variance analysis was conducted to understand the explanatory power of the first 2 and first 4 components.
- Cluster visualization post-PCA was performed.

## XGBoost Classifier with Cross-Validation

- An XGBoost Classifier with 5-fold cross-validation was implemented for classification tasks.
- Performance metrics were reported to assess the classifier's performance.

## Tools and Libraries

The project was executed using Python, with the support of widely-adopted machine learning libraries, including scikit-learn, matplotlib, and XGBoost.

For detailed code and results associated with each task, please refer to the project files.
