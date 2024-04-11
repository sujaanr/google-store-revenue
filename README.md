# Google Store Analytics Transactions Revenue Prediction

## Overview
This project is part of the GStore Revenue Prediction Challenge, aimed at analyzing the Google Merchandise Store customer dataset to predict revenue per customer. Utilizing data analysis and machine learning models, the project seeks to provide actionable insights for operational improvements and efficient marketing budget allocation.

## Structure and Contents
The Jupyter notebook is structured into several key sections, each focusing on different aspects of the data analysis and modeling process:

### Exploratory Data Analysis (EDA)
Initial analysis of the Google Store Revenue Dataset to understand the data's characteristics.
- **Dataset Information**
- **Device-related columns overview**
- **Dropping unnecessary columns for analysis**

### Feature Engineering
Techniques applied to create new features that could improve model performance.
- **Handling missing values**
- **Generating transaction-level and user-level datasets for modeling**

### Graph Analysis
Visual exploration of the data.
- **Revenue and country comparison graphs**
- **Aggregated and transaction-level insights**

### Modeling
Application of various machine learning models to predict revenue on both transaction and user levels.
- **LightGBM**
- **Ridge Regression Model**
- **Gradient Boost Model**
- **XGBoost Model**

### Customer Segmentation and LTV (Life Time Value) Prediction
- **Segmentation based on Recency, Frequency, and Monetary value**
- **LTV prediction using lightGBM**, including feature engineering to enhance model performance
