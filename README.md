# 📚 Online Bookstore Sales Analysis

## 📌 Project Overview

This project focuses on analyzing online bookstore sales data to understand sales performance, revenue trends, book popularity, customer behavior, and order status.

The project uses Python for data cleaning and Exploratory Data Analysis (EDA), and Microsoft Power BI for building an interactive sales dashboard.

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Microsoft Power BI
## 📸 Dashboard Preview

![Online Bookstore Dashboard](dashboard.png)
## 📂 Dataset Overview

The project includes three datasets:

- Orders Dataset
- Customers Dataset
- Products Dataset

**Dataset Summary:**

| Metric | Count |
|---|---:|
| Total Orders | 15,000 |
| Total Customers | 5,000 |
| Total Products | 4,000 |

## 🧹 Data Cleaning

Data cleaning was performed using Python and Pandas.

The following operations were performed:

- Handled missing values.
- Checked duplicate records.
- Converted order dates into datetime format.
- Standardized country and city names.
- Handled invalid quantity and product values.
- Checked customer and product ID matching.
- Prepared cleaned datasets for analysis.

## 📊 Exploratory Data Analysis (Python)

The following analyses were performed:

1. Overall Business Overview
2. Monthly Revenue Analysis
3. Product Performance Analysis
4. Genre-wise Revenue Analysis
5. Customer Analysis
6. Country-wise Revenue Analysis
7. City-wise Revenue Analysis
8. Order Status Analysis

## 📈 Power BI Dashboard

An interactive dashboard was created using Microsoft Power BI to monitor online bookstore sales performance.

### Key Performance Indicators (KPIs)

- Total Customers: 5K
- Total Orders: 15K
- Total Quantity Sold: 69K
- Total Revenue: 109.46M

### Dashboard Visualizations

- Top 5 Selling Books by Revenue
- Revenue by Genre
- Orders by Status
- Monthly Sales Trend
- Country-wise Analysis

### Interactive Filters

- Genre
- Country
- Order Date

## 🔍 Key Business Insights

- Total recorded revenue is approximately 109.46M.
- India generated the highest revenue among the analyzed countries.
- Sci-Fi was the highest revenue-generating genre.
- October 2023 recorded the highest monthly revenue.
- Completed orders accounted for 39.37% of total orders.
- Pending orders accounted for 20.23%.
- Cancelled orders accounted for 19.79%.

## 💡 Business Recommendations

- Focus on high-performing book genres.
- Monitor monthly revenue fluctuations.
- Improve order completion rates.
- Investigate pending and cancelled orders.
- Improve customer and product data consistency.
- Plan promotional campaigns based on sales trends.

## ⚠️ Data Limitations

- Some customer IDs do not match between Orders and Customers datasets.
- Some product IDs do not match between Orders and Products datasets.
- Missing customer, city, and order status information was found.
- May 2026 revenue may represent an incomplete month.
- Payments recorded for pending and cancelled orders require further verification.

## 📁 Project Structure

```text
Online-Bookstore-Sales-Analysis/
│
├── data/
│   ├── Cleaned_Orders.csv
│   ├── Cleaned_Customers.csv
│   └── Cleaned_Products.csv
│
├── charts/
│   ├── monthly_revenue.png
│   ├── top_products.png
│   └── other_charts.png
│
├── notebooks/
│   └── Retail_Sales_Analysis.ipynb
│
├── online_bookstore_sales.pbix
│
└── README.md
```

## 👨‍💻 Author

**Krishna Yadav**

Aspiring Data Analyst

**Skills:** Python | SQL | Excel | Power BI | Data Analysis

---

⭐ If you find this project interesting, feel free to explore the repository!
