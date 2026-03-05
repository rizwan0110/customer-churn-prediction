# Overview

This project focuses on predicting customer churn for an e-commerce spa business using machine learning models. The goal was to identify customers who are likely to stop purchasing and help the company design effective customer retention strategies.

The project was completed as part of the Machine Learning course in the AI Engineering Master's program at Jönköping University.

The study evaluates and compares multiple machine learning algorithms to determine which model performs best for churn prediction. 

# Business Problem

Customer churn is a major challenge for businesses because retaining existing customers is often more profitable than acquiring new ones. 

The aim of the project is to:

- Predict which customers are likely to churn

- Understand patterns in customer purchasing behavior

- Support data-driven customer retention strategies

The dataset was provided by Skogsro Spa, a Swedish spa business offering skincare products and spa services. 

# Data

Two datasets were used:

1. Order Dataset

- Customer ID
- Order ID
- Product information
- Purchase date
- Zip code

2. Product Dataset

- Product description
- Article number
- Price

The order dataset contained 14,257 unique customers and purchase data from 2013–2024. 


# Methodology

The project followed a standard machine learning workflow:

- Data Exploration
- Data Cleaning and Preprocessing
- Feature Engineering
- Handling Class Imbalance
- Model Training
- Model Evaluation

Several behavioral features were engineered, including:

- Total customer spending
- Purchase frequency 
- Number of products purchased 
- Product category preferences 
- Recency of purchases 
- Geographic segmentation
- Customer churn was defined as no purchase activity for more than 9 months. 

# Models Tested

- Logistic Regression
- Random Forest
- Gradient Boosting
- Support Vector Machine (SVM)

# Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

# Results

Among all models tested, Random Forest achieved the best overall performance.

Key results:
- Accuracy: ~84%
- AUC: ~0.86

The model successfully identified churn patterns based on customer spending and purchasing behavior. 


# Tools & Technologies

- Python
- Jupyter Notebook
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Excel

*The dataset and the code cannot be shared due to company confidentiality.*

