# My-Excel-Projects-Repository
📊 Excel Data Analysis – Data Technician Bootcamp

A collection of hands-on Excel tasks completed during a Data Technician bootcamp, applying real-world data analysis techniques to retail and sales datasets.


🗂️ Project Overview

This project demonstrates practical Excel skills built across structured bootcamp sessions. Tasks involved cleaning, analysing, and visualising data from retail sales and bike sales datasets, progressing from foundational functions through to PivotTables and dynamic charts.


🛠️ Skills & Techniques

Formulas & Functions

FunctionPurposeSUM / SUMIFTotal sales figures and conditional summationsAVERAGE / AVERAGEIFMean calculations across full datasets and filtered subsetsDATE / MONTH / YEARExtracting and working with date componentsUNIQUEGenerating distinct value lists from columnsVLOOKUPCross-referencing values across tablesSWITCHCategorising data by condition (e.g. High / Medium / Low sales volume)

Data Management


Filtering – isolating records by criteria (e.g. age, region, product)
Sorting – ordering data by value, largest to smallest and custom sequences


PivotTables


Summarising sales by county, product, age group, gender, and country
Identifying top-performing markets and customer segments
Analysing profitability across multiple dimensions


Charts & Visualisation


Building charts from PivotTable data
Visualising sales trends and category breakdowns
Interpreting patterns across regions and demographics



📁 Datasets Used


retail-sales_dataset.xlsx – Retail transaction data used to practise sorting, filtering, and formula application
Bike_Sales_Pivot_Lab.xlsx – Multi-country bike sales data used for PivotTable analysis
Bike_Sales_Visualizations_Lab.xlsx – Sales data used to build and interpret charts
County Sales Dataset – Product sales across English counties, used for SWITCH function categorisation and PivotTable summarisation



📌 Key Tasks

Task 1 – Retail Sales Analysis

Applied SUM and AVERAGE to calculate total and average commission values. Practised filtering the Age column and sorting by Transaction ID.

Task 2 – Bike Sales PivotTable

Built a PivotTable across age group, gender, and country dimensions. Notable findings:


🇺🇸 United States was the most profitable country overall
🇦🇺 Australia recorded sales across all markets
Adults (25–64) generated the highest sales volume; women in this group led bike sales


Task 3 – County Sales: SWITCH Categorisation

Inserted a calculated column using SWITCH to label each row by sales volume:

excel=SWITCH(TRUE, C2 > 600, "High", C2 >= 300, "Medium", "Low")

Complemented with a PivotTable summarising sales by county and product type.

Task 4 – Data Visualisation

Created charts from bike sales data to surface trends across markets and demographics.


💡 What I Learned


How to combine functions like SUMIF, AVERAGEIF, and VLOOKUP to answer specific business questions
How PivotTables enable rapid multi-dimensional analysis without writing formulas
How the SWITCH function provides a cleaner alternative to nested IF statements
How chart choice and layout affect the clarity of data insights
