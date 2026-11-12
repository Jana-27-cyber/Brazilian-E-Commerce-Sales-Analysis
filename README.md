# Brazilian E-Commerce Sales Analysis

## Week 1 – Data Science Internship Project

## Project Overview

This project focuses on cleaning, analyzing, and visualizing the Brazilian E-Commerce Public Dataset by Olist.

The objective is to understand e-commerce sales performance, customer purchasing behavior, product category performance, payment preferences, and delivery trends using Python and data analysis techniques.

The project includes data inspection, data cleaning, exploratory data analysis (EDA), KPI calculation, customer analysis, business insights, and data visualization.

## Project Objectives

- Inspect and understand the raw datasets.
- Identify missing values, duplicate records, and data quality issues.
- Clean and validate datasets while preserving the original raw data.
- Analyze sales performance and calculate business KPIs.
- Identify top-performing product categories and products.
- Understand customer purchasing behavior.
- Analyze monthly sales and delivery performance.
- Create meaningful visualizations and a dashboard.
- Generate business insights and recommendations.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- VS Code
- Git and GitHub

## Dataset Overview

The project uses the Brazilian E-Commerce Public Dataset by Olist.

The analysis uses nine datasets covering:

- Customers
- Geolocation
- Orders
- Order items
- Payments
- Reviews
- Products
- Sellers
- Product category translation

These datasets contain information about customer orders, products, payments, sellers, delivery, and reviews.

## Analysis Performed

### 1. Data Inspection

- Loaded and inspected the original datasets.
- Examined dataset dimensions and column names.
- Checked data types and data consistency.
- Identified missing values and duplicate records.
- Investigated data quality issues across datasets.

### 2. Data Cleaning

- Identified and analyzed missing values.
- Checked duplicate records.
- Validated important columns and data types.
- Investigated missing product and payment information.
- Preserved missing values when original records could not verify the actual values.
- Saved cleaned datasets separately without modifying the original raw datasets.

### 3. Sales Analysis

- Monthly sales and order trends.
- Order status distribution.
- Product category performance.
- Payment method analysis.
- Credit card installment analysis.
- State-wise and city-wise sales.
- Freight cost analysis.
- Delivery performance analysis.
- Product-level revenue analysis.

### 4. Customer Analysis

- Unique customer identification using customer unique IDs.
- One-time customer analysis.
- Repeat customer analysis.
- State-wise customer distribution.
- City-wise customer distribution.
- Customer purchasing behavior analysis.

### 5. Data Visualization

Created visualizations to communicate:

- Monthly sales trends.
- Order status distribution.
- Payment method distribution.
- Top product categories.
- State-wise and city-wise sales.
- Delivery performance.
- Sales correlation.
- Customer type distribution.
- Customer geographical distribution.
- Overall sales dashboard.

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

**KPI Calculation Note:** Total Product Sales Value is calculated using order item prices across all order statuses, excluding freight. It is not the same as completed-sales revenue or total payment value. Average Product Sales Value per Order is calculated using this product sales value divided by total orders.

## Important Business Insights

1. **Overall Sales Performance:** The platform recorded 99,441 orders and 112,650 units sold, demonstrating substantial transaction activity.

2. **Monthly Order Trend:** November 2017 recorded the highest order volume, with 7,544 orders. This indicates a significant increase in purchasing activity during that month.

3. **Top Revenue-Generating Category:** The `health_beauty` category generated the highest product sales value, amounting to R$1,258,681.34.

4. **Top-Selling Category by Quantity:** The `bed_bath_table` category recorded the highest quantity sold, with 11,115 units. This shows that the category with the highest sales quantity may differ from the category generating the highest revenue.

5. **Customer Retention:** Out of 96,096 unique customers, 2,997 were repeat customers. The repeat customer percentage was 3.12%, indicating an opportunity to improve customer retention.

6. **Top Revenue-Generating Product:** Product `bb50f2e236e5eea0100680137654686c`, belonging to the `beleza_saude` category, generated R$63,560.00 from 194 units sold across 186 delivered orders.

7. **Delivery Performance:** Delivery performance analysis helps identify delivery delays and geographical areas that may need operational improvement.

8. **Payment Behaviour:** Payment method and installment analysis provide information about customer payment preferences and can support improvements to the checkout experience.

**Product Revenue Note:** The top product revenue result is calculated using delivered orders only. Product sales values exclude freight charges.

## Business Recommendations

- Introduce customer loyalty and retention programs.
- Provide personalized offers to encourage repeat purchases.
- Focus marketing campaigns on high-performing product categories.
- Promote popular products based on customer demand.
- Improve delivery performance in regions with higher delay rates.
- Analyze payment preferences to improve the checkout experience.
- Use monthly sales trends for better business planning.

## Data Quality and Validation

The project included systematic data quality checks:

- Missing values were identified and documented.
- Duplicate records were checked across the original datasets.
- No duplicate rows were identified in the checked datasets.
- Missing product information was investigated against the original order items dataset.
- 775 orders with missing product information had no matching original order item records.
- Raw datasets were preserved separately from cleaned outputs.
- The final sales dataset was saved and verified.

## Project Output Files

### Main Files

- `01_data_inspection.ipynb` – Main data inspection and analysis notebook.
- `README.md` – Project documentation.
- `requirements.txt` – Required Python libraries.

### Sales Analysis Outputs

Location: `outputs/sales_analysis/`

- `final_sales_dataset.csv`
- `sales_missing_values_report.csv`
- `sales_dataset_summary.csv`
- `sales_dashboard_kpis.csv`
- `monthly_sales_trend.png`
- `order_status_distribution_readable.png`
- `payment_type_distribution_readable.png`
- `top_10_states_sales_chart.png`
- `top_10_cities_sales_chart.png`
- `top_10_categories_sales_value.png`
- `delivery_performance_chart.png`
- `sales_correlation_heatmap.png`
- `sales_analysis_dashboard.png`
- `customer_type_distribution.png`
- `top_10_customer_states.png`
- `top_10_customer_cities.png`

### Data Quality Report

Location: `outputs/reports/`

- `missing_values_analysis.png`

## Limitations and Assumptions

- The analysis is based on the available Olist public dataset.
- Missing values were not filled with assumed values when original records could not verify them.
- Product sales value excludes freight charges.
- The overall product sales KPI includes all order statuses.
- The top revenue-generating product calculation uses delivered orders only.
- September 2016 and October 2018 may represent partial periods in the available dataset.
- Historical trends do not guarantee future sales performance.

## Conclusion

This project demonstrates an end-to-end data analysis workflow using a real-world Brazilian e-commerce dataset.

Data inspection, cleaning, validation, KPI calculation, exploratory analysis, customer analysis, and visualization were performed to understand business performance.

The findings highlight product category performance, customer retention opportunities, monthly order trends, payment preferences, and delivery performance.

The project demonstrates how data analysis can support business decisions through meaningful insights and visual reporting.

## How to Run the Project

1. Clone or download this repository.
2. Open the project folder in VS Code.
3. Create and activate a Python virtual environment if required.
4. Install the required libraries:

```bash
pip install -r requirements.txt
```

5. Open the Jupyter Notebook:

```bash
jupyter notebook 01_data_inspection.ipynb
```

6. Run the notebook cells from top to bottom.

**Note:** Keep the original datasets in the `data/raw/` folder so the notebook can access the required input files.

## GitHub Repository

[Brazilian E-Commerce Sales Analysis](https://github.com/Jana-27-cyber/Brazilian-E-Commerce-Sales-Analysis)

## Author

**GitHub:** [Jana-27-cyber](https://github.com/Jana-27-cyber)

**Project:** Data Science Internship – Week 1

**Domain:** Data Science | Data Analysis | E-Commerce Analytics