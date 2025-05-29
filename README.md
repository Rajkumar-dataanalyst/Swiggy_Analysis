# 🍽️ Swiggy Dashboard Project (SQL + Tableau)

## 🧾 Project Overview

This project is a comprehensive **Swiggy Dashboard** created using **Tableau Desktop**, powered by **MySQL** backend integration. The goal is to analyze and visualize food delivery metrics using structured KPI queries and visual storytelling. The dashboard is spread across **two interactive pages** with filters, parameters, and navigation options.

- 📂 Data Source: Excel (8 sheets)
- 🔄 Imported into: MySQL
- 🔗 SQL to Tableau connection established
- ✅ KPIs created using SQL and validated in Tableau with calculated fields
- 🖥️ Final Output: 2-page interactive dashboard

---

## 🛠️ Tools & Technologies Used

| Tool              | Purpose                                  |
|-------------------|------------------------------------------|
| **Tableau Desktop** | Dashboard design and interactivity      |
| **MySQL**           | Backend data storage and KPI querying   |
| **Microsoft Excel** | Raw data source (8 sheets)              |
| **SQL**             | KPI logic, data preparation             |
| **Tableau Calculated Fields** | Frontend KPI calculation & validation |
| **Filters & Parameters** | User-driven interactivity           |

---

## 🖼️ Page 1: Orders & Metrics

![Orders & Metrics](./Orders_and_Metrics.png)

### 🔹 Description:
This page provides an overview of order-related KPIs and customer behavior trends using multiple visual formats.

### 📌 KPIs:
- **Average Order Value (AOV)** – ₹1,044  
- **Repeat Customers %** – 58.00%  
- **Total Customers** – 6,329  
- **Order Cancellation Rate** – 20.93%

### 📊 Visuals:
- **App vs Web Amount** by City
- **Amount Trend** (Line Chart with Average Line)
- **Payment Methods** (Donut Chart)
- **City-wise Total Amount** (Bar Chart)
- **Order Status by Amount** (Pie Chart)

### 🧰 Interactive Features:
- **Filters**: `City`, `Year of Order Date`
- **Parameter Control**: Switch between `Amount`, `Revenue`, and `Orders`
- **Navigation Buttons**: Page-to-page switch

---

## 🖼️ Page 2: Customers & Delivery

![Customers & Delivery](./Customers_and_Delivery.png)

### 🔹 Description:
This page zooms into customer loyalty, delivery patterns, and restaurant-level performance.

### 📌 KPIs:
- **On-Time Delivery %** – 33.66%  
- **Customer Satisfaction Score (CSS)** – 1.997  
- **Total Revenue** – ₹1,04,33,244  
- **Active Delivery Agents** – 1,000

### 📊 Visuals:
- **Delivery Status**: On-Time, Late, Cancelled
- **Repeated Customers** by City (Bar Chart)
- **Vehicle Type** used by delivery agents (Bubble Chart)
- **Member Status** (Gold, Platinum, Regular)
- **Top 3 Restaurants** by performance
- **Food Preferences vs Delivery Outcome** (Matrix-style display)

### 🧰 Interactive Features:
- **Filters**: `Year of Order Date`, `City`
- **Parameter Control**: Choose `Amount`, `Revenue`, or `Orders`
- **Navigation Buttons**: Jump between dashboard pages

---

## 🔄 KPI Development Workflow

1. **Data Preparation**:
   - Imported 8 Excel sheets into **MySQL**
   - Structured tables and relationships built in SQL

2. **SQL-Based KPIs**:
   - Wrote SQL queries to generate all key metrics
   - Verified metric logic and output in SQL

3. **Tableau Dashboarding**:
   - Connected Tableau to MySQL
   - Created KPIs using **calculated fields** in Tableau
   - Cross-validated Tableau results with SQL queries

4. **Dashboard Design**:
   - Created **2 pages**: “Orders & Metrics” and “Customers & Delivery”
   - Added **filters, parameters, and navigation** for seamless analysis

---

## ✅ Conclusion

This project showcases end-to-end BI skills combining:
- **SQL data modeling**
- **Calculated KPIs**
- **Advanced Tableau visualization**
- **Interactive UX with filters and parameters**

The result is a professional-grade dashboard ready for stakeholder reporting, executive overviews, or portfolio demonstration.

> 🧩 Ideal for showcasing business insights and analytical thinking in interviews or freelance projects.
