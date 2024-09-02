# Grocery Store Power BI Project

This repository contains the Power BI project completed during my internship at ICT Academy of Kerala. The project focuses on data transformation, modeling, and visualization for a wholesale trading company dealing with Food and Beverage products. The company is named "Grocery Store" for the purpose of this project.

## Project Overview

The project was carried out in three main parts:

1. **Data Transformation Tasks**
2. **Data Modeling Tasks**
3. **Report Creation**

### 1. Data Transformation Tasks

The initial stage of the project involved cleaning and transforming the provided dataset. Key transformations included:

- **Customer Table**: Renamed `CompanyName` to `CustomerName`.
- **Employee Table**: Created a new column `Full Name` by concatenating first and last names. Removed the `BirthDate` column.
- **Suppliers Table**: Renamed `CompanyName` to `SupplierName`.
- **Shippers Table**: Renamed `CompanyName` to `ShipperName`.
- **Orders Table**: Changed the data type of `ShipPostalCode` to text.
- **Order_Details Table**: Changed the data type of `Discount` to Fixed Decimal. Created three new columns:
  - `GrossAmount` = UnitPrice * Quantity
  - `DiscountAmount` = GrossAmount * Discount
  - `NetAmount` = GrossAmount - DiscountAmount

Final checks were performed to ensure that all columns had the correct data types and that auto-detection of new relationships and auto time intelligence were disabled.

### 2. Data Modeling Tasks

Data modeling involved setting up the relationships between tables and ensuring proper summarization and formatting:

- Adjusted the format of the `Discount` column in `Order_Details` to Decimal.
- Modified summarization for columns like `Year`, `MonthNo`, etc., in the `DateTable`.
- Marked `DateTable` as the central date table.

### 3. Report Creation

The final stage involved creating interactive reports and dashboards for various departments, including:

- **Business Operations**: KPIs like overall sales, number of orders, total customers, and more.
- **Customer Insights**: Analysis of Net Amount by customer country, top customers, and customer order patterns.
- **Product Performance**: Insights into the top and bottom products by orders and net amount.
- **Employee Analysis**: Employee performance by orders and net amount, and other employee-related metrics.
- **Performance Over Time**: Net Amount analysis over months and quarters, discount patterns, and more.

Each report was designed with appropriate slicers, titles, and a consistent layout, including a company logo.


## Conclusion

This project showcases my ability to perform complex data transformations, create data models, and design insightful reports using Power BI. It demonstrates my skills in handling end-to-end data analysis projects.