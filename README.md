# Data-Warehouse-Data-Modeling-and-Analytics-Project
Designing and Building a Data Warehouse with ETL processes, data modeling and Analytics.
This project showcases a complete data warehousing, data modelling and analytics solution, covering everything from data warehouse development to the generation of actionable insights. This portfolio project reflects industry-standard best practices in both data engineering and analytics.

---
## 🏗️ Data Architecture
The data architecture in this project is structured using the Medallion Architecture, comprising **Bronze**, **Silver**, and **Gold** layers:
![Data Architecture](docs/DataArchitecture.drawio.png)

1. **Bronze Layer**: Serves as the landing zone for raw data ingested directly from source systems. In this case, data is imported from CSV files into a SQL Server database.
2. **Silver Layer**: Focuses on data refinement through cleansing, standardization, and normalization, making the data suitable for downstream processing and analysis.
3. **Gold Layer**  : Contains curated, business-ready data organized in a star schema format, optimized for reporting, dashboarding, and advanced analytics.

## 📖 Project Overview
This project involves:
1. **Data Architecture**    : Designing a Modern Data Warehouse Using Medallion Architecture **Bronze**, **Silver**, and **Gold** layers.
2. **ETL Pipelines**        : Extracting, transforming, and loading data from source systems into the warehouse.
3. **Data Modeling**        : Developing fact and dimension tables optimized for analytical queries.
4. **Analytics & Reporting**: Creating SQL-based reports and dashboards for actionable insights.

## 🚀 Project Requirements

### Building the Data Warehouse 

#### Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

#### Specifications
- **Data Sources** : Import data from two source systems (ERP and CRM) provided as CSV files.
- **Data Quality** : Cleanse and resolve data quality issues prior to analysis.
- **Integration**  : Combine both sources into a single, user-friendly data model designed for analytical queries.
- **Scope**        : Focus on the latest dataset only; historization of data is not required.
- **Documentation**: Provide clear documentation of the data model to support both business stakeholders and analytics teams.

---
### BI: Analytics & Reporting (Data Analysis)

#### Objective
Develop SQL-based analytics to deliver detailed insights into:
- **Customer Behavior**
- **Product Performance**
- **Sales Trends**

These insights empower stakeholders with key business metrics, enabling strategic decision-making.  

## 📂 Repository Structure
```
data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details.
│   ├── data_architecture.drawio        # Draw.io file shows the project's architecture
│   ├── data_catalog.md                 # Catalog of datasets, including field descriptions and metadata
│   ├── data_flow.drawio                # Draw.io file for the data flow diagram
│   ├── data_models.drawio              # Draw.io file for data models (star schema)
│   ├── naming-conventions.md           # Consistent naming guidelines for tables, columns, and files
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Scripts for extracting and loading raw data
│   ├── silver/                         # Scripts for cleaning and transforming data
│   ├── gold/                           # Scripts for creating analytical models
│
├── tests/                              # Test scripts and quality files
│
├── README.md                           # Project overview and instructions
```
---

