# Walmart Sales Analysis | Google Colab, SQLite & Power BI

## Project Overview

This project focuses on analyzing Walmart sales data to identify business trends, evaluate sales performance, and generate actionable insights.

The analysis was carried out using **Google Colab, SQLite, and Power BI**. Google Colab was used for data exploration and preprocessing, SQLite for querying and analyzing the data, and Power BI for creating interactive dashboards and visualizing key business metrics.

## Project Objectives

- Analyze overall sales and transaction performance.
- Identify top-performing and low-performing product categories.
- Understand customer ratings across different product categories.
- Analyze customer payment preferences and transaction values.
- Evaluate branch-level and city-level sales performance.
- Develop interactive dashboards to communicate business insights.

## Tools & Technologies

| Tool | Purpose |
|---|---|
| Google Colab | Data exploration, cleaning, and preprocessing |
| SQLite | SQL queries and business data analysis |
| Power BI | Interactive dashboards and data visualization |
| Python | Data handling and preprocessing in Google Colab |
| Pandas | Data manipulation and analysis |

## Dataset Overview

The project uses the `walmart_cleaned` dataset, containing **9,969 transactions** across **100 branches**.

Important columns include:

- `invoice_id`
- `Branch`
- `City`
- `category`
- `sales`
- `quantity`
- `payment_method`
- `rating`
- `year`
- `year_month`

## Project Workflow

### 1. Data Exploration & Cleaning – Google Colab

- Imported and inspected the Walmart sales dataset.
- Explored the dataset structure and data types.
- Checked for missing values and duplicate records.
- Performed data cleaning and preprocessing.
- Prepared the cleaned dataset for SQL analysis.

### 2. Data Analysis – SQLite

Used SQLite to write SQL queries and extract meaningful business insights.

Analysis included:
- Total sales and transaction analysis.
- Sales performance by product category.
- Average customer ratings by category.
- Sales distribution by payment method.
- Average transaction value by payment method.
- Yearly and monthly sales trends.
- Branch-level and city-level sales performance.
- Top and bottom-performing branches.

### 3. Dashboard Development – Power BI

Imported the cleaned dataset into Power BI and developed a three-page interactive dashboard.

## Dashboard Pages

### Page 1 – Sales Overview

Provides a high-level overview of Walmart's sales performance.

**Key Performance Indicators:**
- Total Sales
- Total Transactions
- Total Quantity Sold
- Average Transaction Value

**Visualizations:**
- Monthly Sales Trend
- Sales by Product Category
- Annual Sales Overview
- Transactions by Payment Method

### Page 2 – Product & Payment Analysis

Focuses on product category performance, customer satisfaction, and payment preferences.

**Visualizations:**
- Average Customer Rating by Category
- Sales by Payment Method
- Average Transaction Value by Payment Method
- Sales by Product Category

### Page 3 – Store Performance Analysis

Evaluates sales performance across Walmart branches and cities.

**Key Performance Indicators:**
- Total Stores
- Highest Store Sales
- Lowest Store Sales
- Average Sales per Store

**Visualizations:**
- Top 10 Branches by Sales
- Bottom 10 Branches by Sales
- Sales Performance by City
- Branch Sales vs Transaction Volume
- Branch Contribution to Total Sales

## Key Business Insights

- Total sales reached approximately **1.21 million** across 9,969 transactions.
- A total of **23,483 units** were sold across 100 branches.
- Fashion Accessories and Home & Lifestyle generated the highest sales among product categories.
- Cash payments had the highest average transaction value.
- Food & Beverages recorded the highest average customer rating.
- Branch-level analysis revealed differences in sales performance across locations.

## Interactive Dashboard Features

The Power BI report includes slicers that allow users to explore the data dynamically by:

- Year
- Payment Method
- Product Category
- City

## Repository Structure

```text
Walmart-Sales-Analysis/
│
├── Dataset/
│   └── walmart_cleaned.csv
│
├── Google_Colab/
│   └── Walmart_Sales_Analysis.ipynb
│
├── SQLite/
│   └── SQL_Queries.sql
│
├── PowerBI/
│   └── Walmart_Sales_Analysis.pbix
│
├── Screenshots/
│   ├── Sales_Overview.png
│   ├── Product_Payment_Analysis.png
│   └── Store_Performance_Analysis.png
│
└── README.md
```

## Conclusion

This project demonstrates an end-to-end data analytics workflow, from data exploration and cleaning to SQL-based analysis and interactive dashboard development.

By combining Google Colab, SQLite, and Power BI, the project transforms raw retail sales data into meaningful business insights and visual reports.

**Project Type:** Data Analytics | Business Intelligence

**Technologies:** Google Colab | Python | SQLite | SQL | Power BI
