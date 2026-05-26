# Readme.md
<img width="1704" height="982" alt="Screenshot 2026-05-26 at 10 18 13 AM" src="https://github.com/user-attachments/assets/781114d7-9dce-4999-b724-bb9d949ac8d4" />
Power BI DashBoard Project


# Overview
This project showcases an interactive and visually
appealing dashboard built using Power BI. 
The dashboard is designed to provide meaningful 
insights through data 
visualization, helping users make data-driven decisions efficiently.

# Features
Interactive and user-friendly dashboard.

Clean and attractive design.

Dynamic filtering and slicing options.

Key performance indicators (KPIs).

Data visualization using charts, graphs, and tables.

Drill-down and drill-through capabilities.

# Tools and Technologies
Power BI Desktop.

Data Modeling.

DAX (Data Analysis Expressions).

Data Visualization Techniques.
 

# Insights Provided
Overview of key metrics.

Trend analysis.

Comparative analysis.

Performance tracking.

# Purpose
The purpose of this project is to demonstrate data 
visualization skills and the ability to transform raw 
data into actionable insights using Power BI.

# Future Improvements
Add more advanced analytics.

Integrate real-time data sources.

Enhance dashboard performance.

# Modeling 
<img width="1686" height="1008" alt="Screenshot 2026-05-26 at 10 19 43 AM" src="https://github.com/user-attachments/assets/d3aaa15b-d1b8-4c30-b89b-f6d0812a491a" />
Power Bi Sales Dashboard

# Overview

This project presents an interactive Power BI dashboard built using a structured data model consisting of fact and dimension tables. The dashboard provides insights into sales performance, product trends, customer behavior, and returns analysis.

The data model follows a star schema design to ensure efficient querying and better performance.

# Data Model

The project is designed using the following tables:

# Fact Tables

1.Sales_Fact

 .Contains transactional sales data

 .Includes metrics like Cost, Profit, Quantity

 .Linked with Product, Customer, Region, and Date dimensions

2. Returns_Fact
   
 .Contains product return data

 .Tracks returned quantities and related details
 
 .Connected with Product, Region, and Date
 
# Dimension Tables
1.Product_Dim
   
  .Product details such as ProductID, ProductName, Category, and Cost

2.Customer_Dim
   
 .Customer information including CustomerID, FullName

3. Region_Dim
   
 .Regional information including RegionID
and RegionName

4.Date_Dim

.Date-related attributes such as Year, 

.Quarter, Month, Day, Weekday

# Relationships

.One-to-many relationships between dimension tables and fact tables

.Centralized fact table (Sales_Fact) connected to all dimensions

.Returns_Fact shares relationships with Product, Region, and Date

.Proper key-based joins using IDs (ProductID, CustomerID, RegionID, Date)
---
Dax Formulas  








