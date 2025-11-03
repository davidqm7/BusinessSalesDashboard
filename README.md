# BusinessSalesDashboard
An end-to-end data analytics project analyzing sales, profit, and performance trends across regions, categories, and customer segments using **Python** and **Power BI**.  
This project demonstrates the complete data analytics lifecycle — from data cleaning and analysis to visualization and business insights.


## 🚀 Project Overview
The goal of this project is to evaluate sales performance and identify key drivers of profitability in a retail dataset.  
Using data cleaning in Python and interactive dashboarding in Power BI, this analysis uncovers how discounts, categories, and regional differences impact overall performance.

## 🧰 Tools & Technologies
| Phase | Tools / Technologies |
|-------|----------------------|
| Data Cleaning & Preparation | Python, pandas, NumPy |
| Exploratory Data Analysis | pandas, matplotlib, seaborn |
| Data Visualization | Power BI|
| Data Source | Superstore Sales Dataset (10K+ records) |

## 🧹 Step 1: Data Preparation
Performed data cleaning and preprocessing using **Python (pandas)**:
- Removed duplicates and missing values
- Converted dates and extracted `Year` and `Month`
- Standardized numeric columns (`Sales`, `Profit`, `Discount`, etc.)
- Added calculated fields:
  - `Profit Margin (%) = (Profit / Sales) * 100`
  - `Discounted Sales = Sales * (1 - Discount)`

Saved final dataset as:

data/cleaned_superstore_sales.csv

## 📈 Step 2: Exploratory Data Analysis (EDA)
Explored patterns and relationships:
- Distribution of sales and profit by category and region
- Correlation between discount and profitability
- Yearly and monthly sales trends
- Customer segmentation by sales contribution

## 🧹 Step 3: Dashboard Development (Power BI)
Developed an interactive Power BI Dashboard titled
 "Superstore Sales Performance Dashboard"

 ![dashboard](image.png)