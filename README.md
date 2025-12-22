![Excel](https://img.shields.io/badge/Excel-217346?logo=microsoft-excel&logoColor=white)

# Excel-Streaming-Service-Dashboard
Excel workbook with synthetic streaming service data and interactive dashboards. Analyze demographics, subscriptions, watch behavior, and ratings directly in Excel. Includes anomalies for cleaning practice and showcases BI storytelling with pivot tables, slicers, and charts.

# 📊 Streaming Service Data Analysis

This repository contains an **Excel dataset (`SundaramSamaddar_CPDA_6.xlsx`)** capturing user behavior and subscription details for a fictional streaming service.  
It is designed for **data cleaning, transformation, and analytics practice** using tools like Power BI, Python, and SQL.

---

## 📂 Dataset Overview

The dataset includes **user-level records** with attributes related to demographics, subscription, and viewing behavior.

### Key Columns
- **User_ID** – Unique identifier for each user  
- **Age_Group** – Age bracket (18–24, 25–34, etc.)  
- **User_Name** – User’s name (anonymized)  
- **Primary_Watch_Time** – Preferred viewing time (Morning, Afternoon, Evening, Late Night)  
- **Join_Date / Last_Login** – Subscription start and last activity dates  
- **Active_Days** – Number of days user was active  
- **Monthly_Price** – Subscription fee in USD  
- **Watch_Hours / Average_Watch_Hour** – Total and average viewing hours  
- **Favorite_Genre** – Preferred content genre (Action, Drama, Sci-Fi, etc.)  
- **Active_Devices / Profile_Count** – Devices used and profiles created  
- **Total_Movies_Watched / Total_Series_Watched** – Content consumption metrics  
- **Country / Language_Preference** – Demographic attributes  
- **Payment_Method** – PayPal, Credit Card, Debit Card, Cryptocurrency  
- **Recommended_Content_Count** – Number of recommendations shown  
- **Average_Rating_Given** – Average rating provided by the user  
- **Has_Downloaded_Content** – Whether user downloaded content  
- **Membership_Status** – Active/Inactive  
- **Loyalty_Points** – Engagement score  
- **First_Device_Used** – Device used at signup  

---

## ⚠️ Data Quality Notes

Some anomalies are intentionally included for **ETL and data cleaning practice**:
- **Join_Date anomalies**: Certain rows contain placeholders like *“No. of Black Spaces”* or *“No. of Outliers with -ve Active days”*.  
- **Watch Hours vs Active Days mismatches**: Some users show unrealistic ratios (e.g., very high watch hours with few active days).  
- **Decimal precision issues**: Ratings such as `4.5999999999999996` need rounding.  
- **Duplicate names**: Multiple users share the same name but have different IDs.  
- **Payment diversity**: Includes modern methods like cryptocurrency for testing categorical handling.

---
