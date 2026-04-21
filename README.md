# Customer Spending Behavior & Risk Analysis

## Overview
This project analyzes customer spending behavior using a simulated healthcare expenditure dataset inspired by MEPS-style variables. The goal is to identify high-cost individuals and estimate annual spending using machine learning techniques.

## Business Problem
Organizations need to identify high-risk customers early so they can allocate resources more effectively, improve planning, and support data-driven decision-making.

## Objectives
- Identify customers likely to become high-cost individuals
- Predict annual spending using regression modeling
- Visualize spending distribution and risk patterns
- Translate model results into business insights

## Dataset
The dataset used in this notebook is a simulated dataset containing:
- Age
- Income
- Chronic conditions
- Doctor visits
- Annual spend
- High-cost indicator

## Methods
### Classification
- Random Forest Classifier
- Goal: classify whether a customer is high-cost

### Regression
- Linear Regression
- Goal: estimate annual spending

### Visualization
- Histogram of annual spending
- Exploratory analysis of cost behavior

## Key Insights
- Higher doctor visits and chronic condition burden are associated with greater spending risk
- Spending behavior can be framed as both a classification and regression problem
- Predictive modeling can support early identification of high-risk customers

## Business Impact
This project shows how analytics can help organizations:
- Identify high-risk customer segments
- Improve resource allocation
- Support proactive decision-making
- Build a foundation for risk-based intervention strategies

## Tools Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Project Files
- `customer_spending_analysis.ipynb` — main notebook
- `README.md` — project summary

## Author
Nicholson Hartowidjojo
