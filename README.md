# 🛒 SuperStore Data Analysis with Python & SQL Server

## 📌 Project Overview
This project explores the **SuperStore dataset** (9,994 rows, 21 columns) using  
**Azure Data Studio Notebooks**, integrating both **SQL** and **Python** to perform  
end-to-end data analysis.

The goal is to transform raw sales data into **actionable business insights** through:
- SQL queries for structured data extraction
- Python (Pandas, Matplotlib, Seaborn) for data analysis and visualization
- Business Intelligence insights to support decision-making

---

## 🗂️ Dataset Description
The dataset contains **order-level transactions** with the following key fields:
- **Order Information**: `Row ID`, `Order ID`, `Order Date`, `Ship Date`, `Ship Mode`
- **Customer Information**: `Customer ID`, `Customer Name`, `Segment`
- **Geographical Information**: `Country/Region`, `City`, `State`, `Postal Code`, `Region`
- **Product Information**: `Product ID`, `Category`, `Sub-Category`, `Product Name`
- **Financial Metrics**: `Sales`, `Quantity`, `Discount`, `Profit`

---

## ⚙️ Tech Stack
- **SQL Server** (Windows Authentication)
- **Azure Data Studio** (Notebook mode)
- **Python**:  
  - `pandas` (data handling)  
  - `matplotlib` & `seaborn` (visualization)  
  - `pyodbc` (SQL Server connection)

---

## 🔑 Key Features
1. Connect to **SQL Server** with Windows Authentication via `pyodbc`.
2. Write **T-SQL queries** for data extraction and aggregation.
3. Perform **Exploratory Data Analysis (EDA)** using Python.
4. Build **charts & dashboards** inside Azure Data Studio.
5. Answer key **business questions** (sales, profit, discount impact, customer segments, etc.).

---

## 📊 Business Questions Answered
Some of the main insights we generated:
1. Total sales and profit per year.
2. Top-performing product categories and sub-categories.
3. Impact of discounts on profit margins.
4. Regional and state-level sales performance.
5. Shipping mode usage and efficiency.
6. Top 10 customers by sales and profit.
7. Monthly and quarterly sales trends.
8. Loss-making products despite high sales.
9. Correlation between sales, quantity, discount, and profit.
10. Customer segmentation by region and purchase behavior.

---

## 🚀 How to Run
1. Install requirements:
   ```bash
   pip install pandas matplotlib seaborn pyodbc
