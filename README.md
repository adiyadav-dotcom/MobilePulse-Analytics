# 📱 MobilePulse Analytics

## 📌 Project Title

**MobilePulse Analytics – Mobile Sales Performance Dashboard**

---

## 📖 Short Description

**MobilePulse Analytics** is an interactive **Power BI dashboard** developed to analyze mobile phone sales performance and transform raw sales data into meaningful business insights.

The dashboard provides an overview of sales performance through KPIs, charts, and interactive filters, allowing users to explore sales trends, product performance, quantities sold, pricing, and transaction activity.

---

## 🛠️ Tech Stack

* **Power BI** – Dashboard development and data visualization
* **DAX** – Creating calculated measures and KPIs
* **Power Query** – Data cleaning and transformation
* **Microsoft Excel** – Data storage and preparation

---

## 📊 Data Source

The raw mobile sales dataset used in this project was obtained from **Kaggle**.

The dataset was imported into Power BI and transformed using **Power Query** before being used for analysis and dashboard development.

---

# ✨ Features & Highlights

* 📊 Interactive mobile sales dashboard
* 💰 Total Sales KPI
* 📦 Total Quantity Sold KPI
* 💵 Average Price Per Unit KPI
* 🧾 Total Transactions KPI
* 🔎 Interactive filtering and data exploration
* 📈 Sales performance analysis
* 📱 Mobile/product performance analysis
* 📊 Easy-to-understand business visualizations
* 🧮 DAX-based calculations and measures
* 🧹 Data cleaning and transformation using Power Query

---

# 💼 Business Problems

The dashboard is designed to address common business questions such as:

* How much total sales have been generated?
* How many mobile units have been sold?
* What is the average price per unit?
* How many transactions have been recorded?
* Which products or categories contribute most to sales?
* How can sales performance be monitored more efficiently?
* How can raw sales data be converted into actionable business insights?

---

# 🎯 Goal of the Dashboard

The main goal of **MobilePulse Analytics** is to provide a centralized and interactive dashboard that helps users:

* Monitor overall sales performance
* Understand sales and quantity trends
* Analyze product performance
* Track important business KPIs
* Identify useful patterns in sales data
* Support data-driven business decision-making

---

# 📈 Key Visuals / Charts

The dashboard contains visualizations designed to provide a quick understanding of mobile sales performance.

### KPI Cards

* **Total Sales**
* **Total Quantity**
* **Average Price Per Unit**
* **Total Transactions**

### Charts & Visualizations

* 📊 **Sales by Mobile/Product** – Compares sales performance across products.
* 📈 **Sales Trend** – Helps identify changes in sales over time.
* 📦 **Units Sold Analysis** – Shows quantity performance.
* 💰 **Price Analysis** – Provides insights into pricing and average selling price.
* 🔍 **Interactive Filters/Slicers** – Allows users to explore specific segments of the data.

> *Note: The exact charts may vary depending on the visuals included in the final Power BI dashboard.*

---

# 📋 Business Report

The dashboard converts raw mobile sales data into an easy-to-understand business report.

It enables users to quickly evaluate:

**Sales → Quantity → Pricing → Transactions → Product Performance**

This provides a simple way to monitor business performance and identify areas that may require further analysis.

---

# 🧮 DAX Measures

The project uses DAX measures including:

1 : Average = AVERAGE(Sales_data[Price Per Unit]) 
2 : Total Quantity = SUM(Sales_data[Units Sold]) 
3 : Total Sales = SUMX(Sales_data,Sales_data[Units Sold]*Sales_data[Price Per Unit])
4 : Transactions = COUNTROWS(Sales_data) 

Details:
AVERAGE() → Finds the average of a numeric column.
SUM() → Adds all numbers in a column.
SUMX() → Performs a calculation row by row, then adds the results.
COUNTROWS() → Counts how many rows are in a table.
Sales_data[Column] → Refers to a specific column inside the Sales_data table.
Sales_data → Your Power BI sales table

These measures are documented separately in the `DAX` folder.

---

# 📸 Dashboard Screenshot

### MobilePulse Analytics Dashboard

![MobilePulse Analytics Dashboard](Screenshots/MobilePulse_Analytics_Dashboard.png)

You can also view the dashboard screenshot directly from the **Screenshots** folder in this repository.

---

# 📁 Project Structure

```text
MobilePulse-Analytics/
│
├── 📁 Dashboard/
│   └── MobilePulse_Analytics.pbix
│
├── 📁 Screenshots/
│   └── MobilePulse_Analytics_Dashboard.png
│
├── 📁 Dataset/
│   └── mobile_sales_data.xlsx
│
├── 📁 DAX/
│   └── DAX_Measures.txt
│
└── 📁 Documentation/
    └── Project_Documentation.pdf
```

---

## 🎯 Project Type

**Data Analytics | Business Intelligence | Power BI**

---

## 👨‍💻 Developed By

**Aditya Yadav**

BE – Artificial Intelligence & Machine Learning

---

⭐ If you find this project useful, feel free to explore the repository and review the dashboard, DAX measures, dataset, and documentation.
