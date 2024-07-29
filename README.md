# Customer Churn Analysis

## Overview

This repository contains a comprehensive analysis of customer churn for a banking dataset. The analysis focuses on various aspects of customer behavior and characteristics to understand factors influencing customer attrition. Key analyses include customer balance distributions, relationships between credit ratings and salaries, and the impact of customer demographics and service usage on churn.

## Contents

churn_df: The primary dataset containing customer information.
README.md: This file providing an overview of the repository.
Churn visual analisys.ipynb


## Dataset

The dataset churn_df includes the following columns:

age: Age of the customer.

exited: Binary flag indicating whether the customer has exited (1) or is loyal (0).

balance: Balance of the customer's account.

credit_rating: Credit rating of the customer.

estimated_salary: Estimated salary of the customer.

gender: Gender of the customer.

num_services: Number of services purchased by the customer.

active_status: Whether the customer is active.

country: Country of the customer.

CreditScoreCat: Credit score category.

Tenure: Number of years the customer has been with the bank.

## Key Analyses

Ratio of Exited and Loyal Customers:
Analyze the proportion of customers who have exited versus those who are loyal.

Balance Distribution Histogram:
Plot the distribution of account balances for customers with more than $2,500 in their accounts.

Balance Distribution by Churn:
Compare the balance distributions between exited and loyal customers.

Scatter Plot of Credit Rating vs. Estimated Salary:
Visualize the relationship between clients' credit ratings and their estimated salaries.

Churn by Gender:
Determine whether men or women have higher churn rates.

Churn and Number of Services:
Analyze how the number of services purchased affects customer churn.

Impact of Active Status on Churn:
Evaluate whether being an active client influences churn rates.

Churn by Country:
Identify which countries have higher shares of departed customers.

Summary Table of Credit Score and Tenure:
Create a table summarizing the average churn rate based on credit score categories and tenure with the bank.

Heatmap of Churn Rates:
Build a heatmap with annotations based on the summary table to visualize churn rates across different credit score categories and tenures.

## Requirements

Python 3.x
pandas
seaborn
matplotlib
numpy
scipy

## License

This project is licensed under the MIT License. See the LICENSE file for details.
