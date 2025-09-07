# Credit-Card-Fraud-Detection

# Project Overview
This project aims to detect fraudulent credit card transactions using machine learning techniques. Credit card fraud is a critical problem causing billions of dollars in losses annually. The project uses a publicly available dataset to build models that can distinguish between genuine and fraudulent transactions, thereby helping to prevent unauthorized charges.

# Dataset
The dataset used in this project is the "Credit Card Fraud Detection" dataset from Kaggle. It contains transactions made by European cardholders over two days in 2013. The dataset has 31 features with 284,807 transactions, of which 492 are fraudulent. Due to privacy concerns, most features are transformed by PCA, except for 'Time', 'Amount', and 'Class' (the target variable).

- Data Source: Kaggle - Credit Card Fraud Detection
- Features: 28 PCA components + Time + Amount
- Target: Class (1 = fraud, 0 = not fraud)

# Project Goals
- To analyze and visualize the dataset.
- To address class imbalance through techniques like undersampling or SMOTE.
- To build and evaluate multiple machine learning models for fraud detection.
- To compare models and choose the best performing one based on metrics like accuracy, precision, recall, and F1-score.

# Machine Learning Algorithms Used
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Decision Tree
- (Optional) Ensemble methods like Random Forest or XGBoost
