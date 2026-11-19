# Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository!
This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project it highlights industry best practices in data engineering and analytics.

---

## Data Architecture
The data architecture for this project follows Medallion Architecture **Bronze**, **Silver**, and **Gold** layers:

![High Level Architecture](docs/Data%20Architecture.png)

1. **Bronze Layer**: Stores raw data from the source systems. Data is ingested from CSV Files into SQL Server Database.
2. **Silver Layer**: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
3. **Gold Layer**: This layer contains business-ready data modeled into a star schema required for reporting and analytics. 

--

## Project Overview
In this project i have:
1. **Design the architecture**: a modern data warehouse with three layers, bronze, silver and gold.
2. **Build the ETL pipelines**: load the source files and move the data through the layers.
3. **Model the data**: facts and dimensions, ready for reports.
4. **Analyze it**: answer business question with SQL. 

---

## Project Requirements

### Building the Data Warehouse (Data Engineering)

#### Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision making.

#### Specifications
- **Data Sources**: Import data from two source system (ERP and CRM) provided as CSV file.
- **Data Quality**: Cleanse and resolve data quality issues prior to analysis.
- **Integration**: Combine both sources int to a user friendly data model deigned for analytical queries.
- **Scope**: Focus on the latest dataset only; historization of data is not required.
- **Documentation**: Provides clear documentation of the data model to support both business stakeholders and analytics teams.

---

### BI: Analytics & Reporting (Data Analytics)
Develop SQL-based analytics to deliver detailed insights into:
- **Customer Behavior**
- **Product Performance**
- **Sales Trends**

These insights empower stakeholders with key business metrics, enabling strategic decision-making.



