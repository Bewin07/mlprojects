🩺 Insurance Claim Prediction
📘 Overview

Insurance companies face the critical challenge of predicting claim amounts accurately to optimize pricing and manage financial risk. This project focuses on predicting insurance claim amounts using various factors such as age, BMI, smoking habits, and medical conditions. By applying machine learning techniques, we aim to build an automated and accurate claim prediction system.

🎯 Problem Statement

A key challenge for the insurance industry is determining an appropriate premium for each customer based on their risk profile. Incorrect estimation can lead to:

Financial loss for the company

Unfair premiums for customers

This project aims to predict the claim amount of a policyholder using health and demographic attributes to enable data-driven decision-making in insurance pricing.

Approach :
  1. Data Preprocessing
  
  Handling missing values
  
  Encoding categorical variables
  
  Outlier detection and treatment
  
  Feature scaling
  
  2. Exploratory Data Analysis (EDA)
  
  Statistical summary and correlation heatmap
  
  Relationship between BMI, smoking habits, and claim amount
  
  Visual analysis of health and demographic patterns
  
  3. Model Development
  
  Train-test split
  
  Regression algorithms used:
  
  Linear Regression
  
  Decision Tree Regressor
  
  Random Forest Regressor
  
  XGBoost Regressor
  
  4. Model Evaluation
  
  Metrics used:
  
  Mean Absolute Error (MAE)
  
  Mean Squared Error (MSE)
  
  R² Score

Model comparison to select the best-performing algorithm

📊 Key Insights

Smokers tend to have significantly higher claim amounts.

BMI and age are strong predictors of insurance cost.

Regular exercise and non-smoking habits contribute to lower claims.

Random Forest or XGBoost achieved the best performance among tested models.

💻 Technologies Used

Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost

Environment: Jupyter Notebook
