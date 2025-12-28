## 📊 Sales & Customer Performance Dashboard (Tableau)

### 🔗 Live Dashboard
👉 [View Interactive Dashboard on Tableau Public](https://public.tableau.com/app/profile/gabriel.dos.santos6309/viz/Book1_17667727863160/SalesDashboard)

---

### 🖼 Dashboard Preview
![Sales & Customer Dashboard](./images/Sales%20Dashboard.png)
---

### 📌 Overview
This project features two interactive Tableau dashboards designed to help stakeholders analyze **sales performance**, **customer behavior**, and **year-over-year trends**.

- Sales KPIs: Total Sales, Profit, Quantity
- Customer KPIs: Customers, Orders, Sales per Customer
- Dynamic year selection, drill-downs, and filters


## User Story | Sales Performance

### Introduction
This user story outlines the specifications for building two dashboards using **Tableau** to help stakeholders—including sales managers and executives—analyze sales performance and customer behavior.

---

## Sales Dashboard | Requirements

### Dashboard Purpose
The purpose of the sales dashboard is to present an overview of sales metrics and trends in order to analyze **year-over-year sales performance** and better understand overall sales trends.

### Key Requirements

#### KPI Overview
- Display a summary of **Total Sales**, **Total Profit**, and **Total Quantity**
- Show values for both the **current year** and the **previous year**

#### Sales Trends
- Present monthly trends for each KPI for both the current year and the previous year
- Clearly identify months with the **highest** and **lowest** sales

#### Product Subcategory Comparison
- Compare sales performance across different **product subcategories**
- Include a comparison of **sales versus profit**

#### Weekly Trends for Sales & Profit
- Present weekly sales and profit data for the current year
- Display **average weekly values**
- Highlight weeks that are **above** and **below** the average to draw attention to performance variations

---

## Customer Dashboard | Requirements

### Dashboard Purpose
The customer dashboard provides an overview of customer data, trends, and behaviors to help marketing teams and management better understand **customer segments** and improve **customer satisfaction**.

### Key Requirements

#### KPI Overview
- Display the **total number of customers**
- Display **average sales per customer**
- Display the **total number of orders**
- Show metrics for both the **current year** and the **previous year**

#### Customer Trends
- Present monthly trends for each customer KPI for both the current year and the previous year
- Clearly identify months with the **highest** and **lowest** sales

#### Customer Distribution by Number of Orders
- Represent the distribution of customers based on the **number of orders placed**
- Provide insights into customer **behavior, loyalty, and engagement**

#### Top 10 Customers by Profit
- Present the **top 10 customers** ranked by total profit
- Display additional details including:
  - Rank
  - Number of orders
  - Current sales
  - Current profit
  - Last order date

---

## Design & Interactivity Requirements

### Dashboard Dynamics
- Allow users to explore **historical data** by selecting any desired year
- Enable easy **navigation between dashboards**
- Make charts and graphs interactive, allowing users to **filter data directly from visualizations**

### Data Filters
- Product filters:
  - Category
  - Subcategory
- Location filters:
  - Region
  - State
  - City
