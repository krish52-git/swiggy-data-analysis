# 🍽️ Swiggy Data Analysis Project (SQL)

## 📌 Project Overview

This project focuses on analyzing Swiggy food delivery data using SQL to extract meaningful business insights. The goal is to understand customer behavior, restaurant performance, delivery efficiency, and overall business trends.

---

## 🎯 Objectives

* Analyze order trends and revenue
* Identify peak ordering hours
* Find top-performing restaurants and food items
* Understand customer behavior and retention
* Evaluate delivery performance
* Detect business issues like delays or cancellations

---

## 🐍 Python Visualization
- <a href="https://github.com/krish52-git/swiggy-data-analysis/blob/main/swiggy_data.ipynb">
In addition to SQL analysis, Python (Pandas & Matplotlib) was used to:

- Visualize top cities by order volume
- Analyze restaurant revenue distribution
- Understand category-wise demand


## 📂 Dataset## 
- <a href="https://github.com/krish52-git/swiggy-data-analysis/blob/main/swiggy_data%20(2).csv">

The dataset contains Swiggy order details such as:

* Order ID
* User ID
* Restaurant Name
* Item Name
* Category
* Order Date & Time
* Amount
* Delivery Time
* Rating
* Status (Delivered/Cancelled)
* City

---

## 🛠️ Tools & Technologies

* SQL (PostgreSQL / MySQL)
  - <a href="https://github.com/krish52-git/swiggy-data-analysis/blob/main/Swiggy_SQL_Project_Krish.pdf">

---

## 📊 Key Business Questions Solved 

### 1. Total Orders & Revenue

* Measured overall business performance

### 2. Order Trends Over Time

* Analyzed daily/monthly growth patterns

### 3. Peak Order Hours

* Identified busiest time slots

### 4. Top Selling Items

* Found most popular food items

### 5. Top Restaurants

* Ranked restaurants based on revenue

### 6. Orders by Location

* Identified high-demand cities

### 7. Average Order Value (AOV)

* Measured customer spending behavior

### 8. Delivery Performance

* Evaluated average delivery time

### 9. Customer Retention

* Identified repeat customers

### 10. Rating Analysis

* Measured customer satisfaction

### 11. Category-wise Performance

* Found most popular food categories

### 12. Late Deliveries

* Identified operational issues

### 13. High-Value Customers

* Found top spending users

### 14. Monthly Growth

* Tracked business expansion

### 15. Cancellation Analysis

* Measured order failures

---

## 🔍 Sample SQL Query

```sql
SELECT restaurant_name, SUM(amount) AS revenue
FROM swiggy
GROUP BY restaurant_name
ORDER BY revenue DESC
LIMIT 10;
```

---

## 📈 Key Insights

* Peak orders occur during evening hours
* Certain restaurants consistently generate higher revenue
* A small group of customers contributes significantly to revenue
* Delivery delays impact customer ratings
* Some cities show higher demand compared to others

---

## 💡 Conclusion

This project demonstrates how SQL can be used to analyze real-world business data and generate actionable insights. It highlights important metrics that can help improve operations, customer experience, and revenue.

---

## 🚀 Future Improvements

* Build interactive dashboards using Power BI / Tableau
* Perform predictive analysis using Python
* Customer segmentation using machine learning

---

## 👨‍💻 Author

Krishnakumar M

---
