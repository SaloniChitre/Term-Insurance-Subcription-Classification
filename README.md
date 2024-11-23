# Classification Project: Bank Marketing Dataset

## Overview
This project involves the implementation and evaluation of multiple machine learning algorithms to predict whether a customer will subscribe to a term deposit (`Yes` or `No`). The dataset used is the **Bank Marketing Dataset**, and the algorithms analyzed include:
-**Logistic Regression**
- **Naive Bayes**
- **KNN**
-**Decision Tree**
- **Random Forest**
- **XGBoost**

The goal of the project is to compare the performance of these models using metrics such as **Accuracy**, **Precision**, **Recall**, **F1-Score**, and **ROC-AUC**, and identify the best-performing algorithm.

---

## Dataset Description
The **Bank Marketing Dataset** consists of data collected from direct marketing campaigns of a Portuguese banking institution. The target variable is `y`, which indicates whether a customer subscribed to a term deposit.

### Key Features
- `age`: Age of the client.
- `job`: Type of job (e.g., admin, technician, etc.).
- `marital`: Marital status.
- `duration`: Last call duration in seconds.
- `pdays`: Number of days since last client contact.
- `nr.employed`: Number of employees in the economy.
- `cons.conf.idx`: Consumer confidence index.
- Target (`y`): Binary classification (`Yes` or `No`).

### Dataset Size
- **41,188 rows** and **21 columns**.

---

## Project Workflow
1. **Data Preprocessing**
   - Handled missing values.
   - Encoded categorical variables using one-hot encoding.
   - Standardized numerical features to improve model performance.
   - Split the data into training (70%) and testing (30%) sets.

2. **Model Implementation**
   - **Naive Bayes**:
     - Probabilistic classifier based on Bayes' Theorem with the assumption of feature independence.
   - **Random Forest**:
     - An ensemble model using multiple decision trees with majority voting for classification.
   - **XGBoost**:
     - A gradient boosting algorithm optimized for speed and performance.

3. **Model Evaluation**
   - Evaluated using the following metrics:
     - **Accuracy**
     - **Precision**
