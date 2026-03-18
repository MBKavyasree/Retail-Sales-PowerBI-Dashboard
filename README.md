# 📊 Retail Sales Analytics Dashboard (Power BI)

## 🔗 Live Dashboard Preview
Screenshots available in the repository showcasing interactive Power BI visuals.

## 📌 Project Overview

This project presents an interactive **Retail Sales Analytics Dashboard** built using Power BI to analyze **100K+ sales transactions**. The dashboard provides insights into revenue trends, regional performance, customer demographics, and product category distribution to support data-driven decision making.

---

## 🎯 Objectives

* Analyze overall sales performance and revenue trends
* Identify top-performing regions and product categories
* Understand customer demographics and purchasing behavior
* Monitor key business KPIs

---

## 🛠️ Tools & Technologies

* Power BI
* Power Query
* DAX (Data Analysis Expressions)
* Data Modeling
* Data Visualization

---

## 📂 Dataset

* Retail Sales Dataset (100K records)
* Includes fields such as Sales Amount, Region, Category, Customer Demographics, and Date

---

## 📊 Dashboard Features

### 🔹 KPI Metrics

* Total Sales
* Total Orders
* Average Sales
* Average Discount

---

### 🔹 Sales Analysis

* Sales Trend Over Time
* Sales by Region

📸
![Sales Analysis](screenshots/sales_analysis.png)

---

### 🔹 Customer Analysis

* Sales by Customer Gender
* Customer Insights

📸
![Customer Analysis](screenshots/customer_analysis.png)

---

### 🔹 Product Analysis

* Sales Distribution by Product Category

📸
![Product Analysis](screenshots/product_analysis.png)

---

### 🔹 Dashboard Overview

📸
![Dashboard Overview](screenshots/dashboard_overview.png)

---

## ⚙️ Key DAX Measures

```DAX
Total Sales = SUM(sales_100k[Sales_Amount])

Total Orders = COUNT(sales_100k[Sales_ID])

Average Sales = AVERAGE(sales_100k[Sales_Amount])

Avg Discount = AVERAGE(sales_100k[Discount])
```

---

## 💡 Key Insights

* Certain regions contribute significantly higher revenue
* Product categories vary in sales contribution
* Customer demographics influence purchasing patterns
* Sales trends show fluctuations over time

---

## 🚀 How to Use

1. Download the `.pbix` file from the repository
2. Open in Power BI Desktop
3. Interact with slicers to explore insights

---

## 📁 Project Structure

```
Retail-Sales-PowerBI-Dashboard
│
├── dataset
│   └── sales_100k.csv
│
├── dashboard
│   └── Retail_Sales_Analytics_Dashboard.pbix
│
├── screenshots
│   ├── dashboard_overview.png
│   ├── sales_analysis.png
│   ├── customer_analysis.png
│   └── product_analysis.png
│
└── README.md
```

---

## 📈 Future Improvements

* Add sales forecasting
* Include customer segmentation analysis
* Enhance dashboard design with advanced visuals

---

## 👩‍💻 Author

Kavyasree
BTech AIML Student | Data Analytics Enthusiast

