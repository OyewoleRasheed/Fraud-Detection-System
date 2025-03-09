# **Credit Card Fraud Detection Using Machine Learning**  

This project aims to develop an efficient and accurate fraud detection system using machine learning techniques on a credit card transaction dataset from Kaggle. Credit card fraud is a significant financial threat, making early and precise detection critical for minimizing losses and enhancing security.  

## **Project Overview**  
The dataset consists of anonymized credit card transactions labeled as fraudulent or non-fraudulent. Given the highly imbalanced nature of the data, with fraudulent transactions being a small fraction of the total, specialized techniques such as oversampling, undersampling, and anomaly detection are applied to improve model performance.  

## **Machine Learning Models Used**  
Several classification models are trained and evaluated, including:  
- **Random Forest**  
- **XGBoost**  
- **Gradient Boosting**  
- **Logistic Regression**  

To assess model performance, a confusion matrix is utilized, with a strong emphasis on minimizing false negatives (fraud cases misclassified as non-fraud). The Random Forest model demonstrated the best performance, achieving the lowest false positive rate, thereby minimizing financial risk while accurately identifying fraudulent transactions.  

## **Key Features**  
- **Data Preprocessing**: Checking for missing values, standardizing, splitting dataset into test and train.  
- **Prediction**: ETraining the models and making predictions.  
- **Model Evaluation**: Using precision, recall, F1-score, and confusion matrix analysis.  
- **Risk Minimization**: Prioritizing models that reduce false negatives to prevent financial losses.  

This project serves as a foundation for deploying real-time fraud detection systems in financial institutions, ensuring enhanced transaction security and fraud prevention.
