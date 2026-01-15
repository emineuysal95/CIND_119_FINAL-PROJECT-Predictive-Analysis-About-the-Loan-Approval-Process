#💳 Credit Risk Prediction: Streamlining Loan Approval Processes

A Data-Driven Approach using SAS and R

##🚀 Business Impact

Developed a predictive framework to automate credit risk assessment, achieving 78% accuracy in identifying high-risk loan applicants. This model helps financial institutions reduce default rates while optimizing decision-making efficiency.

##📊 Project Overview

This project focuses on predicting loan approval outcomes using the German Credit dataset. We explore key financial and demographic attributes and apply two supervised learning models to classify creditworthiness.

Goal: To build a data-driven decision support system that reduces financial risk and streamlines approvals.

##🛠️ Tools & Technologies

- RStudio: Naive Bayes model & Exploratory Data Analysis (EDA).

- SAS: Decision Tree model & Performance metrics.

- Dataset: German Credit Dataset (1,000 records, 21 features).

##🔍 Analytical Steps

   - EDA & Data Cleaning: Outlier detection (IQR), missing value checks, and class imbalance analysis (70% creditworthy).

   - Feature Engineering: Identified top predictors (Account Balance, Value Savings, Credit Amount).

   - Predictive Modeling:

      * Decision Tree (SAS): Optimized with Cost-Complexity Pruning to prevent overfitting; achieved 76% accuracy and 0.76 AUC.

      * Naive Bayes (R): Improved via feature selection to eliminate noise; emerged as the top performer with 78% accuracy.

##📈 Results & Recommendations

Top Predictors: Account Balance and Savings Value are the most influential variables.

Strategic Recommendation: Financial institutions should prioritize these high-impact variables to enhance risk modeling precision.

Future Work: Integrate external credit scores and income data to further improve prediction accuracy.

📂 Repository Structure
data/: German Credit dataset (CSV).

SAS_Code/: Decision Tree implementation.

reports/: Model outputs, plots, and summaries.

Course: CIND 119: Introduction to Big Data Analytics

Institution: Toronto Metropolitan University (TMU)

Author: Emine Uysal

Date: December 2024
