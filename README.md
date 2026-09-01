# 📊 EDA Sales Analysis

An Exploratory Data Analysis (EDA) project on sales data, using Python and Pandas to uncover revenue trends, category performance, and pricing patterns.

## 🎯 Objective

Act as a data detective — ask meaningful questions about the dataset, and use filtering, grouping, and analysis techniques to find answers backed by data.

## 📁 Files

- `EDA_Sales_Analysis.ipynb` — Jupyter/Colab notebook with full analysis
- `sales_data.csv` — Raw sales dataset (Jan–Dec 2025)

## 🔍 Dataset Overview

The dataset contains monthly sales records across 5 product categories:
- Electronics
- Clothing
- Home & Kitchen
- Books
- Beauty

Columns: `Month`, `Category`, `Product`, `UnitsSold`, `Price`, `Revenue`

## ❓ Questions Explored

1. **Which product category generates the most revenue?**
   Electronics leads with ~$203,592 in total revenue, followed by Clothing and Beauty. Books generated the least.

2. **Which month had the highest total sales revenue?**
   December recorded the highest revenue (~$69,892), suggesting a seasonal holiday spike. April was the lowest.

3. **Does a higher price lead to fewer units sold in Electronics?**
   Correlation between price and units sold was very weak (-0.089), showing that product type — not price — drives demand more strongly.

## 🛠️ Tools & Libraries

- Python
- Pandas
- Matplotlib

## 📈 Key Skills Demonstrated

- Data loading & inspection
- Filtering
- Groupby aggregations
- Correlation analysis
- Data visualization

## 🚀 How to Run

1. Clone this repository
2. Open `EDA_Sales_Analysis.ipynb` in Jupyter Notebook or Google Colab
3. Make sure `sales_data.csv` is in the same directory
4. Run all cells

---
*Created as part of a Data Analysis practice project.*
