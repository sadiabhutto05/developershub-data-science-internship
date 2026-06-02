# Term Deposit Subscription Prediction using Machine Learning and SHAP Explainability

## Overview

This project focuses on predicting whether a bank customer will subscribe to a term deposit based on information collected during direct marketing campaigns. The objective is to develop and evaluate machine learning models that can help financial institutions identify potential customers who are more likely to subscribe to a term deposit product.

The project utilizes the Bank Marketing Dataset from the UCI Machine Learning Repository and applies various data preprocessing, exploratory data analysis, classification modeling, and explainable AI techniques to generate accurate and interpretable predictions.

---

## Problem Statement

Banks often conduct marketing campaigns to promote term deposit subscriptions. However, contacting every customer can be costly and inefficient. By analyzing customer demographic information, financial characteristics, and previous campaign interactions, machine learning models can help predict which customers are most likely to subscribe.

The goal of this project is to build predictive models that classify customers into two categories:

* Subscribe to a term deposit (Yes)
* Not subscribe to a term deposit (No)

Such predictions can assist banks in improving marketing efficiency, reducing operational costs, and increasing campaign success rates.

---

## Dataset Information

### Dataset Name

Bank Marketing Dataset

### Source

UCI Machine Learning Repository

### Description

The dataset contains customer information collected from direct marketing campaigns conducted by a Portuguese banking institution. Each record represents a customer and includes demographic, financial, and campaign-related attributes.

### Target Variable

**y**

* Yes → Customer subscribed to a term deposit
* No → Customer did not subscribe

### Key Features

* Age
* Job
* Marital Status
* Education
* Default Status
* Housing Loan
* Personal Loan
* Contact Type
* Campaign Duration
* Number of Contacts
* Previous Campaign Outcome
* Account Balance
* Month of Contact

---

## Project Workflow

### 1. Data Loading and Exploration

The dataset was loaded using Pandas and inspected to understand its structure, dimensions, feature types, and target distribution.

### 2. Data Cleaning and Preprocessing

The following preprocessing steps were performed:

* Handling missing values
* Removing duplicate records
* Encoding categorical variables
* Preparing features and target variables
* Splitting data into training and testing sets

### 3. Exploratory Data Analysis (EDA)

Several visualizations were created to gain insights into customer behavior and subscription patterns, including:

* Target class distribution
* Age distribution
* Job category analysis
* Loan and housing status analysis
* Correlation heatmaps
* Feature relationship visualizations

### 4. Model Development

Two classification algorithms were implemented:

#### Logistic Regression

A baseline linear classification model used to establish initial performance benchmarks.

#### Random Forest Classifier

An ensemble learning model capable of capturing complex relationships within the dataset and improving predictive accuracy.

### 5. Model Evaluation

Models were evaluated using multiple performance metrics:

* Accuracy Score
* Precision
* Recall
* F1 Score
* Confusion Matrix
* ROC Curve
* AUC Score

These metrics provide a comprehensive understanding of model performance, especially for imbalanced classification problems.

### 6. Explainable AI (XAI)

To improve model transparency and interpretability, SHAP (SHapley Additive exPlanations) was used.

SHAP helps explain:

* Why a prediction was made
* Which features contributed most to the prediction
* The positive and negative impact of each feature
* Individual customer-level prediction explanations

At least five individual predictions were analyzed using SHAP visualizations.

---

## Technologies and Libraries Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* SHAP

### Development Environment

* Google Colab / Jupyter Notebook

---

## Results

The machine learning models successfully predicted customer subscription behavior using historical marketing campaign data.

Key findings include:

* Campaign-related features significantly influence customer decisions.
* Previous campaign outcomes contribute strongly to prediction accuracy.
* Random Forest generally outperforms Logistic Regression due to its ability to model complex relationships.
* SHAP explanations provide valuable insights into feature importance and customer behavior patterns.

---

## Business Impact

The developed solution can assist banking institutions by:

* Identifying high-potential customers
* Improving marketing campaign efficiency
* Reducing unnecessary marketing costs
* Increasing conversion rates
* Supporting data-driven decision making
---

## Conclusion

This project demonstrates the application of machine learning and explainable AI techniques in the banking sector. By leveraging customer and campaign data, predictive models can effectively identify potential term deposit subscribers. The integration of SHAP explanations enhances model transparency, making the solution more trustworthy and actionable for business stakeholders.

The project highlights how data-driven decision-making can improve marketing effectiveness and contribute to better customer targeting strategies in financial institutions.
