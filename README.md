# Amazon Sales Performance Analysis

## Project Overview

This project analyzes Amazon marketplace sales data to understand revenue performance, product contribution, regional sales distribution, and order status patterns.

The objective of this project is to transform raw transaction data into meaningful business insights using data cleaning, analysis, and dashboard visualization.


## Business Questions

This analysis aims to answer:

- How is the overall revenue trend over time?
- Which product categories generate the highest revenue?
- Which states contribute the most sales?
- What is the overall order status performance?


## Dataset

Dataset:
Amazon Sale Report

Dataset contains:

- 128,975 sales transactions
- Order information
- Product details
- Customer location
- Fulfillment information
- Sales amount


## Tools Used

- Microsoft Excel
- Pivot Table
- Data Cleaning
- Data Visualization
- Dashboard Development


## Data Cleaning Process

The following data quality issues were identified and handled:

| Issue | Action |
|---|---|
| Unnecessary columns | Removed index and empty columns |
| Amount stored as text | Converted amount into numeric format |
| Inconsistent date formats | Standardized date values |
| Missing values | Handled based on business context |
| Multiple order statuses | Created status grouping for analysis |


## Dashboard

The dashboard includes:

- Total Revenue KPI
- Total Orders KPI
- Units Sold KPI
- Cancellation Rate KPI
- Monthly Revenue Trend
- Revenue by Category
- Top 10 States by Revenue
- Order Status Analysis

![Amazon Sales Dashboard](dashboard.jpeg)

## Key Insights

### Revenue Performance

Revenue reached its highest point during April–June, with April showing the strongest sales performance.

### Product Performance

Set and Kurta categories generated the highest revenue contribution compared to other product categories.

### Geographic Performance

Maharashtra and Karnataka were the highest revenue-contributing states.

### Operational Performance

Most orders reached shipped status, while cancellation rate reached 14%, indicating an opportunity for further investigation.


## Recommendations

- Optimize inventory planning for high-performing product categories.
- Focus marketing activities on high-revenue regions.
- Analyze cancellation reasons to improve order completion.
- Use historical sales trends for future demand planning.
