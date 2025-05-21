# Pedestrian-Patterns-on-Major-Sydney-Streets
## 📌 **Project Overview**
This project explores pedestrian traffic patterns across four major streets (Bridge Street, Elizabeth Street, Market Street, and Park Street) from 2020 to early 2025. The goal was to perform robust data cleaning and transformation using Microsoft SQL Server, design a star schema for analytical querying, and build an interactive Power BI dashboard to uncover insights and recommend strategies for stakeholders such as urban planners, retailers, and public safety officials.

  ![image](https://github.com/user-attachments/assets/8df619e2-dd9f-4fa6-b70f-3c70ca98afa5)

## 🛠 **Tools & Technologies**
SQL Server – Data cleaning, transformation, and schema design

Power BI – Dashboard development and visualization

DAX – Custom calculations for KPIs and trend analysis

Power Query – Data model refinement


## 📊 **Key Features**
### 🔄 **Data Preparation (SQL Server)**
Imported flat files and performed data quality checks:

Handled nulls, duplicates, and inconsistent datetime formatting

Built a staging table to hold raw data before final transformation

Transformed time-related fields:

Split Week into Year and Week Number

Generated accurate Day and Day No columns using DATENAME() and DATEPART()

Designed a star schema: 
- Fact_PedestrianCounts
- Dim_Date
- Dim_Location


### 📈 **Dashboard Highlights (Power BI)**
- Line charts for average of pedestrian count over time (hourly) compared to last week and last year
- Heatmaps showing pedestrian volume by month and location.
- Bar charts comparing average traffic across day of the week.
- Ribbon chart ranking locations by quarterly foot traffic, highlighting which streets consistently had the highest volume of pedestrians over time.
- Slicer filters enabled dynamic filtering by year range, allowing users to isolate specific time periods for focused analysis.
- KPI Cards showing the % short-term and long-term pedestrian movement changes (4-day moving average and 52 days in turn)

![image](https://github.com/user-attachments/assets/4f56275d-7fb3-47fc-b070-3910ed070f19)



## 🔍 **Insights Discovered**
- Peak pedestrian activity consistently occurs between 1:00 PM – 5:00 PM (peak ar 5:00 PM), likely due to after-work traffic and shopping.
- Lowest pedestrian volume occurs from 11:00 PM – 5:00 AM, when most public and commercial activity is minimal.
- Thursday and Friday were consistently the busiest weekdays, indicating increased mid-to-late week engagement in city areas.
- Weekends showed moderate traffic but less than expected, suggesting a possible shift toward weekday urban activities.Park Street recorded the highest overall foot traffic across all periods.
- Market Street followed closely as the second busiest street.
- Seasonal surges were recorded in February–March and November–December, likely driven by summer holidays, back-to-school periods, and holiday shopping
- 

## 💡 **Business Recommendations**
- Retailers and food outlets on Park and Market Streets should prioritize staffing and promotional campaigns during peak hours and months (late afternoon and holiday seasons).
- Transport services should increase frequency near 4–6 PM, especially on Thursdays and Fridays
- Consider pedestrian flow improvements (crosswalks, signage) in high-traffic areas to improve safety and flow.
- Use peak hours and peak locations for launching marketing campaigns or city events
- Digital signboards and billboards will see maximum impressions in Park and Market Streets during Feb–Mar and Nov–Dec.




## Screenshots
### 2020 (No data of last year - 2019)

![image](https://github.com/user-attachments/assets/fd6e9245-d5cf-469f-913e-5c4c62ac2682)

### 2021

![image](https://github.com/user-attachments/assets/faed73b3-1f7e-4958-bb2d-e9004fc0a022)

### 2022

![image](https://github.com/user-attachments/assets/3a550566-541c-475f-bdb0-95dfb73dd769)
### 2023

![image](https://github.com/user-attachments/assets/d963cc0e-d864-4956-a18f-7cb13180c878)

### 2024

![image](https://github.com/user-attachments/assets/74e8b60d-118d-4be8-9175-07d3433ebde0)

### 2025 (only have data until April)

![image](https://github.com/user-attachments/assets/e6604de3-4b53-48df-a30b-52372842d624)

