# Customer Retention and Cohort Analysis using SQL

## Project Overview

This project uses PostgreSQL to analyze customer purchasing behavior, repeat purchases, monthly retention, customer spending, revenue trends, and inactive customers.

The objective is to understand how customers engage with a business over time, identify valuable customers, and generate insights that can help improve customer retention and business performance.

## Objectives

- Analyze customer purchasing patterns.
- Identify repeat customers and calculate the repeat-customer rate.
- Track monthly revenue and active customers.
- Perform cohort analysis based on customers' first completed purchases.
- Analyze customer retention across subsequent months.
- Calculate customer spending and historical lifetime revenue.
- Identify customers without completed purchases.
- Rank customers based on revenue contribution.
- Compare completed and cancelled orders.

## Tools and Technologies

- **Database:** PostgreSQL
- **SQL Environment:** pgAdmin
- **Language:** SQL
- **Version Control:** Git and GitHub

## Dataset Description

The project uses fictional sample data stored in two relational tables.

### 1. `cohort_customers`

Contains customer information.

| Column | Description |
|---|---|
| customer_id | Unique customer identifier |
| customer_name | Customer name |
| city | Customer's city |
| signup_date | Date the customer registered |

### 2. `cohort_orders`

Contains customer order information.

| Column | Description |
|---|---|
| order_id | Unique order identifier |
| customer_id | Customer who placed the order |
| order_date | Date of the order |
| order_amount | Monetary value of the order |
| order_status | Completed or cancelled |

The dataset contains 
