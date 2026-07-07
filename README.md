# Greenwich Retail Business Intelligence Dashboard
An end-to-end Business Intelligence solution developed using Microsoft Power BI to transform retail transactional data into actionable business insights through interactive dashboards, KPI-driven reporting, dimensional data modeling, and business analytics.

## Project Overview

This project presents an end-to-end Business Intelligence solution developed for Greenwich Retail using Microsoft Power BI. The solution transforms transactional, customer, product, order, and regional data into interactive dashboards that support business performance monitoring, profitability analysis, customer insights, and strategic decision-making.

Using Power BI, Power Query, DAX, and dimensional data modeling, the project delivers an executive reporting solution that enables management to monitor key business performance indicators (KPIs), identify growth opportunities, evaluate operational performance, and support data-driven decision-making.

## Business Problem

Retail businesses generate large volumes of transactional data every day, but transforming that information into actionable business insights can be challenging. Decision makers require a clear understanding of sales performance, customer purchasing behaviour, product profitability, and regional trends in order to improve operational efficiency and maximise profitability.

This project demonstrates how Power BI can transform raw transactional data into an interactive business intelligence solution that supports data-driven decision making through dynamic dashboards, KPI monitoring, and visual analytics.

## Project Objectives

The primary objectives of this Business Intelligence project were to:

- Develop an interactive Power BI dashboard for executive reporting.
- Analyze sales performance across products, customer segments, and regions.
- Evaluate profitability using profit and profit margin metrics.
- Understand customer demographics and purchasing behaviour.
- Identify regional performance trends and business growth opportunities.
- Support data-driven strategic decision-making through KPI monitoring and visual analytics.

 ## Executive Summary & Key Performance Indicators (KPIs)

 The Executive Summary provides management with a concise review of the organization's overall business performance through the following key performance indicators (KPIs):

| KPI | Value |
|:--------------------------|---------:|
| Total Sales | **$470.53K** |
| Total Profit | **$61.62K** |
| Profit Margin | **13.10%** |
| Active Customers | **573** |
| Total Quantity Sold | **7,979** |
| Total Orders | **2,102** |
| Unique Orders | **1,038** |
| Average Order Value (AOV) | **$453.30** |

 ## Dataset

• Source: Greenwich Retail Sales Dataset (Excel)

|Dimension Tables |Description | 
|-------|-------------|
| Sales | Fact table containing all sales transactions. |
| Customer_dim | Customer demographic information used for customer segmentation and analysis. |
| Product_dim | Product details including category, sub-category, and product names. |
| Order_dim | Order information including order dates, shipping mode, and order attributes. |
| Location_dim | Geographic information including city, state, country, and region. |
| Calendar_dim | Date dimension used for time intelligence, trend analysis, and date-based reporting. |
| Calculations | DAX measures and calculated metrics used throughout the dashboard. |


## Data Preparation

Power Query was used to:

✓ Validate data types

✓ Clean and transform the dataset

✓ Create dimension tables

✓ Remove unnecessary columns

✓ Prepare the model for analysis

## Data Model

The Power BI semantic model follows a star schema design consisting of one fact table (Sales), five dimension tables (Customer_dim, Product_dim, Order_dim, Location_dim, and Calendar_dim), and one dedicated calculation table for DAX measures. This structure improves model performance, simplifies filtering, and supports efficient business analysis.

## Power BI Data Model (Star Schema)

<img width="1868" height="1128" alt="Relational Modeling" src="https://github.com/user-attachments/assets/6e53bf0a-2225-4993-bdff-2bd79d1ea682" />

## Model Highlights
- One central fact table (Sales)
- Five dimension tables for descriptive attributes
- Dedicated calculation table containing reusable DAX measures
- Optimized for interactive reporting

## Dashboard Overview

The Power BI solution consists of three interactive dashboards designed to support different levels of business analysis.

- **Dashboard 1 – Greenwich Sales Performance** - Executive overview of company performance, monthly sales trend, profitability, regional performance, and product categories. 
- **Dashboard 2 - Sales Performance Analysis** - Product profitability, regional sales performance, active customers, top-and low performing products, and operational insights.
- **Dashboard 3 - Customer Demography Analysis** – Customer segmentation, customer profitability, and purchasing behaviour analysis based on demographics, and shippment analysis.

  ## Dashboard 1 - Greenwich Sales Performance Dashboard

  <img width="2002" height="1114" alt="Sales-Dashboard_1" src="https://github.com/user-attachments/assets/7e8c9bb9-d980-4927-996a-5c0f1c65db03" />

  ### Key Business Insights

- Monthly sales followed four distinct performance phases: a volatile first quarter (January - March), a sustained decline during April–June, a steady recovery throughout July–September, and a sharp October downturn followed by a strong year-end rebound. November recorded the highest monthly sales at $76K.
- Furniture generated the highest sales revenue ($170.52K) but the lowest profit ($3K), making it the least profitable product category despite being the top revenue contributor. This presents opportunities to improve profitability through pricing optimization, supplier negotiations, cost management, and discount strategy reviews.

- The Top 10 most profitable products made a substantial contribution to overall company profit, highlighting high-value products that could be prioritized in future sales strategies.

## Dashboard 2 - Sales Performance Analysis Dashboard

<img width="1704" height="1030" alt="Sales_Dashboard_2" src="https://github.com/user-attachments/assets/9258250a-012c-47d6-9311-9a7d6cacc6ff" />

### Key Business Insights

- Technology delivered the highest profit ($34K) while generating lower sales than Furniture, demonstrating superior profitability.
- East generated the highest sales revenue ($156K), while West achieved the highest profit margin (14.64%), indicating the strongest profit efficiency among all regions.
- The Top 10 highest-selling products accounted for a significant proportion of total sales revenue, highlighting the company's dependence on a relatively small group of high-performing products.
- The least five sold products generated minimal sales, presenting opportunities for product portfolio review and inventory optimization.
- The West region recorded the highest number of active customers (276), followed by East (246), suggesting stronger customer engagement in these regions.

  ## Dashboard 3 – Customer Demographic Analysis Dashboard

  <img width="2008" height="1122" alt="Customer_Dashboard" src="https://github.com/user-attachments/assets/9969d885-cd50-44d8-bf96-91449c4d4a93" />

### Key Business Insights

- The Corporate customer segment generated the highest profit ($7.75K) approximately 47.6% of total segment profit, followed by the Consumer segment ($5.43K), while the Home Office segment contributed the lowest profit ($3.09K). This highlights the importance of the corporate customers as the company's most valuable customer group. Management should prioritize customer retention initiatives and strengthen relationships with corporate clients while identifying opportunities to increase profitability within the Consumer and Home Office segments through targeted marketing and product strategies.
- Standard Class was the most frequently selected shipping method and also generated the highest shipment-related profit ($9.68K), indicating that it played a significant role in both customer orders and overall business profitability, although the underlying reason why customers prioritized this mode cannot be determined from the available data.
- The Top 10 customers contributed a significant share of total profit, with Christopher Marr leading at approximately $3.2K, highlighting the importance of retaining high-value customers.
- Andrew Gjertsen and Peter Fuller were the most active customers, recording 75 and 68 purchases respectively, demonstrating exceptionally high engagement levels.
- Since a relatively small group of customers contributed significantly to the total profit, this emphasizes the importance of customer retention and personalized engagement strategies.
- California and New York generated the strongest profitability, making them the company's highest-performing states in terms of sales and profit contribution.

  ## Executive Summary Of Key Business Insights
  
- Sales performance followed distinct seasonal patterns, with a sustained decline during the second quarter followed by a strong recovery in the second half of the year
- Furniture generated the highest sales revenue but the lowest profit, making it the least profitable.
- Technology was the most profitable product category.
- Sales weakened during the second quarter before recovering strongly in the second half of the year.
- East generated the highest revenue, while West achieved the strongest profit efficiency.
- Corporate customers were the most profitable customer segment.
- Standard Class dominated customer shipping preferences.
- Standard Class generated the highest profitability over other shipping modes.
- The analysis identified a group of high-value products and customers that made significant contributions to overall business performance, highlighting opportunities for targeted retention and product optimization strategies.

  ## Business Recommendations

- **Improve Furniture profitability** by reviewing pricing strategies, supplier contracts, discount policies, and operational costs, as the category generated the highest sales revenue but the lowest profit.
- **Replicate successful operational practices from the West region** across other regions to improve overall profit margins, as West achieved the highest profitability efficiency despite lower sales than East. Such practices might be analyzing the operational, pricing, and sales practices used in the West region and identifying opportunities to implement similar strategies in the other regions.
- **Strengthen relationships with Corporate customers** through retention initiatives and tailored engagement strategies, while identifying opportunities to grow profitability within the Consumer and Home Office segments.
- **Prioritize high-performing products** while reviewing the commercial viability of consistently low-performing products through pricing adjustments, targeted promotions, or inventory optimization.
- **Continue optimizing Standard Class shipping**, as it was both the most frequently selected shipping method and the highest contributor to shipment-related profit.
- **Investigate seasonal sales patterns** to better understand the second-quarter decline and strong fourth-quarter recovery, supporting improved forecasting, inventory planning, and promotional strategies.

  ## Tools & Technologies
  
- Microsoft Excel
- Microsoft Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- Dimensional Data Modeling (Star Schema)
- Git 
- GitHub

## About the Author

This project was developed by Comfort Egbebu as part of her Business Intelligence portfolio. It demonstrates practical skills in Microsoft Power BI, Power Query, DAX, dimensional data modeling, and business performance analysis, while showcasing the ability to transform raw business data into actionable insights for decision-making.


## Project Resources

The repository includes:

- Business Intelligence Project Report (PDF)
- Dashboard screenshots
- Power BI project file (.pbix) 
- Source dataset (Excel files) 

  Thank you for taking the time to explore this project. Feedback and professional connections are always welcome.

