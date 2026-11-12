# Brazilian E-Commerce Sales Analysis

## Project Overview

This project analyzes Brazilian e-commerce data to understand
sales performance, customer behavior, payment patterns,
product performance, and delivery performance.

The analysis uses the Olist e-commerce dataset and applies
Python-based data cleaning, exploratory data analysis,
business analytics, and data visualization techniques.

## Project Objectives

- Analyze overall sales and order performance.
- Identify top-performing product categories.
- Understand customer purchasing and retention patterns.
- Analyze payment methods and installment preferences.
- Evaluate delivery performance.
- Identify important business insights and recommendations.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- SQL / SQLite (where applicable)

## Dataset Overview

The project uses multiple related e-commerce datasets,
including information about:

- Customers
- Orders
- Order items
- Payments
- Products
- Sellers
- Reviews
- Geolocation

## Analysis Performed

### 1. Data Cleaning

- Inspected dataset structure and data types.
- Identified missing values and duplicate records.
- Investigated missing product and payment information.
- Preserved missing values when the original records
  could not verify the actual values.

### 2. Sales Analysis

- Monthly sales trends.
- Order status analysis.
- Product category performance.
- Payment method analysis.
- Installment analysis.
- State-wise and city-wise sales.
- Freight cost analysis.
- Delivery performance analysis.

### 3. Customer Analysis

- Unique customer identification.
- One-time customer analysis.
- Repeat customer analysis.
- State-wise customer distribution.
- City-wise customer distribution.

### 4. Data Visualization

Created visualizations to communicate:
- Monthly sales trends.
- Top product categories.
- Payment distribution.
- Order status distribution.
- Geographic sales performance.
- Delivery performance.
- Customer distribution.

## Key Project Results

| Metric | Result |
|---|---:|
| Total Orders | 99,441 |
| Total Units Sold | 112,650 |
| Total Product Sales Value | R$13,591,643.70 |
| Average Product Sales Value per Order | R$136.68 |
| Total Unique Customers | 96,096 |
| One-Time Customers | 93,099 |
| Repeat Customers | 2,997 |
| Repeat Customer Percentage | 3.12% |

Note: Product sales value is calculated from order item prices
and excludes freight. It should not be confused with total
payment value.

## Important Business Insights

1. The dataset contains 99,441 orders.
2. The bed_bath_table category recorded the highest number
   of items sold.
3. The health_beauty category generated the highest
   product sales value.
4. Credit card was the most frequently used payment method.
5. Sao Paulo recorded the highest state-wise sales value.
6. Most customers placed only one order.
7. The repeat customer percentage was 3.12%.

## Business Recommendations

- Introduce customer loyalty and retention programs.
- Provide personalized offers to encourage repeat purchases.
- Focus marketing campaigns on high-performing categories.
- Improve delivery performance in states with higher delay rates.
- Analyze payment preferences to improve the checkout experience.
- Use monthly sales trends for better business planning.

## Data Quality and Validation

The final order-level sales dataset contains:

- 99,441 rows.
- 19 columns.
- No duplicate rows.
- No duplicate order IDs.

Additional validation included:

- Missing-value investigation and treatment.
- Original versus final dataset reconciliation.
- Date column validation.
- Sales KPI recalculation.
- Customer KPI recalculation.

## Project Output Files

Important outputs are stored in:

`outputs/sales_analysis/`

The folder includes cleaned sales data, KPI reports,
business observations, customer insights, visualizations,
and validation reports.

## Conclusion

This project demonstrates how Python can be used to
analyze real-world e-commerce data and convert raw data
into meaningful business insights.

The findings can help businesses understand sales trends,
customer retention, product performance, payment behavior,
and delivery efficiency.

---
