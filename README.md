# 📈 E-Commerce Sales & Profit Analysis using Python

## Overview

This project performs Exploratory Data Analysis (EDA) on an e-commerce retail dataset to uncover sales trends, profitability, customer segment performance, and product category insights.

The analysis is performed using **Python**, **Pandas**, and **Plotly**, with interactive visualizations that help understand business performance and identify areas for improvement.

---

## Business Problem

Retail companies generate large volumes of sales data every day. Understanding sales trends, profit margins, and customer purchasing behavior helps businesses make informed decisions regarding inventory, pricing, and marketing.

This analysis answers questions such as:

- Which months generate the highest sales?
- Which product categories contribute the most revenue?
- Which sub-categories are most profitable?
- Which customer segment generates the highest profit?
- What is the relationship between sales and profit?
- Do high-revenue categories actually convert that revenue into profit?

---

## Dataset

**Dataset:** Sample Superstore (9,994 transaction records, Jan–Sep 2017)

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

- Imported dataset using Pandas (`encoding='latin-1'`, required for this file's special characters)
- Data exploration (`.describe()`, `.info()`) to check summary stats and data types
- Converted `Order Date` and `Ship Date` from string to datetime
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

### 📉 Sales-to-Profit Ratio Analysis (by Segment)

Calculated Sales-to-Profit ratio to evaluate business efficiency across customer segments — a lower ratio means fewer sales dollars were needed to generate each dollar of profit.

---

### 🧮 Profit Margin by Category

Calculated Profit Margin % (`Profit / Sales`) for each product category, to check whether revenue ranking and profitability ranking actually agree.

---

## Key Insights

- Sales fluctuate throughout the year with noticeable seasonal peaks.
- Technology and Office Supplies contribute significantly to overall revenue.
- Some product sub-categories generate high sales but relatively low profits.
- Customer segments differ in both revenue generation and profitability — **Home Office is the most profit-efficient segment** (lowest sales-to-profit ratio) despite having the smallest sales volume of the three.
- **Sales alone are not always an indicator of profitability**: Furniture generates revenue nearly on par with Technology ($742K vs. $836K) but converts only a **2.5% profit margin**, compared to Technology's **17.4%** — a category that looks strong by revenue is actually the weakest by profitability, likely due to heavier discounting.

---

## Technologies Used

- Python
- Pandas
- Plotly
- Jupyter Notebook

## Links

- GitHub: https://github.com/Aakash200411
- LinkedIn: https://www.linkedin.com/in/aakash-lodha-9a2ab0259/
- Portfolio: https://aakash200411.github.io/Portfolio/
