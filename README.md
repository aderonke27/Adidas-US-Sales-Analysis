# Adidas-US-Sales-Analysis![Excel](https://img.shields.io/badge/Tool-Microsoft%20Excel-217346?style=flat&logo=microsoft-excel&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Domain](https://img.shields.io/badge/Domain-Retail%20%7C%20Sales%20Analytics-blue)

## Table of Contents
1. [Project Overview](#project-overview)
2. [Problem Statement](#problem-statement)
3. [Objectives](#objectives)
4. [Dataset Description](#dataset-description)
5. [Tools Used](#tools-used)
6. [Data Cleaning Process](#data-cleaning-process)
7. [Data Analysis](#data-analysis)
8. [Dashboard](#dashboard)
9. [Key Insights](#key-insights)
10. [Recommendations](#recommendations)
11. [Conclusion](#conclusion)
12. [Project Files](#project-files)
13. [Contact Information](#contact-information)

## Project Overview
This project presents a sales performance analysis of Adidas US operations using Microsoft Excel. The analysis covers sales transactions across five regions, six major retail partners, six product categories, and three sales channels from January to December.

The goal was to move beyond descriptive reporting and deliver strategic, actionable insights that answer the core business questions.

## Problem Statement
Adidas operates across a large and complex US retail landscape involving multiple regions, retailers, product lines, and sales channels. Without a structured view of performance across these dimensions, it becomes difficult to identify which areas are driving growth, which are underperforming, and where strategic resources should be focused.

This analysis was designed to address that gap by transforming raw transactional sales data into a clear, decision-ready performance overview.

## Objectives
* Evaluate total sales, operating profit, and operating margin across all dimensions
* Identify the highest and lowest performing regions by revenue and profitability
* Determine which retail partners and sales channels generate the most value
* Analyze product category performance to guide inventory and marketing decisions
* Uncover seasonal trends to support campaign and promotional planning
* Deliver strategic recommendations backed by data

## Dataset Description
The dataset used for this analysis is the Adidas US Sales Database, containing 9,648 transaction records spanning from January to December. Each row represents a single sales transaction and captures 13 fields covering retailer information, geographic location, product details, pricing, and financial performance metrics.

The Retailer and Retailer ID fields identify the six retail partners involved in the analysis — Foot Locker, West Gear, Sports Direct, Kohl's, Amazon, and Walmart. The Invoice Date records when each transaction occurred, enabling time-based and seasonal trend analysis. Geographic fields including Region, State, and City allow for location-based performance breakdowns across the five US regions — West, Northeast, Southeast, South, and Midwest.

On the product side, the Product field captures the category of item sold, covering six lines ranging from Men's Street Footwear to Women's Apparel. Price per Unit and Units Sold record the selling price and quantity for each transaction, while Total Sales captures the total revenue generated. Financial performance is measured through Operating Profit, which reflects profit after operating costs, and Operating Margin, which expresses profitability as a ratio per transaction. Finally, the Sales Method field identifies the channel through which each sale was made — either In-store, Online, or Outlet.

## Tools Used
Microsoft Excel — Data cleaning, pivot table analysis, dashboard development

## Data Cleaning Process
Before analysis, the dataset was reviewed and prepared to ensure accuracy and consistency:
* Date formatting — Invoice dates were stored as serial numbers and converted to proper date format (DD/MM/YYYY) for time-based analysis
* Data type validation — Numerical fields (Price per Unit, Total Sales, Operating Profit) were checked and formatted correctly as currency values
* The dataset was screened for duplicate transaction records
* Consistency checks — Product names, retailer names, and region labels were standardized for uniform grouping in pivot tables
* Fields were checked for blanks or null entries that could affect aggregation accuracy
* Margin values were confirmed as decimal ratios and formatted as percentages for readability

## Data Analysis
The analysis was structured across five key dimensions:
* Regional Performance: Sales and profitability were aggregated by region to identify geographic strengths and gaps across the West, Northeast, Southeast, South, and Midwest.
* Retailer Performance: Revenue and operating profit were broken down by all six retail partners — West Gear, Foot Locker, Sports Direct, Kohl's, Amazon, and Walmart — to evaluate partner value and contribution.
* Product Category Performance: All six product categories were analyzed for total revenue, units sold, and average operating margin to determine the most and least profitable lines.
* Sales Channel Analysis: Performance was compared across three sales channels — In-store, Online, and Outlet — by revenue, units sold, and operating profit to identify the most efficient distribution method.
* Monthly Trend Analysis: Monthly revenue and average price per unit were tracked across the full year to identify seasonal peaks, troughs, and pricing patterns.

## Dashboard
The project includes two interactive Excel dashboards built with PivotCharts, slicers, and conditional formatting:

Dashboard 1 — Regional and retailer performance overview with revenue and profit breakdowns
<img width="1548" height="809" alt="Screenshot (188)" src="https://github.com/user-attachments/assets/860c890f-5516-408b-8fd9-9b2a9ddf6268" />

Dashboard 2 — Product category analysis, monthly trends, and sales channel comparison
<img width="1538" height="802" alt="Screenshot (189)" src="https://github.com/user-attachments/assets/ea53bc5c-d282-4560-9a4e-7187efef5573" />

## Key Insights
Regional Performance
* The West region was the top-performing region with $269.9M in revenue and $89.6M in operating profit — the highest of all five regions
* The Midwest was the lowest performer with $135.8M in revenue and $52.8M in profit

Retailer Performance
* West Gear generated the highest total revenue at $242.9M, followed closely by Foot Locker at $220.1M
* Walmart was the lowest-performing retail partner with $74.6M in revenue
* West Gear also led in operating profit at $85.7M, indicating strong profitability alongside high revenue

Product Performance
* Men's Street Footwear was the top revenue-generating product at $208.8M with the highest operating margin of 44.6%
* Women's Athletic Footwear was the lowest revenue product at $106.6M
* Women's Apparel had the highest total units sold at 433,827 units, suggesting strong volume but lower price point

Sales Channel Performance
* In-store generated the highest operating profit at $127.6M, despite online having the highest unit sales at 939,093 units
* Online shows growing volume but lower per-unit profitability compared to in-store
* Outlet contributed the highest unit volume after online but had the lowest margin efficiency

Monthly Trends
* Sales peaked in July ($95.5M) and August ($92.2M), indicating strong summer demand
* The lowest sales month was March ($56.8M)
* Average price per unit was highest in December ($55.49) and lowest in March ($37.77), suggesting seasonal pricing strategies

## Recommendations
* Double down on the West region — With the highest revenue and profit, Adidas should prioritize marketing investment, inventory allocation, and retailer support in this region to defend and grow its leading position.
*  Strengthen the Midwest strategy — The Midwest significantly underperforms other regions. A targeted growth strategy including local promotions, increased online presence, and better retailer partnerships could unlock untapped revenue.
*  Prioritize Men's Street Footwear — As both the top revenue product and highest margin product (44.6%), this category should be the core of promotional campaigns and inventory investment.
*  Review Women's Athletic Footwear strategy — This category underperforms across both revenue and units. Adidas should evaluate whether pricing, product positioning, or retailer placement is limiting its growth.
*  Invest in online channel growth — Online already leads in unit volume. Improving online profitability through better pricing strategy and reduced fulfilment costs could make it the most valuable channel overall.
*  Leverage summer demand peaks — The July–August revenue peak should be anticipated with increased stock preparation, targeted campaigns, and promotional pricing to maximize capture of seasonal demand.
*  Re-evaluate the Walmart partnership — With the lowest revenue ($74.6M) and profit ($25.8M) among all retailers, Adidas should review whether the terms of the Walmart partnership are delivering sufficient commercial value.

## Conclusion
This analysis of Adidas US sales data revealed clear patterns in regional performance, retailer value, product profitability, and seasonal demand. The West region and Men's Street Footwear emerged as the strongest performers, while the Midwest and Women's Athletic Footwear present growth opportunities. The findings provide a data-backed foundation for Adidas to make more informed decisions about where to invest, which products to prioritize, and how to optimize its retail partnerships and sales channels for greater profitability.

## Project Files
[View main Excel workbook](./Adidas_US_Sales_Analysis.xlsx)

The Excel workbok contains:
* The raw data
* Analysis sheets
* Dashboards

## Contact Information
* Email: aladeloyeesther616@gmail.com
* LinkedIn: https://linkedin.com/in/estheraderonke
