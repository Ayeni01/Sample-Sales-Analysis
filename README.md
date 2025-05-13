## Superstore Sales, Profit, and Customer Lifetime Value (CLV) Analysis Report

## Table of Contents

- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Data Source](#data-source)
- [Dataset Description](#dataset-description)
- [Tools Used](#tools-used)
- [Data Preparation and Cleaning](#data-preparation-and-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [KPI Development](#kpi-development)
- [Dashboard Explanation](#dashboard-explanation)
- [Insight Summary](#insight-summary)
- [Recommendations](#recommendations)
- [Conclusion](#conclusion)

# Superstore Sales, Profit, and Customer Lifetime Value (CLV) Dashboard
![Project 1a](https://github.com/user-attachments/assets/05d72dc9-0986-4ee8-a035-c9fd46ccf723)


### 📌 Introduction

This project provides a comprehensive Power BI dashboard analyzing retail operations from the popular Superstore dataset. It visualizes key metrics such as **Sales**, **Profit**, **Discounts**, and **Customer Lifetime Value (CLV)** across time, product categories, regions, and customer segments. Designed for strategic decision-making, the dashboard uncovers performance trends, high-value customer behaviors, and optimization opportunities.

---

### 📊 Project Overview

The objective of this dashboard is to transform raw sales data into an interactive reporting tool that supports:
- Real-time **performance monitoring**
- **Customer segmentation** via CLV analysis
- **Geographical sales breakdown**
- Insight into **discount impact**
- Seasonality tracking and **scenario-based forecasting**

---

### 🎯 Objectives

- Analyze sales and profit across time, regions, categories, and customer segments.
- Calculate and visualize **Customer Lifetime Value (CLV)**.
- Evaluate discount strategies and their effect on margins.
- Enable drillthrough for **product- and region-level deep dives**.
- Forecast seasonal trends using historical data.

---

### 🛠️ Tools & Technologies

- **Power BI** – Visualizations, dashboard development, DAX modeling
- **Microsoft Excel** – Initial data preparation
- **DAX** – Measures, KPIs, CLV calculation, forecasting logic
- **Superstore Dataset** – [Download here (Tableau)](https://www.tableau.com/sites/default/files/2021-05/Sample%20-%20Superstore.xls)

---

### 📂 Dataset Description

- ~10,000 sales transactions across 4 years
- Key fields:
  - `Order Date`, `Ship Date`, `Sales`, `Profit`, `Quantity`, `Discount`
  - `Customer ID`, `Segment`, `Region`, `Category`, `Sub-Category`, `Product Name`

---

### 🧹 Data Cleaning & Modeling

- Converted dates and financial fields to correct data types
- Created a custom **Date Table** for time intelligence
- Added calculated fields:
  - `Year`, `Month`, `Customer Lifespan`
  - `CLV Group` (High / Medium / Low)
- Built star schema with defined relationships

---

### 📊 Exploratory Data Analysis (EDA)

Visualized trends and distributions using:
- **Sales and Profit Over Time**: Identifies seasonality and year-over-year growth
- **Sales by Region and State**: Highlights geographic strengths
- **Category/Sub-category Performance**: Pinpoints top-performing products
- **Profit vs. Discount**: Reveals how discounting erodes margin
- **Segment Contribution**: Understands value from Corporate, Consumer, Home Office
- **CLV Analysis**: Detects customer value trends over time and geography

---

### 📌 Key Performance Indicators (KPIs)

- Total Sales
- Total Profit
- Average Discount
- Profit Margin
- **Customer Lifetime Value (CLV)** using:
CLV = Average Order Value × Purchase Frequency × Customer Lifespan
- Adjusted CLV with What-If Parameter for economic simulation

---

### 📈 Dashboard Features

- **Top-level KPIs** for real-time business health monitoring
- **Drillthrough pages** for Product and Region analysis
- **Dynamic filters** for Region, Category, Segment, Date, CLV Group
- **Forecasting with DAX trend lines**
- **CLV by Segment and Region**
- **High-value Customer Identification** with segmentation

---

### 💡 Insight Highlights

- **Technology** is the most profitable category
- **Furniture** suffers due to high discounting and low margins
- **West region** dominates in sales and contribution
- Q4 repeatedly shows peak sales performance
- **Top 20% of customers** drive over 80% of revenue
- High discount rates consistently lead to negative profit

---

### ✅ Recommendations

- Reduce discounting in low-margin categories (especially Furniture)
- Replicate West region strategies in underperforming regions
- Focus marketing and retention on **high-CLV customers**
- Prepare for seasonal spikes (Q4) with targeted campaigns
- Improve underperforming products or bundle them with top-sellers
- Use CLV segmentation for personalized marketing efforts

---

### 🧠 Conclusion

The dashboard delivers a full-scale business intelligence solution that connects product performance, customer behavior, and profitability insights. By integrating **seasonality analysis** and **economic simulations**, it equips business leaders with both retrospective and forward-looking capabilities.

---

### 🚀 Future Enhancements

- Real-time data integration using Power BI Service
- Churn prediction and CLV progression modeling
- RFM segmentation and customer clustering
- Automated alerts for performance anomalies
- Extended cross-filtering with AI visuals and natural language Q&A

### 📎 License

This project is for educational and portfolio purposes only.  
Dataset © Tableau Software – publicly available for learning.
