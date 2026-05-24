# 📊 Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository! 🚀  

This project demonstrates a complete end-to-end data warehousing and analytics solution — from building a modern data warehouse to generating actionable business insights. Designed as a portfolio project, it showcases industry best practices in **Data Engineering**, **ETL Development**, and **Analytics**.

---

# 🏗️ Data Architecture

This project follows the **Medallion Architecture** approach using **Bronze**, **Silver**, and **Gold** layers.

## 🥉 Bronze Layer
- Stores raw data directly from source systems.
- Data is ingested from CSV files into SQL Server without transformation.

## 🥈 Silver Layer
- Performs data cleansing, standardization, normalization, and transformation.
- Prepares high-quality data for analytical processing.

## 🥇 Gold Layer
- Contains business-ready data modeled into a **Star Schema**.
- Optimized for reporting, dashboards, and analytical queries.

---

# 📖 Project Overview

This project includes:

- **Data Architecture**  
  Designing a modern data warehouse using Medallion Architecture.

- **ETL Pipelines**  
  Extracting, transforming, and loading data from multiple source systems into SQL Server.

- **Data Modeling**  
  Building fact and dimension tables optimized for analytics.

- **Analytics & Reporting**  
  Creating SQL-based reports and dashboards to generate actionable insights.

---

# 🎯 Skills Demonstrated

This repository is a great resource for professionals and students looking to showcase expertise in:

- SQL Development
- Data Architecture
- Data Engineering
- ETL Pipeline Development
- Data Modeling
- Data Analytics

---

# 🛠️ Tools & Resources

All tools used in this project are free to use.

| Tool | Description |
|------|-------------|
| Dataset | Source CSV files used for ERP and CRM data |
| SQL Server Express | Lightweight SQL Server database engine |
| SQL Server Management Studio (SSMS) | GUI for managing SQL Server databases |
| Git & GitHub | Version control and collaboration |
| Draw.io | Designing architecture and data flow diagrams |
| Notion | Project management and documentation |

---

# 🚀 Project Requirements

## 📌 Building the Data Warehouse (Data Engineering)

### Objective
Develop a modern data warehouse using SQL Server to consolidate sales data and enable analytical reporting for informed decision-making.

### Specifications

- **Data Sources**  
  Import data from ERP and CRM systems provided as CSV files.

- **Data Quality**  
  Clean and resolve data quality issues before analysis.

- **Data Integration**  
  Combine both sources into a unified analytical data model.

- **Scope**  
  Focus only on the latest available dataset. Historical tracking is not required.

- **Documentation**  
  Provide clear and structured documentation for both business stakeholders and analytics teams.

---

# 📈 BI: Analytics & Reporting

## Objective
Develop SQL-based analytics and reporting solutions to generate insights into:

- Customer Behavior
- Product Performance
- Sales Trends

These insights help stakeholders make data-driven strategic decisions.

For additional details, refer to:

```bash
docs/requirements.md

data-warehouse-project/
│
├── datasets/                           # Raw ERP and CRM datasets
│
├── docs/                               # Project documentation and architecture
│   ├── etl.drawio                      # ETL techniques and workflow diagrams
│   ├── data_architecture.drawio        # Overall project architecture
│   ├── data_catalog.md                 # Dataset metadata and field descriptions
│   ├── data_flow.drawio                # Data flow diagrams
│   ├── data_models.drawio              # Star schema and data models
│   ├── naming-conventions.md           # Naming standards and conventions
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Raw data ingestion scripts
│   ├── silver/                         # Data cleaning and transformation scripts
│   ├── gold/                           # Analytical model creation scripts
│
├── tests/                              # Data quality and testing scripts
│
├── README.md                           # Project overview and setup guide
├── LICENSE                             # License information
├── .gitignore                          # Ignored files and folders
└── requirements.txt                    # Project dependencies
