# Bank Marketing Predictive Analysis

## 📌 Project Overview

This project focuses on predicting whether a customer of a Portuguese banking institution will subscribe to a **term deposit** based on historical direct marketing campaign data.

The objective is to build and evaluate machine learning models that can help the bank optimize **marketing strategies**, reduce unnecessary calls, and improve customer conversion rates.

--------------------------------------------------------------------------

## 📊 Dataset Description

The dataset was created by **Paulo Cortez** and **Sérgio Moro (2012)** and contains data collected from **phone-based marketing campaigns** conducted between **May 2008** and **November 2010**.

The goal is to predict the output variable:

y → Whether the client subscribed to a term deposit (**"yes"** or **"no"**)

--------------------------------------------------------------------

## 🗂 Dataset Files

- **bank.csv** → Random sample (10%) of the dataset used for model training & testing

--------------------------------------------------------------------------

## 📋 Key Features
| **Feature**   | **Description**                                      |
| ------------- | ---------------------------------------------------- |
| **Age**       | Customer’s age                                       |
| **Job**       | Type of job                                          |
| **Marital**   | Marital status                                       |
| **Education** | Education level                                      |
| **Default**   | Credit default status                                |
| **Balance**   | Yearly account balance                               |
| **Housing**   | Housing loan status                                  |
| **Loan**      | Personal loan status                                 |
| **Contact**   | Contact communication type                           |
| **Campaign**  | Number of contacts performed in the current campaign |
| **Pdays**     | Days passed since the client was last contacted      |
| **Previous**  | Number of previous campaign contacts                 |
| **Poutcome**  | Outcome of the previous marketing campaign           |
| **Duration**  | Call duration (strong predictive feature)            |

There are **no** missing values in the dataset.

-------------------------------------------------------------------------------

## 🎯 Problem Statement

Predict whether a client will subscribe to a **term deposit**, helping financial institutions make data-driven decisions for marketing and customer engagement.

----------------------------------------------------------------------------------

## 🧠 Approach & Methodology

 1. **Data Preprocessing**

 - Handled categorical encoding

 - Normalized numeric features

 - Feature selection for best performance

2. **Exploratory Data Analysis (EDA)**

 - Analyzed patterns between customer demographics and subscriptions

 - Identified key drivers like call duration and previous campaign success

3. **Model Building**

Trained and compared the following algorithms:

 - Logistic Regression

 - Decision Trees

 - Naive Bayes

 - Support Vector Machine

 - K-Nearest Neighbors

 - Random Forest

 - Gradient Boosting

 - Extreme Gradient Boosting (XGBoost)

4. **Model Evaluation**
Evaluated using:

 - Accuracy

 - Precision & Recall

 - F1-Score

 - Sensitivity & Specificity

 - ROC-AUC

-------------------------------------------------------------------------------

## 🏆 Results

The **XGBoost** model achieved the **best** overall performance, providing the most reliable predictions for identifying potential term **deposit** subscribers.

This model can help businesses:

- Reduce marketing costs

- Improve campaign targeting

- Increase conversion rates

---------------------------------------------------------------------------------

## ⚙️ Tools & Technologies

- **Python**

- **Pandas & NumPy**

- **Seaborn & Matplotlib**

- **Scikit-Learn**

- **XGBoost**

- **Jupyter Notebook**

--------------------------------------------------------------------------------

## 🚀 How to Run

1. Clone the repository

2. Install dependencies

- pip install pandas numpy seaborn matplotlib scikit-learn xgboost


3. Open the notebook

- jupyter notebook

-----------------------------------------------------------------------------------

## 📈 Key Business Insights

- Customers with higher **call duration** are more likely to subscribe.

- Clients who had successful outcomes in previous campaigns show **higher** conversion probability.

- **Age, job type**, and **account balance** also influence customer decisions.
