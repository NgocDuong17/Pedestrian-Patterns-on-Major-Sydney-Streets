# Pedestrian-Patterns-on-Major-Sydney-Streets
## 📌 **Project Overview**

<img width="1154" height="646" alt="image" src="https://github.com/user-attachments/assets/1e686097-f14a-4c76-83c8-6d4581e8d6bb" />

 
This project explores pedestrian traffic patterns across four major streets (Bridge Street, Elizabeth Street, Market Street, and Park Street) from 2020 to early 2025. The goal was to perform robust data cleaning and transformation using Microsoft SQL Server, design a star schema for analytical querying, and build an interactive Power BI dashboard to uncover insights and recommend strategies for stakeholders such as urban planners, retailers, and public safety officials.

data source: https://data.cityofsydney.nsw.gov.au/datasets/66421e1dfe264bb19c76179ae92281cf_0/explore


## 🛠 **Tools & Technologies**
SQL Server – Data cleaning, transformation, and schema design

Power BI – Dashboard development and visualisation

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
- Line charts for the average of pedestrian count of the current week (hourly) compared to last week and last year
- Bar charts comparing average traffic across the day of the week.
- Column chart ranking locations by quarterly foot traffic, highlighting which streets consistently had the highest volume of pedestrians over time.
- Slicer filters enabled dynamic filtering by year range, allowing users to isolate specific time periods for focused analysis.
- 
<img width="311" height="58" alt="image" src="https://github.com/user-attachments/assets/5a168d66-67ab-464f-9861-1117feb1bca1" />

<img width="313" height="226" alt="image" src="https://github.com/user-attachments/assets/84385d1e-68b2-4352-835f-445e2bb62514" />


<img width="429" height="288" alt="image" src="https://github.com/user-attachments/assets/8d5016cc-526b-4a2e-9c86-87bb2c5913af" />


## 🔍 **Insights Discovered**
- Peak pedestrian activity consistently occurs between 1:00 PM – 5:00 PM (peak ar 5:00 PM), likely due to after-work traffic and shopping.
- Lowest pedestrian volume occurs from 11:00 PM – 5:00 AM, when most public and commercial activity is minimal.
- Thursday and Friday were consistently the busiest weekdays, indicating increased mid-to-late week engagement in city areas.
- Weekends showed moderate traffic but less than expected, suggesting a possible shift toward weekday urban activities. Park Street recorded the highest overall foot traffic across all periods.
- Market Street is closely followed as the second busiest street.
- Seasonal surges were recorded in February–March and November–December, likely driven by summer holidays, back-to-school periods, and holiday shopping
- 

## 💡 **Business Recommendations**
- Retailers and food outlets on Park and Market Streets should prioritise staffing and promotional campaigns during peak hours and months (late afternoon and holiday seasons).
- Transport services should increase frequency near 4–6 PM, especially on Thursdays and Fridays
- Consider pedestrian flow improvements (crosswalks, signage) in high-traffic areas to improve safety and flow.
- Use peak hours and peak locations for launching marketing campaigns or city events
- Digital signboards and billboards will see maximum impressions in Park and Market Streets during Feb–Mar and Nov–Dec.




## Screenshots
### 2020 (No data of last year - 2019)
<img width="1282" height="715" alt="image" src="https://github.com/user-attachments/assets/f02063b6-72a9-42fd-b133-c71f24f9b865" />


### 2021
<img width="1281" height="728" alt="image" src="https://github.com/user-attachments/assets/fe20331e-8ddd-4a37-a925-f1823863c6ca" />


### 2022
<img width="1282" height="719" alt="image" src="https://github.com/user-attachments/assets/3e31cbff-46a1-4e6f-87f9-17689a22e85f" />


### 2023
<img width="1280" height="715" alt="image" src="https://github.com/user-attachments/assets/02fbe23a-623a-41f6-af8a-ebdbb1539501" />


### 2024
<img width="1285" height="724" alt="image" src="https://github.com/user-attachments/assets/bb629d6d-3b63-421b-8002-c5adc5d9a96b" />


### 2025 (only have data until April)
<img width="1280" height="717" alt="image" src="https://github.com/user-attachments/assets/f0e912fc-6ca6-43b2-a6ce-bccee75ced02" />


