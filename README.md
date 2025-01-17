# Awesome Chocolates Dashboard: Optimizing Sales, Profitability, and Regional Performance

![brand-picture](Assets/Images/pic.png)


## Table of Contents
1. [Business Objective](#business-objective)
2. [User Story](#user-story)
3. [Key Points](#key-points)
4. [Ideal Solutions](#ideal-solutions)
5. [Dashboard Snapshot](#dashboard-snapshot)
6. [Process Overview](#process-overview)
   - [Data Cleaning](#data-cleaning)
   - [Data Exploration](#data-exploration)
   - [Analysis and Visualization](#analysis-and-visualization)
7. [Key Visuals Generated](#key-visuals-generated)
8. [Tools and Formula](#tools-and-formula)
9. [Insights Generated](#insights-generated)
   - [Sales Trend Analysis](#sales-trend-analysis)
   - [Regional Performance](#regional-performance)
   - [Product Performance](#product-performance)
   - [Sales Performance](#sales-performance)
10. [Actionable Recommendations](#actionable-recommendations)
11. [Conclusion](#conclusion)

---

## Business Objective
Evaluate the performance of Awesome Chocolate's sales and shipping operations from February 2023 to February 2024 across six countries (Australia, Canada, India, USA, New Zealand, and the UK) by analyzing total sales, profits, shipments, and product performance. The goal is to identify the most profitable months, regions, and products, and assess salesperson effectiveness to uncover actionable insights for sustained profitability and strategic decision-making.

---

## User Story
As a Data Analyst at Awesome Chocolate, I want to analyze the company’s sales, profits, shipments, and costs across six key regions (Australia, Canada, India, USA, New Zealand, and the UK), as well as assess the performance of individual products and sales personnel. This will help deliver actionable insights to stakeholders, enabling data-driven decisions that optimize operations, highlight top-performing products, reduce costs, and improve profitability.

---

## Key Points
- **Inconsistent Regional Performance**: Some regions show lower profits, reducing overall profitability.
- **Underperforming Products**: Low-margin products lack insights into why they underperform.
- **Seasonal Revenue Fluctuations**: Profits rely heavily on seasonal spikes.
- **Limited Salesperson Insights**: Limited visibility into individual performance hinders rewarding top performers or supporting others.

---

## Ideal Solutions
Develop a dynamic, interactive dashboard showcasing key metrics like sales, profits, salesperson performance, and product data. This will enable stakeholders to identify top-performing regions, optimize product strategies, and streamline logistics for improved profitability and operational excellence.

---

## Dashboard Snapshot
- **Key Metrics Displayed**:
  - Sales trend by month
  - Total sales by location
  - Salesperson performance and KPI ratings

---

## Process Overview
### Data Cleaning
- **Tools**: Excel, Power BI
- Import raw data and handle missing values.
- Standardize formats (dates, currency, categories).

### Data Exploration
- **Tools**: Excel, Power BI
- Analyze sales, profits, shipments, and costs.
- Generate summary statistics using DAX measures.

### Analysis and Visualization
- **Tools**: Power BI
- Create visualizations for:
  - Revenue and profit trends.
  - Shipment efficiency by region.
  - Product and salesperson performance.

---

## Key Visuals Generated
1. **Sales Trend by Month**: Line graph of sales trends.
2. **Total Sales by Location**: Column chart of sales by region.
3. **Salesperson Performance**: Table of salesperson KPIs.

---

## Tools and Formula
### DAX Measures
- **Total Sales**: `Total Sales = SUM('shipments'[Sales])`
- **Total Costs**: `Total Costs = SUM('shipments'[Cost])`
- **Profits**: `Total Profits = [Total Sales] - [Total Costs]`

---

## Insights Generated
### Sales Trend Analysis
- **Peak Months**: February 2023, December 2023 (Valentine’s Day, Christmas).
- **Low Months**: April 2023, November 2023 (off-peak opportunities).

### Regional Performance
- **Top Regions**: New Zealand, Australia.
- **Underperforming Region**: UK (highest shipment costs, low demand).

### Product Performance
- **Top Products**: Peanut Butter Cubes, Organic Choco Syrup.
- **Underperforming Products**: Caramel Stuffed Bars, Baker’s Choco Chips.

### Sales Performance
- **Top Performers**: Salespeople in New Zealand, Australia.
- **Underperformers**: Salespersons in the UK and Canada.

---

## Actionable Recommendations
1. **Stabilize Revenue Across Months**:
   - Launch targeted campaigns in April and November.
   - Offer seasonal promotions.
2. **Improve Regional Performance**:
   - Address inefficiencies in the UK.
   - Expand market share in high-performing regions.
3. **Optimize Product Portfolio**:
   - Promote high-margin products.
   - Redesign low-performing products.
4. **Enhance Logistics Efficiency**:
   - Consolidate shipments.
   - Optimize routes.
5. **Boost Sales Team Effectiveness**:
   - Use performance dashboards.
   - Provide coaching for underperformers.

---

## Conclusion
The analysis highlights seasonal dependency in revenue, with opportunities to stabilize profits in off-peak months. Investments in high-performing regions, products, and logistics can drive sustained growth. By leveraging insights, Awesome Chocolate can make data-driven decisions for future success.

---

**Thank you for reading!**
