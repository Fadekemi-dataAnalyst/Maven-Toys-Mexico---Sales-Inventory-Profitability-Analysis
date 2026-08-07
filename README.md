# Maven Toys Mexico-Sales Inventory Profitability Analysis

### Project Structure
- Project Overview
- Business Objectives
- Tools Used
- Dashboard Overview
- Key Business Insights
- Strategic Recommendations
- Conclusion



###  Project Overview

This Power BI project analyzes the **sales performance, profitability, inventory levels, and stockout events** of Maven Toys Mexico.
The goal was to transform raw sales and inventory data into an interactive dashboard that helps identify revenue trends, profitable product categories, inventory efficiency, store performance, and potential revenue losses caused by stockouts.
The analysis resulted in a five-page interactive Power BI dashboard covering Executive Summary, Profit Margin, Sales Trend, Stockout Events, and Inventory Analysis.


### Business Objectives

The analysis focused on answering key business questions:
- How much revenue is the business generating?
- Which product categories contribute most to revenue and profit?
- What is the company's overall gross margin?
- How is revenue changing over time?
- Which stores have the highest and lowest gross margins?
- How efficiently is inventory being managed?
- Which product categories have high Days of Inventory?
- Where are stockouts occurring?
- Which products and locations are associated with the highest estimated lost revenue?
- What strategic actions can improve profitability and inventory performance?


### Tools Used
- Power BI — Data modeling, DAX calculations, dashboard development and visualization
- Power Query — Data cleaning and transformation
- DAX — Measures, KPIs, profitability, inventory and stockout calculations
- Excel/CSV — Data source



### Dashboard Pages

#### Executive Summary
The Executive Summary provides an overview of the company's financial and operational performance.

**Key KPIs**
- Total Revenue: **MXN 14.4M**
- Gross Profit: approximately **MXN 4M**
- Gross Margin: **28%**
- Estimated Lost Revenue: approximately **MXN 799M**

**Revenue & Profitability**

Toys generated the highest revenue at approximately **MXN 5.1M**, with around **MXN 1.1M** in gross profit.
Other categories included:

| Product Category  |  Revenue | Gross Profit |
| ----------------- | -------: | -----------: |
| Toys              | MXN 5.1M |     MXN 1.1M |
| Art & Crafts      | MXN 2.7M |     MXN 0.8M |
| Electronics       | MXN 2.2M |     MXN 1.0M |
| Games             | MXN 2.2M |     MXN 0.7M |
| Sports & Outdoors | MXN 2.2M |    ~MXN 0.5M |

The dashboard also showed a difference in store profitability, with the Top 5 stores averaging around **32% gross margin**, compared with approximately **25%** for the Bottom 5 stores.


### Profit Margin Analysis
This page focuses on understanding profitability across product categories and store locations.

**Key findings**
The overall gross margin was approximately **28%**.
The analysis revealed differences in margin performance across categories and locations. For example, the matrix showed that Electronics had a **45% margin** overall, while Toys had approximately **21%**.
The Top 5 stores achieved approximately **32% gross margin**, while the Bottom 5 averaged approximately **25%**.

**Business implication**
This highlights an opportunity to investigate what the higher-performing stores are doing differently, including:
- Pricing strategies
- Product mix
- Cost management
- Inventory management
- Sales performance

These practices could potentially be replicated across lower-performing locations.


### Sales Trend Analysis

The Sales Trend page analyzes revenue performance over time and across different dimensions.

**Key findings**
The dashboard recorded:
- Total Revenue: approximately **MXN 14.4M**
- Prior Year Revenue: approximately **MXN 5.3M**
- YoY Growth: approximately **171.5%**
  
The monthly trend also revealed fluctuations in revenue throughout the period, making it possible to identify stronger and weaker trading months.

**Revenue by Day of Week**

The dashboard also examined revenue patterns across the week to help identify intra-week trading behavior.
This can support decisions around:
- Inventory planning
- Staffing
- Promotions
- Marketing campaigns
- Stock replenishment


### Stockout Events Analysis

This page investigates the potential impact of products being unavailable when customers want to purchase them.

**Key KPIs**
- Total Revenue: approximately **MXN 14M**
- Days Out of Stock: approximately **12K**
- Estimated Lost Revenue: approximately **MXN 799M**

The analysis also identified products with significant estimated lost revenue.
For example:
- Lego Bricks: approximately **MXN 46M**
- Magic Sand: approximately **MXN 32M**
- Colorbuds: approximately **MXN 29M**
- Action Figure: approximately **MXN 17M**
- Rubik's Cube: approximately **MXN 17M**

**Business implication**

The results indicate that stockouts may be a significant business concern, particularly for high-demand products.
Prioritizing replenishment for products with high estimated lost revenue could help reduce missed sales opportunities.


### Inventory Analysis

This page evaluates how efficiently inventory is being managed across products and locations.

**Key KPIs**
- Current Inventory Value: approximately **MXN 300K**
- Days of Inventory (DIO): **17.4 days**
- Benchmark: **30 days**

The company's overall DIO of **17.4** days is below the 30-day benchmark.
However, the category-level analysis showed that some categories carry relatively higher inventory levels.
Games had the highest DIO at approximately 20+ days, while Electronics had the lowest at approximately 13 days.
Inventory Value
The treemap was used to analyze inventory value across Product Category → Store Location, making it easier to identify where inventory is concentrated.
This helps management understand where capital is tied up in inventory and where inventory optimization may be required.







