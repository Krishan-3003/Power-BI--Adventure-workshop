# Adventure Works Sales Analysis Dashboard

## 📊 Project Overview

The **Adventure Works Sales Analysis Dashboard** is a data analytics and business intelligence project designed to analyze sales performance, production costs, profit, orders, products, customers, and regional sales.

The dashboard provides an interactive view of business performance and helps identify sales trends, profitable periods, top-performing products, key customers, and regional performance.

This project demonstrates practical skills in **Data Cleaning, Data Transformation, Data Modeling, DAX, Data Visualization, and Business Intelligence using Power BI**.

---

## 🎯 Project Objectives

The main objectives of this project were:

- Analyze overall sales performance.
- Track total sales, production cost, orders, and profit.
- Analyze sales trends across different years and months.
- Compare sales with production costs.
- Identify top-performing products.
- Identify top customers based on sales.
- Analyze sales performance across different regions.
- Calculate and monitor profit margin.
- Build an interactive and user-friendly dashboard.
- Provide meaningful business insights to support data-driven decisions.

---

## 🛠️ Tools & Technologies

- **Power BI**
- **Power Query**
- **DAX**
- **Microsoft Excel**
- **SQL**
- **Data Modeling**
- **Data Visualization**

---

## 📌 Key KPIs

The dashboard tracks the following major KPIs:

| KPI | Description |
|---|---|
| Total Sales | Overall revenue generated from sales |
| Total Production Cost | Total cost associated with production |
| Total Orders | Number of orders processed |
| Total Profit | Profit generated from sales |
| Profit Margin % | Profit as a percentage of sales |

---

## 📈 Dashboard Features

### 1. Sales by Year

The dashboard provides a year-wise comparison of sales performance.

It helps identify:

- Highest and lowest sales years
- Year-over-year sales trends
- Changes in business performance over time

---

### 2. Sales by Month

Monthly sales are visualized using a line chart to understand sales trends throughout the year.

The analysis helps identify:

- High-performing months
- Low-performing months
- Monthly sales growth patterns
- Seasonal sales trends

---

### 3. Sales by Quarter

A quarterly sales analysis is included to compare performance across:

- Q1
- Q2
- Q3
- Q4

This helps understand which quarters contribute most to overall sales.

---

### 4. Sales vs Production Cost

The dashboard compares monthly:

- Sales
- Production Cost

This comparison helps analyze the relationship between revenue and production expenses and provides a better understanding of profitability.

---

### 5. Top 5 Products by Sales

The dashboard identifies the top five products based on sales.

This helps the business understand:

- Best-selling products
- Products generating higher revenue
- Product-level sales contribution

---

### 6. Top 5 Customers by Sales

The dashboard displays the top five customers based on sales.

This can help businesses understand their major customers and analyze customer-level revenue contribution.

---

### 7. Sales by Region

Regional sales performance is visualized to compare sales across different geographical regions.

The analysis helps identify:

- High-performing regions
- Low-performing regions
- Regional sales contribution

---

## 🔍 Dashboard Filters

The dashboard includes interactive filters such as:

- **Month**
- **Region**
- **Year**

These filters allow users to analyze the data based on specific time periods and geographical regions.

---

## 📊 Sample Dashboard Metrics

In the displayed dashboard view, the following metrics are shown:

- **Total Sales:** 29.36M
- **Total Production Cost:** 17.28M
- **Total Orders:** 60,398
- **Total Profit:** 12.08M
- **Profit Margin:** 41.1%

> Note: KPI values change depending on the selected dashboard filters.

---

## 💡 Key Business Insights

Based on the dashboard analysis:

- Sales performance varies significantly across different years.
- Monthly sales show changing trends throughout the year.
- Quarterly analysis helps identify major contributors to annual sales.
- A comparison between sales and production cost provides visibility into profitability.
- A small group of products contributes significantly to overall sales.
- Top customers make an important contribution to revenue.
- Sales performance differs considerably across geographical regions.
- Profit margin provides an overall view of business profitability.

---

## 🧹 Data Preparation

The dataset was prepared before creating the dashboard.

The data preparation process included:

1. Removing unnecessary columns and records.
2. Handling missing and incorrect values.
3. Formatting columns appropriately.
4. Creating required calculated fields.
5. Creating additional time-based fields such as:
   - Year
   - Month
   - Quarter
6. Preparing the data for analysis.
7. Creating relationships between tables.
8. Validating the data before visualization.

---

## 🧮 Data Modeling & DAX

A structured data model was created to support efficient analysis.

DAX was used to create important business measures such as:

- Total Sales
- Total Production Cost
- Total Orders
- Total Profit
- Profit Margin %
- Monthly Sales
- Quarterly Sales
- Product Sales
- Regional Sales

Example calculation:

```DAX
Profit Margin % =
DIVIDE(
    [Total Profit],
    [Total Sales],
    0
)
 ## Snapshot
https://github.com/Krishan-3003/Power-BI--Adventure-workshop/blob/main/adventure%20dashboard.png
