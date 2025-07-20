# 🏠 House Market Analysis – Power BI Project

This end-to-end data analysis project focuses on analyzing the housing market by integrating Power BI with Google BigQuery. The project covers data transformation to visualization and insight generation. Key tasks included writing SQL queries in BigQuery for data understanding, cleaning and shaping data using Power Query Editor, and building insightful visualizations using DAX functions. The final report includes sales performance by region, YOY growth by sales type, price trends, offer-to-purchase comparisons, and key influencers on house prices. The report was published to the Power BI Service.

---

##  Project Overview

**Objective:**  
To analyze housing sales data to understand market trends, evaluate regional performance, compare offer vs purchase prices, and identify key drivers influencing property prices.

**Tools Used:**
- **Power BI Desktop** – For data modeling and visualization
- **Google BigQuery** – As the primary data source
- **SQL** – For querying and transforming raw data
- **DAX** – For custom metrics and time-based calculations
- **Power Query Editor** – For data cleaning and preparation

---
##  Key Tasks Performed

###  Data Cleaning & Modeling
- Used **Power Query Editor** to clean, filter, and shape data.
- Created relationships and cleaned columns for analysis-ready structure.

### Calculations & DAX
- Created **YOY Sales Growth** using `CALCULATE`, `MAX`, `IF`, `BLANK`.
- Added **Units Sold** using `CALCULATE`, `DISTINCTCOUNT`, `YEAR`, `QUARTER`.
- Calculated **Last 12 Month Sales** using `DATESINPERIOD` and `SUM`.
- Built **Median Sales Price Change by Region** using `MEDIANX`.
- Used `TOTALYTD`, `SUM`, `ALLEXCEPT` for regional summaries.

### Visualizations & Report Pages

#### **Page 1: House Market Overview**
- KPI Cards: Total units sold, last 12-month sales
- Bar chart: Median sales price change by region
- Scatter chart: Offer price vs Purchase price
- Area chart: YOY Sales Growth by Sales Type

#### **Page 2: Sales Performance**
- Bar chart: Sales by Region
- Donut chart: Avg Price per Sqm by region
- Offer to SQM Ratio by Sales Type
- Table: Sales by Quarter, Month, Day (using `TOTALYTD`)

####  **Page 3: House Type Analysis**
- Clustered bar: Offer vs Purchase Price by House Type
- Combined bar & line: Average inflation, interest & yield vs price/sqm
- Inflation, interest, and yield breakdown by house type

###  Report Publishing
- Published Power BI report to **Power BI Service**
- Created new workspace and shared the report
- Used clear formatting, color themes, and layout for user-friendly UI

---
