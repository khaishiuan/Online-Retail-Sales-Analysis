# 📊 Online Retail Sales Analysis using Python

An end-to-end exploratory data analysis (EDA) project using the **Online Retail** dataset from the UCI Machine Learning Repository. This project demonstrates the complete data analysis workflow, including data cleaning, feature engineering, visualization, and business insight generation using Python.

---

## 📌 Project Overview

The objective of this project is to analyze transaction data from a UK-based online retailer to understand business performance, identify top-performing products, and examine customer purchasing behaviour. The insights generated can support data-driven decisions related to inventory management, marketing, and customer retention.

---

## 🎯 Objectives

- Clean and preprocess raw transactional data.
- Evaluate overall sales performance using key performance indicators (KPIs).
- Identify best-selling products based on revenue and quantity sold.
- Analyze customer purchasing behaviour and loyalty.
- Generate actionable business recommendations based on analytical findings.

---

## 📂 Dataset

**Source:** UCI Machine Learning Repository

The dataset contains online retail transactions between **December 2010 and December 2011** for a UK-based online retailer.

### Dataset Features

| Column | Description |
|---------|-------------|
| InvoiceNo | Invoice number |
| StockCode | Product code |
| Description | Product description |
| Quantity | Number of products purchased |
| InvoiceDate | Date and time of purchase |
| UnitPrice | Price per unit |
| CustomerID | Unique customer identifier |
| Country | Customer country |

---

## 🛠️ Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Google Colab

---

## 🔄 Project Workflow

```
Raw Dataset
      │
      ▼
Data Understanding
      │
      ▼
Data Cleaning
      │
      ▼
Feature Engineering
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Visualization
      │
      ▼
Business Insights
      │
      ▼
Business Recommendations
```

---

# 📖 Project Structure

```
Online-Retail-Sales-Analysis/
│
├── notebook/
│   └── Online_Retail_Sales_Analysis.ipynb
│
├── figures/
│   ├── monthly_sales.png
│   ├── top_products_revenue.png
│   ├── top_products_quantity.png
│   ├── product_performance_matrix.png
│   ├── top_customers.png
│   ├── customer_segmentation.png
│
├── data/
│   └── Online Retail.xlsx
│
└── README.md
```

---

# 🧹 Data Preparation

The following preprocessing steps were performed before analysis:

- Removed duplicate records
- Removed cancelled transactions
- Removed missing Customer IDs
- Removed invalid quantities and prices
- Converted InvoiceDate to datetime format
- Created additional features including:
  - Revenue
  - Month
  - Day
  - Hour

---

# 📈 Analysis Performed

## 1. Sales Performance Analysis

Analyzed overall business performance using:

- Total Revenue
- Total Orders
- Total Customers
- Average Order Value
- Monthly Revenue Trend

### Key Insights

- Evaluated the overall financial performance of the business.
- Identified monthly sales trends and seasonal fluctuations.
- Provided recommendations for inventory planning and sales forecasting.

---

## 2. Best-Selling Products

Analyzed product performance through:

- Top 10 Products by Revenue
- Top 10 Products by Quantity Sold
- Product Performance Matrix (Revenue vs Quantity Sold)

Products were categorized into:

- ⭐ Star Products
- 💎 Premium Products
- 📦 Volume Products
- ⚠️ Low Performers

### Key Insights

- Identified products generating the highest revenue.
- Distinguished between high-volume and high-value products.
- Highlighted products requiring inventory prioritization or performance review.

---

## 3. Customer Analysis

Customer behaviour was analyzed using:

- Top Customers by Revenue
- Repeat Customer Analysis
- Customer Revenue vs Number of Orders
- Top Frequent Buyers

### Key Insights

- Identified high-value customers.
- Examined customer purchasing patterns.
- Evaluated customer loyalty and repeat purchase behaviour.
- Suggested strategies for customer retention and revenue growth.

---

# 💡 Key Findings

- Sales performance showed clear monthly trends that can support inventory planning.
- A relatively small number of products generated a significant proportion of total revenue.
- Customer spending was concentrated among a small group of high-value customers.
- Repeat customers represent an important opportunity for improving long-term profitability.
- Product and customer segmentation can support more targeted business decisions.

---

# 📌 Business Recommendations

Based on the analysis, the following recommendations are proposed:

- Prioritize inventory planning for high-performing products.
- Promote Star and Premium Products through targeted marketing campaigns.
- Strengthen customer retention using loyalty programmes and personalized promotions.
- Encourage repeat purchases through cross-selling and upselling strategies.
- Continuously monitor sales and customer KPIs to support data-driven decision-making.

---

# 📷 Sample Visualizations

The notebook includes visualizations such as:

- Monthly Revenue Trend
<img width="1189" height="490" alt="Monthly Revenue chart" src="https://github.com/user-attachments/assets/236999d6-341b-4c46-ba43-1261a20576ae" />

- Top Products by Revenue
<img width="1189" height="590" alt="Top Revenue Products" src="https://github.com/user-attachments/assets/49138e2b-e367-41e6-9e16-b03437688de8" />

- Top Products by Quantity Sold
<img width="1189" height="590" alt="Top 10 Quantity Sold" src="https://github.com/user-attachments/assets/bee7256a-d404-4c27-aef4-417ef85c56c8" />

- Top Customers by Revenue
<img width="989" height="590" alt="Top 10 Customers by Revenue" src="https://github.com/user-attachments/assets/3d1523b8-16fe-416f-abdd-79c742201f6b" />

- Top Frequent Buyers
<img width="1189" height="590" alt="Top 10 Frequent Buyers" src="https://github.com/user-attachments/assets/9d94173d-0516-4ae4-b10e-1eb672ca3578" />

---

# 🚀 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Visualization
- Customer Analytics
- Sales Analytics
- Business Insight Generation
- Python Programming
- Data Storytelling

---

# 📄 Project Summary

This project demonstrates an end-to-end retail sales analysis workflow using Python. By transforming raw transactional data into meaningful insights through data cleaning, visualization, and exploratory analysis, the project showcases practical data analytics skills that support business decision-making in areas such as inventory management, product performance evaluation, and customer retention.

---

## 👤 Author

**Fong Khai Shiuan (Sandra)**

Aspiring Data Analyst | Python | SQL | Power BI
