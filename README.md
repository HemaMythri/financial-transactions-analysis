# Financial Transactions Analytics Dashboard

## Project Overview

This project focuses on analyzing financial transaction data using Python, SQL, and Power BI. The objective is to perform Exploratory Data Analysis (EDA), answer key business questions using SQL, and create an interactive dashboard for business insights.

## Dataset

The dataset contains transaction-level financial data, including:

- Transaction ID
- Transaction Date
- Customer ID
- Product Name
- Quantity
- Price
- Payment Method
- Transaction Status
- Total Amount
- Transaction Month
- Transaction Year
- High Value Transaction Indicator

## Objectives

- Perform descriptive statistical analysis.
- Analyze distributions of numerical and categorical variables.
- Answer business questions using SQL queries.
- Identify relationships among variables through correlation analysis.
- Build a Power BI dashboard to visualize key insights.

## Tools & Technologies

- Python
- Pandas
- Matplotlib
- Seaborn
- SQLite
- Jupyter Notebook
- Power BI
- GitHub

## Exploratory Data Analysis (EDA)

### Descriptive Statistics
- Summary statistics for numerical features.
- Missing value analysis.
- Data type verification.

### Univariate Analysis
- Transaction Status Distribution
- Payment Method Distribution
- Quantity Distribution

### Multivariate Analysis
- Correlation Heatmap
- Scatter Plot Analysis
- Pairwise Relationship Analysis

## SQL Business Questions

### 1. Top 5 Products by Revenue
Identified the products generating the highest revenue.

### 2. Revenue by Payment Method
Analyzed customer payment preferences and revenue contribution.

### 3. Transaction Status Distribution
Evaluated successful and unsuccessful transaction counts.

### 4. Top Products by Quantity Sold
Determined the most frequently purchased products.

### 5. High-Value Transaction Analysis
Measured the contribution of high-value transactions.

## Dashboard Components

### KPI Cards
- Total Revenue
- Total Transactions
- Average Order Value
- High-Value Transactions

### Visualizations
- Revenue by Payment Method
- Monthly Revenue Trend
- Top Products by Revenue
- Transaction Status Distribution
- Quantity vs Revenue Analysis

## Key Insights

- Revenue is concentrated among a few top-performing products.
- Certain payment methods contribute significantly to overall revenue.
- High-value transactions play an important role in revenue generation.
- Quantity sold has a positive relationship with total transaction value.
- Monthly trends help identify seasonal sales patterns.

## Project Structure

```
financial-transactions-eda-dashboard/
│
├── cleaned_financial_transactions_v2.csv
├── eda_analysis.ipynb
├── queries.sql
├── dashboard.pbix
├── dashboard.png
└── README.md
```

## How to Run

1. Clone the repository.
2. Install required libraries:

```bash
pip install pandas matplotlib seaborn jupyter
```

3. Open the Jupyter Notebook:

```bash
jupyter notebook
```

4. Run all notebook cells.
5. Open Power BI dashboard file (`dashboard.pbix`) to explore visualizations.

## Conclusion

This project demonstrates how Python, SQL, and Power BI can be integrated to perform end-to-end business analytics. The analysis provides valuable insights into customer transactions, revenue patterns, product performance, and payment behavior.
