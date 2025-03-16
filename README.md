### **📊 Supply Chain Dashboard for Cars**  

## 📌 **Project Overview**  
This Power BI project analyzes key business insights using an interactive Supply Chain Dashboard. It includes an Executive Summary Dashboard, Sales Performance Dashboard, and Customer Feedback & Insights Dashboard to optimize supply chain efficiency and decision-making.
---

## 📊 **Dashboards Included**  

1️⃣ **Executive Summary Dashboard** – High-level KPIs, including revenue, orders, and inventory trends.  
2️⃣ **Sales Performance Dashboard** – Sales analysis by category, time trends, and customer segments.  
3️⃣ **Customer Insights Dashboard** – Customer demographics, purchase behavior, and high-value customers.  
4️⃣ **Supply Chain Efficiency Dashboard** – Shipment tracking, delivery time analysis, and logistics efficiency.  

---
## 🔍 **Approach Used**  

✅ **Data Cleaning & Transformation**  
- Removed duplicates and handled missing values  
- Standardized date and currency formats  

✅ **Data Modeling**  
- Split data into multiple tables: **Orders, Customers, Products, Shipments, Calendar, Suppliers**  
- Created relationships using **primary and foreign keys**  

✅ **DAX Calculations**  
- **Total Sales** = `SUM(order_table[Sales])`  
- **Average Discount** = `AVERAGE(order_table[Discount])`  
- **Sales by Category** = `SUMX(RELATEDTABLE(product_table), order_table[Total Sales])`  
- **Total Orders** = `COUNT(order_table[OrderID])`  
- **Total Quantity** = `SUM(order_table[Quantity])`  

✅ **Visualization & Dashboard Creation**  
- Interactive Power BI reports  
- Custom visuals for detailed insights  
---
## 📈 **Key Business Insights**  

📌 **Sales Trends** – Identified peak sales months & seasonal trends.  
📌 **Customer Insights** – Analyzed high-value customers and buying patterns.  
📌 **Shipping Efficiency** – Optimized logistics by analyzing delivery times.  
---
## 📂 **Dataset Information**  
- **Source**: Downloaded from Kaggle  (https://www.kaggle.com/datasets/prashantk93/supply-chain-management-for-car?select=Car_SupplyChainManagementDataSet.csv)
---

## 🚀 **How to Use**  
1️⃣ **Download** the `.pbix` file.  
2️⃣ **Open in Power BI Desktop**.  
3️⃣ **Refresh data** to ensure up-to-date insights.  
4️⃣ **Explore dashboards** for detailed analysis.  

---

## 👤 **Author**  
- **Yathish G S**  
*(https://github.com/Yathish-1/Supply_chain_Dashboard_Cars)*  

---

## ⚖️ **License**  
This project is licensed under the **MIT License**.  

