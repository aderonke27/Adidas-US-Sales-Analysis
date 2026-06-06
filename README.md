# Adidas-US-Sales-Analysis

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
11. [Limitations](#limitations)
12. [Conclusion](#conclusion)
13. [Project Files](#project-files)
14. [Contact Information](#contact-information)

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
| Field | Description |
|---|---|
| **Retailer** | Name of the retail partner (e.g., Foot Locker, Walmart, Amazon) |
| **Retailer ID** | Unique identifier for each retailer |
| **Invoice Date** | Date of the sales transaction |
| **Region** | US geographic region (West, Northeast, Southeast, South, Midwest) |
| **State** | State where the transaction occurred |
| **City** | City where the transaction occurred |
| **Product** | Product category (e.g., Men's Street Footwear, Women's Apparel) |
| **Price per Unit** | Selling price per unit |
| **Units Sold** | Number of units sold per transaction |
| **Total Sales** | Total revenue generated per transaction |
| **Operating Profit** | Profit after operating costs |
| **Operating Margin** | Profitability ratio per transaction |
| **Sales Method** | Channel through which the sale was made (In-store, Online, Outlet) |

**Dataset Summary:**
* Total Records: 9,648 transactions
* Total Revenue: $899,902,125
- Total Units Sold: 2,478,861
- Total Operating Profit: $332,134,761
- Average Price per Unit: $45.22
- Time Period: January – December (full year)

---

## Tools Used

- **Microsoft Excel** — Data cleaning, pivot table analysis, dashboard development
  - PivotTables — for multi-dimensional aggregation and breakdowns
  - PivotCharts — for visual representation of trends and performance
  - Conditional Formatting — for highlighting key performance indicators
  - Slicers — for interactive filtering on dashboards
  - Formulas — SUMIF, AVERAGEIF, calculated fields for KPI derivation

---

## Data Cleaning Process

Before analysis, the dataset was reviewed and prepared to ensure accuracy and consistency:

- **Date formatting** — Invoice dates were stored as serial numbers and converted to proper date format (DD/MM/YYYY) for time-based analysis
- **Data type validation** — Numerical fields (Price per Unit, Total Sales, Operating Profit) were checked and formatted correctly as currency values
- **Duplicate checks** — The dataset was screened for duplicate transaction records
- **Consistency checks** — Product names, retailer names, and region labels were standardized for uniform grouping in pivot tables
- **Missing values** — Fields were checked for blanks or null entries that could affect aggregation accuracy
- **Operating Margin formatting** — Margin values were confirmed as decimal ratios and formatted as percentages for readability

---

## Data Analysis

The analysis was structured across five key dimensions:

**1. Regional Performance**
Sales and profitability were aggregated by region to identify geographic strengths and gaps across the West, Northeast, Southeast, South, and Midwest.

**2. Retailer Performance**
Revenue and operating profit were broken down by all six retail partners — West Gear, Foot Locker, Sports Direct, Kohl's, Amazon, and Walmart — to evaluate partner value and contribution.

**3. Product Category Performance**
All six product categories were analyzed for total revenue, units sold, and average operating margin to determine the most and least profitable lines.

**4. Sales Channel Analysis**
Performance was compared across three sales channels — In-store, Online, and Outlet — by revenue, units sold, and operating profit to identify the most efficient distribution method.

**5. Monthly Trend Analysis**
Monthly revenue and average price per unit were tracked across the full year to identify seasonal peaks, troughs, and pricing patterns.

---

## Dashboard

The project includes two interactive Excel dashboards built with PivotCharts, slicers, and conditional formatting:

- **Dashboard 1** — Regional and retailer performance overview with revenue and profit breakdowns
- **Dashboard 2** — Product category analysis, monthly trends, and sales channel comparison

> 📁 Dashboard screenshots are available in the repository files below.

---

## Key Insights

**Regional Performance**
- The **West region** was the top-performing region with **$269.9M in revenue** and **$89.6M in operating profit** — the highest of all five regions
- The **Midwest** was the lowest performer with **$135.8M in revenue** and **$52.8M in profit**

**Retailer Performance**
- **West Gear** generated the highest total revenue at **$242.9M**, followed closely by **Foot Locker at $220.1M**
- **Walmart** was the lowest-performing retail partner with **$74.6M in revenue**
- **West Gear** also led in operating profit at **$85.7M**, indicating strong profitability alongside high revenue

**Product Performance**
- **Men's Street Footwear** was the top revenue-generating product at **$208.8M** with the highest operating margin of **44.6%**
- **Women's Athletic Footwear** was the lowest revenue product at **$106.6M**
- **Women's Apparel** had the highest total units sold at **433,827 units**, suggesting strong volume but lower price point

**Sales Channel Performance**
- **In-store** generated the highest operating profit at **$127.6M**, despite online having the highest unit sales at **939,093 units**
- **Online** shows growing volume but lower per-unit profitability compared to in-store
- **Outlet** contributed the highest unit volume after online but had the lowest margin efficiency

**Monthly Trends**
- Sales peaked in **July ($95.5M)** and **August ($92.2M)**, indicating strong summer demand
- The lowest sales month was **March ($56.8M)**
- Average price per unit was highest in **December ($55.49)** and lowest in **March ($37.77)**, suggesting seasonal pricing strategies

---

## Recommendations

1. **Double down on the West region** — With the highest revenue and profit, Adidas should prioritize marketing investment, inventory allocation, and retailer support in this region to defend and grow its leading position.

2. **Strengthen the Midwest strategy** — The Midwest significantly underperforms other regions. A targeted growth strategy including local promotions, increased online presence, and better retailer partnerships could unlock untapped revenue.

3. **Prioritize Men's Street Footwear** — As both the top revenue product and highest margin product (44.6%), this category should be the core of promotional campaigns and inventory investment.

4. **Review Women's Athletic Footwear strategy** — This category underperforms across both revenue and units. Adidas should evaluate whether pricing, product positioning, or retailer placement is limiting its growth.

5. **Invest in online channel growth** — Online already leads in unit volume. Improving online profitability through better pricing strategy and reduced fulfilment costs could make it the most valuable channel overall.

6. **Leverage summer demand peaks** — The July–August revenue peak should be anticipated with increased stock preparation, targeted campaigns, and promotional pricing to maximize capture of seasonal demand.

7. **Re-evaluate the Walmart partnership** — With the lowest revenue ($74.6M) and profit ($25.8M) among all retailers, Adidas should review whether the terms of the Walmart partnership are delivering sufficient commercial value.

---

## Limitations

- **No customer demographic data** — The dataset does not include age, gender, or customer segment information, which would have enabled deeper customer behaviour analysis
- **No cost of goods data** — Only operating profit and margin are available; gross margin analysis was not possible without cost of goods sold
- **Geographic granularity limited** — Analysis was done at region, state, and city level but lacked store-level data which would have enabled more granular retail performance insights
- **Single year of data** — Year-on-year comparison was not possible, limiting the ability to identify growth trends over time
- **No return or refund data** — Net sales could not be computed as product returns were not captured in the dataset

---

## Conclusion

This analysis of Adidas US sales data revealed clear patterns in regional performance, retailer value, product profitability, and seasonal demand. The West region and Men's Street Footwear emerged as the strongest performers, while the Midwest and Women's Athletic Footwear present growth opportunities. The findings provide a data-backed foundation for Adidas to make more informed decisions about where to invest, which products to prioritize, and how to optimize its retail partnerships and sales channels for greater profitability.

---

## Project Files

| File | Description |
|---|---|
| `Adidas_US_Sales_Analysis.xlsx` | Main Excel workbook containing raw data, analysis sheets, and dashboards |

---

## Contact Information

**Aladeloye Esther Aderonke**
Data & Business Analyst | Healthcare · Business · Finance

- 📧 Email: aladeloyeesther616@gmail.com
- 💼 LinkedIn: [linkedin.com/in/estheraderonke](https://linkedin.com/in/estheraderonke)
- 🐙 GitHub: [github.com/aderonke27](https://github.com/aderonke27)
- 📱 Phone: +234 810 636 6936

---

*This project was completed as part of a data analytics portfolio demonstrating business analysis, data visualization, and strategic thinking skills.*
