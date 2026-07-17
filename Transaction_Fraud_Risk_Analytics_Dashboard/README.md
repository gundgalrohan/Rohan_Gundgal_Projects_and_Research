# Transaction Fraud Risk Analytics Dashboard

An interactive Power BI dashboard analyzing 10,000 financial transactions to identify fraud rate patterns across transaction type, merchant category, geography, and time.

## Features

- Data cleaning: type corrections, data quality checks (Power Query)
- Custom fraud status column for readable categorization
- KPI cards: total transactions, fraud cases, fraud rate %, total fraud amount
- Fraud rate % breakdown by transaction type, merchant category, and country
- Fraud case trend by hour
- Top 20 highest-value fraud cases table
- Interactive slicers for transaction type, merchant category, and country

## Tech Stack

- Power BI
- DAX (CALCULATE, DIVIDE)
- Power Query (M)

## Dataset

Synthetic financial fraud dataset (10,000 transactions) with columns: transaction_id, user_id, amount, transaction_type, merchant_category, country, hour, device_risk_score, ip_risk_score, is_fraud.

## Key Findings

- Fraud accounts for only 5% of transaction volume but 46.5% of total transaction value
- Fraud rate varies significantly by transaction type, merchant category, and country
- Fraud cases spike sharply within a specific hour range compared to baseline activity
