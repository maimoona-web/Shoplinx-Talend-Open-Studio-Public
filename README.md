# Shoplinx-Talend-Open-Studio-Public
This project includes ETL workflows developed using Talend Open Studio. The workflows cover data extraction, transformation, and loading processes designed for structured datasets.
##  ETL Implementation (Talend Open Studio)

This project includes ETL workflows developed using Talend Open Studio.
The workflows cover data extraction, transformation, and loading processes
designed for structured datasets.

Due to copyright and data protection considerations, the full Talend project
files are maintained in a private repository. Screenshots and documentation
are provided for reference.
# Shoplinx ETL & Business Intelligence Project

##  Project Overview
This project involved the design and implementation of an end-to-end ETL and analytics pipeline for **Shoplinx**, integrating Talend Open Studio, SQL Server, and Power BI.

The objective was to clean, transform, store, and analyze business data to support strategic decision-making regarding market expansion into Canada.

---

## Tools & Technologies
- Talend Open Studio (ETL Development)
- Microsoft SQL Server (Database Design & Storage)
- Power BI (Data Visualization & Reporting)
- SQL (Data Validation & Querying)

---

## Project Workflow

### Database Understanding
- Imported the provided DACPAC file
- Analyzed the original database schema
- Identified key tables and relationships

### Database Creation
- Designed and created a new SQL Server database
- Structured it to store cleaned and transformed datasets

### ETL Development (Talend)
- Built separate ETL jobs for:
  - Customers
  - Sales
  - Ratings
- Performed data quality checks:
  - Duplicate removal
  - Null value handling
  - Data formatting and standardization
- Used **tMap** components to:
  - Split datasets into Online and Offline segments
  - Transform and map fields accordingly

###  Data Loading
- Created corresponding tables in SQL Server
- Loaded transformed data using **tDBOutput**
- Validated outputs using SQL queries

###  Business Intelligence & Reporting
- Connected Power BI to SQL Server
- Designed interactive dashboards
- Analyzed:
  - Sales performance
  - Customer behaviour
  - Online vs Offline trends
- Provided insights to support decision-making regarding entry into the Canadian market

---

## Key Skills Demonstrated
- ETL pipeline development
- Data cleaning & preprocessing
- SQL database design
- Data transformation & segmentation
- Data validation & quality assurance
- Business intelligence dashboard development
- Analytical thinking for strategic decision-making

---

##  Business Impact
The solution provided structured, clean, and analysis-ready data, enabling data-driven evaluation of market expansion opportunities.

---      

## Deliverables
- Talend ETL workflows
- SQL Server database schema
- Power BI dashboards
- SQL validation queries

---
