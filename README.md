# Mobile-sales-data-with-Power-bi
# 📊 Mobile Sales Data Analysis Dashboard

This project showcases an interactive Power BI dashboard that provides valuable insights into mobile phone sales across different regions, models, payment methods, and time periods.

---

## 🚀 Project Overview

The goal of this project is to analyze and visualize mobile sales data to help stakeholders make data-driven decisions. The dashboard is designed to track key metrics such as total sales, customer ratings, top-selling models, and month-over-month performance.

---

## 📂 Dataset Summary

The dataset includes:
- Customer Ratings
- Total Quantity & Transactions
- Total Sales (Monthly, Quarterly, Yearly)
- Mobile Brands & Models
- Payment Methods (UPI, Credit/Debit Cards)
- Sales by City, Month, and Day

---

💡 Insights Gained
Most sales occurred in major cities like Mumbai, Delhi, and Bangalore.

iPhone SE and OnePlus Nord were among the top-selling models.

Sales were highest in Q4, especially around festive months.

UPI and Credit Cards were the most preferred payment methods.


## 📌 Key Features

- ✅ **KPI Cards** for Quantity, Sales, Transactions, and Average Price
- 📍 **Sales by City** (Map Visual)
- 📅 **Monthly Trend Analysis**
- 🔝 **Top 3 Selling Mobile Models**
- 🎯 **Customer Ratings Breakdown (Good, Average, Poor)**
- 💳 **Transaction Count by Payment Method**
- 🕒 **Time Intelligence:** MTD, QTD, YTD, Same Period Last Year
- 📆 **Sales by Day of Week**

---

## 🧠 DAX Measures Used

- `Total Quantity`
- `Total Sales`
- `Total Transactions`
- `Average Rating`
- `Average Price Per Unit`
- `MTD`, `QTD`, `YTD`
- `Same Period Last Year`

Example:
```DAX
Rating Status = 
IF(
    Sales_Data[Customer Ratings] >= 4, "Good",
    IF(
        Sales_Data[Customer Ratings] > 2, "Average",
        "Poor"
    )



