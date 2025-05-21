# Pedestrian-Patterns-on-Major-Sydney-Streets
##📌 **Project Overview**
This project explores pedestrian traffic patterns across four major streets (Bridge Street, Elizabeth Street, Market Street, and Park Street) from 2020 to early 2025. The goal was to perform robust data cleaning and transformation using Microsoft SQL Server, design a star schema for analytical querying, and build an interactive Power BI dashboard to uncover insights and recommend strategies for stakeholders such as urban planners, retailers, and public safety officials.

##🛠 **Tools & Technologies**
SQL Server – Data cleaning, transformation, and schema design

Power BI – Dashboard development and visualization

DAX – Custom calculations for KPIs and trend analysis

Power Query – Data model refinement

##📊 **Key Features**
###🔄 **Data Preparation (SQL Server)**
Imported flat files and performed data quality checks:

Handled nulls, duplicates, and inconsistent datetime formatting

Built a staging table to hold raw data before final transformation

Transformed time-related fields:

Split Week into Year and Week Number

Generated accurate Day and Day No columns using DATENAME() and DATEPART()

Designed a star schema:

Fact_PedestrianCounts

Dim_Date

Dim_Location

###📈 **Dashboard Highlights (Power BI)**
Hourly traffic trends: Line charts comparing current vs. previous week/year

Monthly heatmaps: Foot traffic by street and month

Day-of-week analysis: Bar charts showing average traffic by weekday

Quarterly ranking: Ribbon chart ranking busiest streets

KPI Cards: Short- and long-term change (4-day and 52-day rolling averages)

Dynamic Filters: Slicer to select year range

##🔍 **Insights Discovered**
Peak foot traffic occurs daily between 12 PM – 5 PM (with peak at 5PM)

Lowest pedestrian activity is from 11 PM – 5 AM

Thursday and Friday are the busiest weekdays

Park Street sees the highest volume, followed by Market Street

Seasonal spikes observed in Feb–Mar and Nov–Dec

##💡 **Business Recommendations**
Retail: Align store hours and marketing with peak traffic times (e.g., late afternoon, holidays)

City Planning: Improve infrastructure (signage, crosswalks) in high-traffic areas

Marketing: Target campaigns during seasonal spikes and in busiest locations

