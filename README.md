
# Streaming Service Customer Data Analysis using Machine Learning

## Overview

This project applies machine learning techniques to analyze customer behavior in a streaming service platform. The objective is to understand the factors influencing **customer spending and churn** using predictive modelling and clustering techniques.

The project explores several supervised and unsupervised machine learning models to extract insights from customer data and support data-driven decision-making.

---

## Objectives

The main goals of this project are:

* Predict customer **monthly spending** using regression models
* Identify **customers likely to churn** using classification models
* Discover **customer segments** using clustering techniques
* Compare the performance of different machine learning models

---

## Dataset

The dataset contains customer information from a streaming service platform, including features such as:

* Age
* Subscription length
* Satisfaction score
* Support tickets raised
* Payment method
* Region
* Last activity

These features were used to analyze customer behavior and predict spending patterns.

---

## Methodology

### 1. Regression Models

Regression models were used to predict **monthly spending**.

The following models were evaluated:

* Linear Regression
* Polynomial Regression
* Multiple Linear Regression
* Neural Network (MLP)
* Random Forest Regression

The **Random Forest model performed best**, achieving:

* **R² = 0.74**
* **RMSE = 4.89**

indicating strong predictive capability for customer spending. 

---

### 2. Classification Models

Classification models were trained to predict **customer churn**.

Models tested:

* Logistic Regression
* Random Forest Classifier
* Neural Network Classifier

The **Random Forest classifier achieved the best performance**, with:

* **Accuracy: 85%**
* **ROC-AUC: 0.92** 

This indicates strong capability in identifying customers likely to cancel their subscription.

---

### 3. Clustering Analysis

Unsupervised learning techniques were used to identify customer segments.

Algorithms implemented:

* K-Means Clustering
* Hierarchical Clustering

Using evaluation metrics such as **Silhouette Score**, the optimal number of clusters was determined to be **four distinct customer segments**. 

These clusters revealed different types of users with varying spending patterns and churn risks.

---

## Key Insights

* Customer **satisfaction score** is the most influential factor affecting spending.
* Combining multiple features significantly improves prediction accuracy.
* Machine learning models can effectively identify customers at risk of churn.
* Clustering analysis reveals distinct customer segments that can support targeted marketing strategies.

---

## Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn
* TensorFlow / Keras
* Matplotlib / Seaborn

---

## Applications

The methods demonstrated in this project can be applied to:

* Customer retention strategies
* Marketing optimization
* Personalized recommendations
* Subscription revenue forecasting

---

## Future Work

Potential improvements include:

* Advanced feature engineering
* Ensemble modelling techniques
* Real-time churn prediction systems
* Integration with recommendation systems

---

## Author
Majid Rasheed
MSc Artificial Intelligence & Data Science
University of Hull

Research interests include:

* Machine Learning
* Data Science
* Predictive Analytics
* AI-driven decision systems

---
