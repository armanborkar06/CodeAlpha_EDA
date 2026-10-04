# CodeAlpha EDA - Retail Sales Data Analysis

## Project Overview

This project performs Exploratory Data Analysis (EDA) on a retail sales dataset.

The main goal is to understand sales performance, profit, product categories, regions, customers, and monthly trends using Python and Pandas.

## Objectives

- Understand the structure and quality of the dataset
- Check missing values and duplicate records
- Analyze sales and profit
- Compare product categories and regions
- Analyze monthly sales and profit
- Identify profitable and loss-making orders
- Find important business insights from the data

## Dataset

The dataset contains retail sales transaction data with 20 records and 10 columns.

Main columns:

- Order_ID
- Order_Date
- Customer_Name
- Product
- Category
- Region
- Quantity
- Unit_Price
- Sales
- Profit

## Tools & Technologies

- Python
- Pandas
- Jupyter Notebook
- Visual Studio Code

## EDA Performed
## Data Visualization

The following visualizations were created using Matplotlib:

- Sales by Category
- Sales by Region
- Monthly Sales Trend
- Profit by Category
- Sales by Product
- Sales vs Profit

These visualizations were used to identify sales trends, category performance, regional performance, product performance, and the relationship between sales and profit.

## Key Visualization Insights

- Electronics generated higher sales and profit than Furniture.
- North region recorded the highest sales.
- February recorded the highest monthly sales.
- Laptop generated the highest sales among the products.
- Sales and Profit have a very strong positive relationship.

### Data Understanding
- Dataset shape
- Column names
- Data types
- Statistical summary

### Data Quality
- Missing value analysis
- Duplicate row analysis
- Date format conversion

### Business Analysis
- Total sales, profit and quantity
- Category-wise sales and profit
- Region-wise sales and profit
- Product-wise sales and profit
- Monthly sales and profit
- Customer-wise sales
- Top sales orders
- Product-wise quantity
- Loss-making order analysis
- Sales and profit correlation

## Key Findings

- The dataset contains 20 sales records and 10 columns.
- No missing values were found.
- No duplicate rows were found.
- All orders in the dataset are profitable.
- February recorded the highest monthly sales.
- February also recorded the highest monthly profit.
- Electronics performed better than Furniture in terms of sales and profit.
- Sales and Profit have a very strong positive correlation of approximately 0.995.

## Project Structure

```text
CodeAlpha_EDA/
│
├── data/
│   └── sales.csv
│
├── eda_analysis.ipynb
│
└── README.md