# UPI Fraud Detection Dashboard

## Project Overview
This project analyzes 100,000 UPI transactions to identify fraud patterns and risk factors. An interactive Power BI dashboard was built to help monitor fraudulent activities effectively.

## Problem Statement
With the rapid growth of UPI payments in India, detecting fraudulent transactions in real-time has become challenging due to high volume and subtle patterns.

## Solution
- Performed Exploratory Data Analysis using Python
- Created a rule-based Risk Score system
- Built an interactive Power BI dashboard with KPIs and filters
- Experimented with Random Forest model for fraud prediction

## Key Insights
- Total Transactions: 100,000
- Fraud Cases: 592 (0.59%)
- High Risk Transactions (Risk Score ≥ 3): ~12,000
- Fraud percentage remains relatively stable across different hours
- Machine Learning model achieved limited performance (10% recall on fraud) due to weak feature signals

## Tools Used
- Python (Pandas, Scikit-learn)
- MySQL
- Power BI & DAX

## Dashboard Features
- KPI Cards: Total Transactions, Fraud Cases, Fraud Rate, Average Amount, High Risk Transactions
- Fraud vs Genuine Distribution
- Fraud % by Hour
- Risk Score Distribution
- Interactive Slicers: Hour, Risk Score, Device Change, Location Change

## Business Impact
Helps fraud monitoring teams quickly identify high-risk transactions and focus on suspicious activities.
