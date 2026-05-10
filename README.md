# Shopping Mall Data Warehouse - Assignment 1

## Project Overview

This project is a Data Warehousing assignment based on a Shopping Mall business scenario. The main purpose of this project is to design and implement a data warehouse that can support business intelligence and analytical reporting.

The project focuses on creating a structured data warehouse using SQL Server and performing the ETL process using SQL Server Integration Services (SSIS). Data from the operational/source database is extracted, transformed, and loaded into the data warehouse using a star schema design.

## Objectives

- Design a data warehouse for shopping mall business analysis.
- Create a star schema with fact and dimension tables.
- Extract data from the source database.
- Clean and transform data using SSIS.
- Load data into the data warehouse.
- Support future OLAP and reporting requirements.

## Technologies Used

- Microsoft SQL Server
- SQL Server Management Studio (SSMS)
- SQL Server Integration Services (SSIS)
- Visual Studio / SQL Server Data Tools
- SQL Queries

## Data Warehouse Design

The data warehouse was designed using a star schema. The fact table stores measurable business data, while dimension tables store descriptive information used for analysis.

## Main Components

### Source Database

The source database contains the original operational data related to the shopping mall business.

### Data Warehouse

The data warehouse stores cleaned and transformed data in a format suitable for analysis.

### Dimension Tables

Dimension tables provide descriptive information for analysis, such as date, mall, product, customer, or payment-related details.

### Fact Table

The fact table stores the main measurable values, such as sales amount, quantity, or transaction-related measures.

## ETL Process

The ETL process was implemented using SSIS.

### Extract

Data was extracted from the operational/source database.

### Transform

The extracted data was cleaned and transformed. This included handling missing values, converting data types, deriving new columns, and preparing data for the warehouse structure.

### Load

The transformed data was loaded into the dimension and fact tables in the data warehouse.

## Key Features

- Star schema design
- Dimension and fact table implementation
- SSIS ETL workflows
- Data cleaning and transformation
- Data loading into warehouse tables
- Foundation for OLAP cube and reporting

## Learning Outcomes

Through this assignment, I learned how to design and implement a data warehouse, create ETL workflows using SSIS, and prepare structured data for business intelligence analysis.

## Conclusion

This assignment helped me understand the complete data warehousing process, from source data extraction to warehouse loading. The final data warehouse provides a strong foundation for OLAP analysis and business intelligence reporting in the next stage of the project.
