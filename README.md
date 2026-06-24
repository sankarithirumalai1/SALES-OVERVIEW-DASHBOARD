
# Sales Overview Analysis| Power BI + SQL

## Project Overview

Designed and developed an interactive Sales Overview Dashboard to analyze business performance across multiple regions (Central, East, South, and West). The solution enables business users to monitor Sales, Profit, and Quantity metrics through dynamic KPI selection, year-based filtering, and year-over-year performance comparison. 

## Dataset Used

 * [Sales Dataset](Dataset/Sales_Data.xlsx)


## Key Features

* Dynamic KPI switching between Sales, Profit, and Quantity using parameter-driven measures.
* Multi-region sales performance analysis covering Central, East, South, and West regions.
* Year-over-Year (YoY) comparison with Current Year (CY) and Previous Year (PY) metrics.
* Interactive state-level sales analysis using Bubble Map and Bar Chart visualizations.
* Monthly trend analysis with custom sparklines and average reference lines.
* Dynamic filtering and cross-highlighting across all report visuals.
* Performance-focused DAX calculations for KPI tracking and trend analysis.

## Dashboard Reports

<img width="1151" height="652" alt="Sales_by_Product_Report page" src="https://github.com/user-attachments/assets/2ed51637-daba-43a2-97f1-51bdde2f29f9" />
<img width="1147" height="651" alt="Sales_By_Region_Report_Page" src="https://github.com/user-attachments/assets/17b53bbd-a8f8-495d-b467-54a905d5cd33" />

## Data Modeling & Transformation

* Performed data cleaning, validation, and quality checks using Power Query.
* Implemented dimensional data modeling following star schema principles.
* Created optimized relationships between fact and dimension tables.
* Developed reusable calculated measures and business logic using DAX.

## Security Implementation

* Implemented Row-Level Security (RLS) to restrict data visibility based on user roles and regional access requirements.
* Applied Object-Level Security (OLS) to secure sensitive business information and limit access to specific fields and measures.

## Advanced DAX & Analytics

* Dynamic Measure Selection using disconnected tables.
* Previous Year (PY) calculations using time intelligence functions.
* Year-over-Year Growth % calculations.
* Conditional KPI indicators and variance analysis.
* Custom trend analysis using monthly sparkline measures.
* Average benchmark calculations for performance monitoring.

## Dashboard Components

### Executive KPI Section

* Current Year Sales
* Current Year Profit
* Current Year Quantity
* Previous Year Comparisons
* YoY Growth Analysis

### Regional Performance Analysis

* Central Region Analysis
* East Region Analysis
* South Region Analysis
* West Region Analysis

### Geographic Sales Analysis

* State-wise Sales Distribution using Bubble Map
* Comparative State Performance using Bar Charts

### Detailed Performance Matrix

* CY Sales vs PY Sales
* CY Profit vs PY Profit
* CY Quantity vs PY Quantity
* YoY Variance Metrics

## Business Impact

* Enabled faster decision-making through self-service analytics.
* Improved visibility into regional sales performance and growth trends.
* Simplified year-over-year comparison and performance monitoring.
* Enhanced data security through role-based access controls.
* Reduced manual reporting effort through automated dashboard insights.

## Tools & Technologies

* Power BI
* Power Query
* Advanced DAX
* Data Modeling
* Row-Level Security (RLS)
* Excel / SQL Data Sources

  ## CONCLUSION

The dashboard successfully transforms raw sales data into meaningful business insights through interactive reporting, year-over-year analysis, regional performance monitoring, and geographic sales visualization. By leveraging Power BI, DAX, data modeling best practices, and security implementation, the solution enhances reporting efficiency, improves decision-making capabilities, and supports self-service analytics across the organization.


