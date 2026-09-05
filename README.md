# Pharmaceutical Sales Performance Dashboard

## Project Overview

This is a self-created Power BI project designed to analyze pharmaceutical sales performance and generate actionable business insights.The dashboard evaluates sales performance across products, regions, territories, and sales representatives while comparing actual revenue against sales targets.

> Note: This project uses a simulated/self-created dataset for portfolio and learning purposes and does not represent actual company data.

## Business Objective 
* The main objectives of this project are to:
  Analyze overall sales and profitability
  Track actual revenue against sales targets
  Identify high-performing products and regions
  Analyze territory-level performance
  Evaluate sales representative performance
  Identify target achievement gaps
  Generate actionable business insights

## Tools & Technologies 
* Power BI — Dashboard development and visualization
* Power Query — Data cleaning and transformation
* DAX — Measures and KPI calculations
* Microsoft Excel — Initial data preparation and analysis

## Dashboard Pages

1. Executive Overview
Provides a high-level view of:
* Total Revenue
* Total Target
* Total Profit
* Total Units 
* Target Achievement %
* Monthly Revenue Trend
* Revenue by Region
* Products by Revenue
* Actual Revenue vs Target

2. Product & Territory Performance
Provides detailed analysis of:
* Product-wise Profit
* Territory-wise Revenue
* Regional Performance Summary

3. Sales Representative Performance
Analyzes:
* Sales Representative Revenue
* Sales Representative Target Achievement
* Revenue vs Target
* Individual Sales Representative Performance

## Key Business Insights 
* Total Revenue: ₹72.26M
* Total Target : ₹75.97M
* Total Profit:  ₹16.92M
* Total Units :  129.57K
* Overall Target Achievement: 95.12%
* GastroSafe generated the highest revenue and profit among the products.
* West recorded the highest regional revenue at approximately ₹22.95M.
* North had the lowest regional target achievement at approximately 94.35%.
* Mumbai was the highest-revenue territory.
* The top sales representative generated approximately ₹9.93M in revenue.
* The highest sales representative target achievement was approximately 96.92%.
* March showed a significant decline in monthly revenue and was identified as an area requiring further investigation.

## Key DAX Measures
Total Revenue
```DAX
Total Revenue =
SUM(Sales_Data1[Revenue])
```

Total Profit
```DAX
Total Profit =
SUM(Sales_Data1[Profit])
```

Total Target
```DAX
Total Target =
SUM(Sales_Data1[Target_Sales])
```

Total Units
```DAX
Total Units =
SUM(Sales_Data1[Units_Sold])
```

Achievement %
```DAX
Achievement % =
DIVIDE(
    [Total Revenue],
    [Total Target],
    0
)
```

## Business Value

The project demonstrates how raw sales data can be transformed into an interactive analytical dashboard that helps identify:
* Performance gaps
* High-performing products
* Regional opportunities
* Territory-level trends
* Sales representative performance
* Target achievement

The overall workflow followed was:

**Excel → Power Query → Data Modeling → DAX → Power BI Dashboard → Business Insights**

## Dashboard Preview

Executive Overview
![Executive Overview](Screenshots/Executive_Overview.png)

Product & Territory Performance
![Product & Territory Performance](Screenshots/Product_Territory_Performance.png)

Sales Representative Performance
![Sales Representative Performance](Screenshots/Sales_Representative_Performance.png)

## Project Learning

This project strengthened my practical understanding of Power BI, DAX, Power Query, Excel, data visualization, and business insight generation.
The key learning was to move beyond simply creating visualizations and focus on converting data into meaningful business insights and potential actions.

## Author
**Appeksha Suryawanshi**

Data Analytics | Power BI | Excel | Business Intelligence
