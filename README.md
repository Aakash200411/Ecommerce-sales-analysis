# 📈 E-Commerce Sales & Profit Analysis using Python

## Overview

This project performs Exploratory Data Analysis (EDA) on an e-commerce retail dataset to uncover sales trends, profitability, customer segment performance, and product category insights.

The analysis is performed using **Python**, **Pandas**, and **Plotly**, with interactive visualizations that help understand business performance and identify areas for improvement.

---

## Project Preview

> Add screenshots of your charts or notebook outputs.

![Dashboard](Images/dashboard.png)

---

## Business Problem

Retail companies generate large volumes of sales data every day. Understanding sales trends, profit margins, and customer purchasing behavior helps businesses make informed decisions regarding inventory, pricing, and marketing.

This analysis answers questions such as:

- Which months generate the highest sales?
- Which product categories contribute the most revenue?
- Which sub-categories are most profitable?
- Which customer segment generates the highest profit?
- What is the relationship between sales and profit?

---

## Dataset

**Dataset:** Sample Superstore

The dataset includes information such as:

- Order Date
- Ship Date
- Category
- Sub-Category
- Sales
- Profit
- Customer Segment
- Region
- State

---

## Project Workflow

### Data Preparation

- Imported dataset using Pandas
- Data exploration
- Checked missing values
- Converted date columns
- Created new date-based features
    - Order Month
    - Order Year
    - Order Day of Week

---

## Analysis Performed

### 📅 Monthly Sales Analysis

- Monthly sales trend
- Highest revenue months
- Seasonal sales patterns

---

### 💰 Sales by Category

- Sales distribution across product categories
- Interactive pie chart

---

### 📦 Sales by Sub-Category

- Comparison of sub-category sales
- Highest-selling products

---

### 📈 Monthly Profit Analysis

- Monthly profit trend
- Comparison with sales trend

---

### 💵 Profit by Category

- Most profitable categories
- Lowest profit categories

---

### 📊 Profit by Sub-Category

- Profit comparison across product groups

---

### 👥 Customer Segment Analysis

Comparison of:

- Total Sales
- Total Profit

across customer segments.

---

### 📉 Sales-to-Profit Ratio Analysis

Calculated Sales-to-Profit ratio to evaluate business efficiency across customer segments.

---

## Key Insights

- Sales fluctuate throughout the year with noticeable seasonal peaks.
- Technology and Office Supplies contribute significantly to overall revenue.
- Some product sub-categories generate high sales but relatively low profits.
- Customer segments differ in both revenue generation and profitability.
- Sales alone are not always an indicator of profitability.

---

## Technologies Used

- Python
- Pandas
- Plotly
- Jupyter Notebook

---

## Python Libraries

```python
pandas
plotly
numpy
```

---

## Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Data Cleaning
- Feature Engineering
- Data Visualization
- Business Analysis
- Trend Analysis
- Customer Segmentation
- Profitability Analysis

---

## Repository Structure

```
Ecommerce-Sales-Analysis/
│
├── Data/
│   └── Sample - Superstore.csv
│
├── Notebook/
│   └── Data_Analysis_(Ecommerce).ipynb
│
├── Images/
│   ├── monthly_sales.png
│   ├── category_sales.png
│   ├── profit_analysis.png
│   └── dashboard.png
│
├── README.md
└── requirements.txt
```

---

## Future Improvements

- Sales forecasting using Time Series Analysis
- Customer Lifetime Value (CLV) analysis
- RFM Customer Segmentation
- Geographic sales analysis
- Interactive Streamlit dashboard

---

## Author

**Your Name**

- GitHub: https://github.com/yourusername
- LinkedIn: https://linkedin.com/in/yourprofile
