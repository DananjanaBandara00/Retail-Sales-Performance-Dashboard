# Retail Sales Performance Dashboard

An interactive Power BI Business Intelligence project developed to analyze retail sales performance, profitability, customer segments, regional trends, product performance, and shipping activity.

## Project Overview

The Retail Sales Performance Dashboard transforms retail transaction data into an interactive analytical solution using Microsoft Power BI.

The project focuses on converting raw transactional data into meaningful business information that can support performance monitoring and data-driven decision-making.

The dashboard allows users to explore sales and profitability from multiple perspectives, including region, category, customer segment, product, customer, shipping method, and time.

## Business Problem

Raw retail transaction data can make it difficult for decision-makers to quickly understand overall business performance, identify high-performing regions and products, evaluate profitability, and recognize areas requiring further investigation.

This project addresses this challenge by providing a centralized interactive dashboard for monitoring sales, profit, orders, customer performance, product performance, and regional profitability.

## Business Objectives

The project aims to:

- Analyze overall sales and profitability performance.
- Develop KPIs for monitoring business performance.
- Compare sales performance across regions.
- Analyze product category and sub-category performance.
- Identify top-performing products and customers.
- Analyze customer segment performance.
- Examine sales and profit trends over time.
- Analyze sales performance by shipping method.
- Explore the relationship between discount and profitability.
- Provide interactive filtering for business users.
- Generate business insights and recommendations from the analysis.

## Dataset

The project uses a retail sales transaction dataset containing information related to:

- Orders
- Customers
- Products
- Categories and sub-categories
- Regions and states
- Customer segments
- Shipping methods
- Sales
- Profit
- Discount
- Quantity
- Order dates

The dataset supports analysis across time, geography, customers, products, sales, profitability, and shipping.

## Tools & Technologies

- **Microsoft Power BI** – Dashboard development and data visualization
- **Power Query** – Data preparation and transformation
- **DAX** – Measures and KPI calculations
- **Microsoft Excel** – Source dataset
- **Data Modeling** – Structuring related data for analysis

## Key Performance Indicators

| KPI | Result |
|---|---:|
| Total Sales | $2.33M |
| Total Profit | $292.30K |
| Total Orders | 5,111 |
| Average Sales per Order | $455.20 |
| Profit Margin | 12.56% |

## Dashboard Pages

### 1. Executive Dashboard

Provides a high-level overview of overall retail performance.

Key components:

- Total Sales
- Total Profit
- Total Orders
- Average Sales per Order
- Profit Margin
- Monthly Sales Trend
- Sales by Region
- Sales by Category
- Interactive filters

![Executive Dashboard](Images/01_Executive_Dashboard.png)

---

### 2. Sales Analysis

Provides detailed analysis of sales trends and product performance.

Key components:

- Top 10 States by Sales
- Top 10 Products by Sales
- Monthly Profit Trend
- Sales by Ship Mode
- Region, Category, Segment, and Year filters

![Sales Analysis](Images/02_Sales_Analysis.png)

---

### 3. Customer & Product Insights

Focuses on customer contribution, product profitability, and transaction-level analysis.

Key components:

- Top 10 Customers by Sales
- Top 10 Sub-Categories by Profit
- Sales by Customer Segment
- Discount vs Profit Analysis
- Detailed Sales Transactions

![Customer & Product Insights](Images/03_Customer_Product_Insights.png)

---

### 4. Business Insights

Provides a management-oriented view of sales and profitability.

Key components:

- Sales vs Profit by Region
- Sales Contribution by Category
- Profit Margin by Region
- Monthly Sales & Profit Trend
- Regional Performance Summary

![Business Insights](Images/04_Business_Insights.png)

## Key Business Insights

### Regional Performance

The West region generated the highest sales at approximately **$739.81K** and also achieved the highest regional profit margin at **14.98%**.

The Central region generated approximately **$503.17K** in sales but had the lowest regional profit margin at **7.92%**, indicating an area that warrants further investigation.

### Category Performance

Technology was the largest contributor to sales, generating approximately **$839.89K**, representing **36.1%** of total sales.

### Customer Segment Performance

The Consumer segment generated the highest sales at approximately **$1.17M**, followed by Corporate and Home Office.

### Shipping Performance

Standard Class was the dominant shipping method by sales, generating approximately **$1.38M**.

### Discount and Profitability

The Discount vs Profit analysis provides a basis for examining how discount levels vary alongside profitability across product categories. This highlights the importance of monitoring discounting practices and evaluating their effect on profitability.

## Business Recommendations

Based on the analysis, the following recommendations were identified:

1. **Investigate Central Region Profitability**  
   Analyze discount levels, product mix, pricing, operational costs, and customer/product profitability to understand the Central region's lower profit margin.

2. **Maintain and Learn from West Region Performance**  
   Identify the factors contributing to the West region's strong sales and profitability and evaluate whether successful practices can be applied to weaker-performing regions.

3. **Prioritize High-Performing Product Categories**  
   Monitor inventory availability, pricing, product assortment, and promotional activity for high-performing categories such as Technology.

4. **Review Discounting Strategy**  
   Evaluate whether higher discounts generate sufficient additional sales to justify their potential effect on profit margins.

5. **Develop Customer-Focused Strategies**  
   Consider targeted strategies for the Consumer segment while also evaluating customer profitability, purchase frequency, and retention.

6. **Monitor Regional KPIs Regularly**  
   Periodically monitor sales, profit, profit margin, and order volume to identify performance changes and support proactive decision-making.

## Data Model

The Power BI model is structured around the **Orders** transaction table with related supporting tables, including **People** and **Returns**.

![Data Model](Documentation/Data_Model.png)

## Project Structure

```text
Retail-Sales-Performance-Dashboard/
│
├── Dataset/
│   └── Dataset.xlsx
│
├── Power BI/
│   └── Retail Sales Performance Dashboard.pbix
│
├── Report/
│   └── Business Analysis Report.pdf
│
├
│
├── Images/
│   ├── 01_Executive_Dashboard.png
│   ├── 02_Sales_Analysis.png
│   ├── 03_Customer_Product_Insights.png
│   └── 04_Business_Insights.png
│
└── Documentation/
    └── Data_Model.png
