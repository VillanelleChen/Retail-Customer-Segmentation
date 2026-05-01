# Customer Analytics: EDA, RFM Segmentation, and Churn Prediction

## Project Overview

This project analyzes customer transaction data to understand purchasing behavior, identify customer segments, and predict customer churn risk. The analysis is completed in a single R Markdown file, combining data cleaning, exploratory data analysis, RFM-based customer segmentation, and churn prediction modeling.

The goal of this project is to transform transaction-level data into customer-level insights that can support retention strategy, targeted marketing, and customer relationship management.

---

## Business Questions

This project focuses on three main questions:

1. What are the key purchasing patterns in the customer transaction data?
2. How can customers be segmented based on recency, frequency, and monetary value?
3. Can customer behavior features be used to predict churn risk?

---

## Project Components

### 1. Exploratory Data Analysis

The exploratory data analysis section examines customer and transaction behavior, including:

- Overall sales and transaction patterns
- Customer purchase frequency
- Revenue distribution across customers
- One-time versus repeat customer behavior
- Product and order-level trends
- Potential churn-related behavior patterns

This step helps identify important trends and provides a foundation for later segmentation and modeling.

---

### 2. RFM Customer Segmentation

Customers are segmented using RFM analysis:

- **Recency**: How recently a customer made a purchase
- **Frequency**: How often a customer made purchases
- **Monetary Value**: How much a customer spent

Based on these metrics, customers are assigned to different customer segments. These segments help distinguish high-value customers, loyal customers, at-risk customers, and lower-engagement customers.

The segmentation results can be used to support targeted marketing and customer retention strategies.

---

### 3. Customer Churn Prediction

The churn prediction section builds a machine learning model to estimate whether a customer is likely to churn based on customer-level behavioral features.

The modeling workflow includes:

- Creating customer-level features
- Defining the churn target variable
- Splitting data into training and testing sets
- Training classification models
- Evaluating model performance
- Interpreting key churn drivers

Model performance is evaluated using classification metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.

---

## Tools and Technologies

- R
- R Markdown
- tidyverse
- dplyr
- ggplot2
- caret / tidymodels
- pROC
- knitr

---

## Repository Structure

```text
customer-analytics-project/
│
├── Final_Project_Topic4_finalver.Rmd
└── README.md
