# Greenwich Retail Business Intelligence & Analytics Dashboard
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
