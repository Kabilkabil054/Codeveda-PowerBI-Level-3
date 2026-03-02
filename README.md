📊 Sales Performance Analysis – Power BI Codveda Internship | Level 3 📌 Project Overview

This project was completed as part of the Codveda Power BI Internship – Level 3.

The main objective was to apply advanced Power BI concepts including:

Star Schema Data Modeling

Writing Advanced DAX Measures

Time Intelligence (YTD & YoY)

Dynamic Filtering (TopN Logic)

Multi-Year Trend Analysis

Professional Dashboard Design

This project analyzes multi-year sales data to understand business performance across cities, categories, and time periods.

--------------------------------------------------------------------------------------------------------------------------------------------------

📂 Dataset

Retail_Sales_Analytics.csv

A structured sales dataset containing:

Order Date

City

Category

Product

Sales

Profit

Quantity

Customer Type

The dataset includes multiple years (2022–2027) to enable time-based analysis.

--------------------------------------------------------------------------------------------------------------------------------------------------

🏗 Data Modeling

To follow best practices, a Star Schema model was created:

Fact_Sales → Main transaction table

Dim_Date → Date dimension (Year, Month, Quarter)

Dim_City → Unique city list

Dim_Product → Product details

Dim_Customer → Customer details

One-to-Many relationships were established between dimension tables and the fact table.

This improves performance and follows professional BI standards.

--------------------------------------------------------------------------------------------------------------------------------------------------

🧮 DAX Measures Created

The following measures were created using DAX:

Total Sales

Total Profit

Total Quantity

Profit Margin %

YTD Sales

Previous Year Sales

Year-over-Year (YoY) Growth %

These measures demonstrate understanding of:

SUM

DIVIDE

CALCULATE

SAMEPERIODLASTYEAR

TOTALYTD

Filter Context

--------------------------------------------------------------------------------------------------------------------------------------------------

🔐 Row-Level Security (RLS)

As part of Level 3 (Advanced), Row-Level Security was implemented to restrict data visibility based on user roles.

Role Created:

City_Filter

Filter Applied: Dim_City[City] = "Delhi" Testing:

Used “View As Role” feature to validate that users can only see data related to the assigned city.

This ensures secure and role-based data access in enterprise reporting environments.

--------------------------------------------------------------------------------------------------------------------------------------------------

⚡ Power Automate Integration

A Power Automate flow was integrated into the dashboard.

When the "Run Flow" button is clicked:

Selected Year

Total Sales

YoY Growth %

are automatically sent via Gmail.

This demonstrates workflow automation capability within Power BI.

--------------------------------------------------------------------------------------------------------------------------------------------------

📊 Dashboard Components 📌 KPI Section

YTD Sales

Total Profit

Profit Margin %

YoY Growth %

--------------------------------------------------------------------------------------------------------------------------------------------------

📈 Visual Analysis

Total Sales by City (Dynamic TopN filter applied)

Total Profit by Category

Monthly Sales Trend

YoY Growth % by Year

--------------------------------------------------------------------------------------------------------------------------------------------------

🎛 Interactive Filters

Year Slicer (2022–2027)

TopN Selection (3 / 5 / 10)

--------------------------------------------------------------------------------------------------------------------------------------------------

🔎 Key Insights

Sales performance varies across cities.

Certain product categories generate higher profits.

Monthly trends show seasonal variations.

YoY growth highlights business performance changes over years.

TopN feature helps identify best-performing cities dynamically.

--------------------------------------------------------------------------------------------------------------------------------------------------

🧰 Tools Used

Power BI Desktop

Power Query

DAX

Star Schema Modeling

--------------------------------------------------------------------------------------------------------------------------------------------------

✅ Project Status

✔ Level 3 Completed Successfully 🚀 ✔ Advanced Time Intelligence Implemented ✔ Dynamic KPI & Trend Analysis Created ✔ Professional Interactive Dashboard Designed

Ready for Advanced BI Challenges 🔥
