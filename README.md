# Data-Visualization-in-Power-BI
# 🛍️ Shop Nest Store – Power BI Business Analytics

## 📌 Project Overview

**Task:**  
To address key business analytics for a retail dataset by designing insightful and interactive **Power BI dashboards** that support management decision-making.

**Action:**  
- Analyzed Shop Nest Store retail data  
- Created calculated columns and measures using **DAX**  
- Designed interactive dashboards with KPIs, slicers, and drill-down capabilities  

**Result:**  
- Delivered user-friendly visuals such as **Combo Charts, Trend Lines, Bar Charts, Pie Charts, Maps, and Area Charts**  
- Enabled real-time filtering and drill-through analysis for customized business insights  
- Improved visibility into sales performance, delivery efficiency, customer behavior, and revenue trends  

---

## 🧰 Tools & Technologies Used

- **Power BI**
- **DAX (Data Analysis Expressions)**
- **Retail Sales Dataset**
- Data Modeling & Visualization Techniques

---

## 📊 Key DAX Measures & Calculated Columns
DAX
Total Revenue = SUM(Price) + SUM(Freight)
Total Orders = COUNT(Order_id)
AOV = [Total Revenue] / [Total Orders]
Is Delayed = IF(Customer_Delivery_Date > Estimated_Delivery_Date, "Delayed", "On Time")
Average Review Score = AVERAGE(Review_Score)
Date = DATE(YEAR(Purchase_Date), MONTH(Purchase_Date), DAY(Purchase_Date))

---

## 📌 KPIs (Cards)

- Total Revenue  
- Total Orders  
- Average Order Value (AOV)  

---

## 🎛️ Slicers

- Month  
- Delivery Status (Delayed / On-Time)  

---

## 📈 Business Analytics Tasks & Visualizations

### 1️⃣ Top Categories by Total Sales
- Identified **Top 10 product categories** by total price  
- Used **Column Chart** with **Top N filtering**

### 2️⃣ Delayed Order Analysis
- Analyzed **delayed vs on-time deliveries** by category  
- Used **Column Chart** and **Table visuals**

### 3️⃣ Monthly Comparison of Delayed vs On-Time Orders
- Created **monthly delivery performance comparison**  
- Enabled **Drill-down (Month → Day)** analysis

### 4️⃣ Payment Method Analysis
- Identified **most frequently used payment methods**  
- Visualized using **Donut Chart**

### 5️⃣ Product Rating Analysis
- Analyzed **Top 10 highest-rated** and **Bottom 10 lowest-rated** products  
- Used **Column Charts** with **Average Review Score**

### 6️⃣ State-wise Sales Analysis
- Identified **high and low-performing states**  
- Used **Map Visualization** with bubble size based on sales

### 7️⃣ Seasonal Sales Pattern Analysis
- Analyzed **Quarterly, Monthly, and Daily sales trends**  
- Used **Area Line Chart** with **Drill-down**

### 8️⃣ Revenue Trend Analysis
- Evaluated **total revenue growth over time (Yearly)**  
- Used **Area Line Chart** and **KPI Card**

---

## 🧭 Dashboard Navigation

Implemented **Page Navigation Buttons** using Power BI Actions for smooth navigation between:

- Summary  
- Delayed Orders  
- Monthly Comparison & Payments  
- Top & Bottom Categories  
- Revenue & Seasonal Sales  

---

## 📌 Key Insights

- Identified categories contributing most to revenue  
- Highlighted delivery delays impacting customer satisfaction  
- Revealed seasonal sales patterns and regional performance  
- Enabled management to make **data-driven business decisions**

---


⭐ *If you find this project useful, feel free to star the repository!*

