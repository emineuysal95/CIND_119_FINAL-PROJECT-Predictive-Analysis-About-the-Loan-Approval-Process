# CIND_119_FINAL-PROJECT-Predictive-Analysis-About-the-Loan-Approval-Process
# Predictive Analysis About the Loan Approval Process

## 📘 Project Overview
This project focuses on predicting loan approval outcomes using the **German Credit dataset**. We explore key financial and demographic attributes of loan applicants and apply two supervised learning models — **Decision Tree** and **Naive Bayes** — to classify creditworthiness.

The aim is to build a data-driven decision support system that assists financial institutions in reducing risk and streamlining the loan approval process.

## 🛠️ Tools & Technologies
- **RStudio** (Naive Bayes model, EDA)
- **SAS** (Decision Tree model, model performance)
- German Credit Dataset (.csv)

## 📊 Dataset Description
- 1000 records of loan applicants
- 21 features including:
  - **Financial attributes**: Account balance, credit amount, value savings, installment percentage
  - **Demographics**: Age, gender/marital status, employment length, apartment type
  - **Target variable**: `Creditability` (1 = good credit, 0 = bad credit)

## 🔍 Key Steps
1. **Exploratory Data Analysis (EDA)**
   - Summary statistics
   - Outlier detection (IQR)
   - Missing value check (none)
   - Class imbalance analysis (70% creditworthy)
2. **Feature Engineering**
   - Identified top predictors: AccountBalance, ValueSavingsandStocks, CreditAmount
   - Correlation and variable importance explored
3. **Predictive Modeling**
   - **Decision Tree** (SAS)
     - Used Gini Index and pruning for generalization
     - Accuracy: ~76%
     - AUC: 0.7611
   - **Naive Bayes** (RStudio)
     - Full model vs. selected features
     - Accuracy: ~78%

## 📈 Results Summary
- **Naive Bayes** slightly outperforms Decision Tree in accuracy.
- **Top Predictors**: Account Balance, Value of Savings, Credit Amount
- Simplified models using fewer predictors still achieve competitive accuracy.

## 🧠 Recommendations
- Focus on most influential variables during application evaluation.
- Add external variables like income or credit score to improve prediction.
- Consider model simplification by removing low-impact variables (e.g., number of dependents).

## 👥 Contributors
- Emine Uysal – SAS modeling and final reporting
- Sharmila Nandi – R modeling and feature importance analysis

## 📂 Repository Structure
```
├── data/                    # German Credit dataset (CSV)
├── SAS_Code/               # Decision Tree implementation in SAS
├── reports/                # Model outputs, plots, and EDA summaries
├── README.md               # Project overview and documentation
```

## 🎯 Goal
To develop an interpretable and accurate model for evaluating the creditworthiness of loan applicants and improving the loan approval process using predictive analytics.

---

> This project was submitted for **CIND 119: Introduction to Big Data Analytics** at Toronto Metropolitan University – The Chang School.
---
Author: Emine Uysal 
FINAL PROJECT: Predictive Analysis About the Loan Approval Process
Date: December 2024

