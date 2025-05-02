# 📊 Task 8 - Simple Sales Dashboard

## 🎯 Objective
Build a basic interactive dashboard using Power BI to visualize sales performance by **product category**, **region**, and **month**.

---

## 📁 Dataset
- **Name**: Superstore_Sales.csv
- **Columns Used**: Order Date, Region, Category, Sales, Profit

---

## 🛠 Tools Used
- Power BI (for dashboard design)
- Optional: Excel (for previewing the dataset)

---

## 📌 Steps Followed

1. **Imported Dataset** into Power BI.
2. **Created a new column** to convert Order Date to Month-Year format using:
   DAX
   MonthYear = FORMAT([Order Date], "MMM-YYYY")
