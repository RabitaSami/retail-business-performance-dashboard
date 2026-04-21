# Retail Business Performance Dashboard

## 📊 Project Overview

This project showcases an interactive Power BI dashboard built to analyse retail business performance across sales, profitability, warehouse operations, and customer behaviour.

The dashboard enables data-driven decision-making by uncovering key trends, inefficiencies, and high-performing areas within the business.

✔ Designed to simulate real-world business intelligence reporting used in data analyst roles

---

## 📷 Dashboard Preview

![Dashboard](dashboard/dashboard.png)

---

## 🔍 Key Business Insights

* **Sales Concentration:** A small number of product categories consistently generate the majority of total sales across all years (2023–2025)
* **Operational Efficiency:** Warehouse shipping preparation times are relatively consistent, with only minor variations between locations
* **Sales Performance:** Profit margins are similar across regions, indicating balanced performance among salespeople
* **Warehouse Strategy:** Underperforming warehouses contribute significantly less revenue and present opportunities for optimisation or consolidation
* **Customer Value:** A strong positive relationship exists between customer sales and profit, showing that high-value customers drive profitability

---

## 🧠 Analysis Questions Addressed

This dashboard answers key business questions:

1. What are the top product categories by net sales (2023–2025)?
2. Are there warehouses that take longer to prepare orders for shipping?
3. Which salesperson has the highest profit margin in each region?
4. Which warehouse(s) should be optimised or shut down based on performance?
5. What is the relationship between customer sales and profit?

---

## ⚙️ Data Preparation & Transformation

Data was cleaned and transformed in Power BI to ensure accurate analysis:

* Corrected data types (dates, numerical values, and text fields)
* Created key measures using DAX:
  * **Total Net Sales**
  * **Total Profit**
  * **Profit Margin (%)**
* Calculated **Shipping Preparation Time** using date differences
* Established relationships between datasets:
  * Sales Orders, Customers, Products, Salesperson, and Stores
* Applied **ranking logic (RANKX)** to identify top-performing salespeople by region
* Aggregated data by year, category, warehouse, and customer for analysis

---

## 📊 Data Model

A structured data model was built using a star schema:

- **Fact Table:** Sales Orders  
- **Dimension Tables:** Customers, Products, Salesperson, Stores  

This model enables efficient filtering, aggregation, and scalable analysis across multiple business dimensions.

---

## 🛠 Tools & Technologies

* **Power BI Desktop**
* **DAX (Data Analysis Expressions)**
* **Data Modelling & Transformation**
* **Excel / CSV datasets**

---

## 📂 Project Files

- **Dashboard**
  - `dashboard/Retail_Performance_Dashboard.pbix`
  - `dashboard/Retail_Performance_Dashboard.pdf`
  - `dashboard/dashboard.png`

- **Datasets**
  - `data/Customers.xlsx`
  - `data/Products.xlsx`
  - `data/Sales_Orders.xlsx`
  - `data/Salesperson.csv`
  - `data/Stores.xlsx`

---

## 📈 Key Features of the Dashboard

* KPI Cards for high-level performance metrics
* Comparative category analysis across multiple years
* Warehouse efficiency analysis
* Profit margin comparison by region
* Customer-level sales vs profit relationship (scatter plot with trendline)
* Clean and intuitive layout for easy interpretation

---

## 💡 Business Value

This dashboard provides actionable insights that can help organisations:

* Focus on high-performing product categories  
* Improve warehouse efficiency  
* Identify underperforming locations  
* Optimise sales strategies  
* Better understand customer profitability  

---

## 👤 Author

**Rabita Sami**  
Business Information Systems Student – Curtin University  

---

## 📌 Notes

This project was developed as part of an academic assignment using a structured dataset.  
All analysis and insights were derived using Power BI and reviewed for accuracy.
