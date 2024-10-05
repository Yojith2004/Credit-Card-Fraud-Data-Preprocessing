# Credit-Card-Fraud-Data-Preprocessing

# Project Overview
This project is part of a larger initiative to build a credit card fraud detection system. My focus in this stage is on data collection, cleaning, preprocessing, and feature engineering, which will lay the foundation for building machine learning models to detect fraudulent transactions.

# Dataset Information
Source: The dataset contains simulated credit card transaction data from 1,000 customers and 800 merchants, spanning the period from 1st January 2019 to 31st December 2020. This data was generated using the Sparkov Data Generation Tool and accessed from Kaggle.
Details: The dataset consists of legitimate and fraudulent transactions, simulating real-world class imbalance in fraud detection.
Dataset Link: https://www.kaggle.com/datasets/kartik2112/fraud-detection

# Data Collection:
Accessed the dataset from Kaggle.
Loaded it into the workspace for further processing.

# Data Cleaning:
Removed duplicate records (if any).
Handled missing values (if any).
Identified and corrected data inconsistencies.

# Feature Engineering:
Transaction Time Features: Extracted new features such as the 'day of the week' and 'hour of the day' from the transaction timestamp to capture temporal patterns in fraudulent behavior.
Transaction Amount Scaling: Scaled the Amount feature for consistency and better model performance.
Transaction Frequency Features: Created features to measure the frequency of transactions for each customer and merchant.

# Data Normalization:
Applied scaling techniques to ensure uniformity across numerical features, which is essential for model training.

The dataset has been cleaned, transformed, and enriched with engineered features. This comprehensive preprocessing lays the groundwork for further analysis, including Exploratory Data Analysis (EDA), which will provide insights into transaction behaviors and highlight patterns relevant to fraud detection.
