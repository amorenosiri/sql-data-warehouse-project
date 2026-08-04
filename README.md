# sql-data-warehouse-project
Building a modern data warehouse project with SQL Server, including ETL processes, data modeling and analytics.

# Data Warehouse and Analytics Project 🚀

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![SQL Server](https://img.shields.io/badge/SQL%20Server-Express-red)](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)
[![SSMS](https://img.shields.io/badge/SSMS-18.12.1-blue)](https://docs.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms)

Welcome to the **Data Warehouse and Analytics Project** repository!  
This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project, it highlights industry best practices in data engineering and analytics.

---

## 🏗️ Data Architecture

The data architecture follows the **Medallion Architecture** (Bronze, Silver, and Gold layers):

<img width="1129" height="658" alt="image" src="https://github.com/user-attachments/assets/5cbe9ff3-8fed-4db7-9742-950c9cbed607" />


- **Bronze Layer**: Stores raw data as-is from the source systems. Data is ingested from CSV files into SQL Server Database.
- **Silver Layer**: Includes data cleansing, standardization, and normalization processes to prepare data for analysis.
- **Gold Layer**: Houses business-ready data modeled into a star schema required for reporting and analytics.

---

## 📖 Project Overview

This project involves:

- **Data Architecture**: Designing a modern Data Warehouse using Medallion Architecture (Bronze, Silver, Gold layers).
- **ETL Pipelines**: Extracting, transforming, and loading data from source systems into the warehouse.
- **Data Modeling**: Developing fact and dimension tables optimized for analytical queries.
- **Analytics & Reporting**: Creating SQL-based reports and dashboards for actionable insights.

🎯 This repository is an excellent resource for professionals and students looking to showcase expertise in:

- SQL Development
- Data Architecture
- Data Engineering
- ETL Pipeline Development
- Data Modeling
- Data Analytics

---

## 🛠️ Important Links & Tools

**Everything is free!**

- **Datasets**: Access to the project dataset (CSV files).
- **SQL Server Express**: Lightweight server for hosting your SQL database.  
  [Download SQL Server Express](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)
- **SQL Server Management Studio (SSMS)**: GUI for managing and interacting with databases.  
  [Download SSMS](https://docs.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms)
- **Git Repository**: Set up a GitHub account and repository to manage, version, and collaborate on your code efficiently.
- **DrawIO**: Design data architecture, models, flows, and diagrams.  
  [DrawIO](https://app.diagrams.net/)
- **Notion**: Get the project template and all phases/tasks from Notion.  
  [Project Template](https://www.notion.so/) (link placeholder)
- **Notion Project Steps**: Access to all project phases and tasks.

---

## 🚀 Project Requirements

### **Building the Data Warehouse (Data Engineering)**

**Objective**  
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

**Specifications**

- **Data Sources**: Import data from two source systems (ERP and CRM) provided as CSV files.
- **Data Quality**: Cleanse and resolve data quality issues prior to analysis.
- **Integration**: Combine both sources into a single, user-friendly data model designed for analytical queries.
- **Scope**: Focus on the latest dataset only; historization of data is not required.
- **Documentation**: Provide clear documentation of the data model to support both business stakeholders and analytics teams.

### **BI: Analytics & Reporting (Data Analysis)**

**Objective**  
Develop SQL-based analytics to deliver detailed insights into:

- Customer Behavior
- Product Performance
- Sales Trends

These insights empower stakeholders with key business metrics, enabling strategic decision-making.

For more details, refer to [docs/requirements.md](docs/requirements.md).

---

## 📂 Repository Structure
data-warehouse-project/
│
├── datasets/ # Raw datasets used for the project (ERP and CRM data)
│
├── docs/ # Project documentation and architecture details
│ ├── etl.drawio # Draw.io file showing ETL techniques and methods
│ ├── data_architecture.drawio # Draw.io file showing the project's architecture
│ ├── data_catalog.md # Catalog of datasets, including field descriptions and metadata
│ ├── data_flow.drawio # Draw.io file for the data flow diagram
│ ├── data_models.drawio # Draw.io file for data models (star schema)
│ └── naming-conventions.md # Consistent naming guidelines for tables, columns, and files
│
├── scripts/ # SQL scripts for ETL and transformations
│ ├── bronze/ # Scripts for extracting and loading raw data
│ ├── silver/ # Scripts for cleaning and transforming data
│ └── gold/ # Scripts for creating analytical models
│
├── tests/ # Test scripts and quality files
│
├── README.md # Project overview and instructions
├── LICENSE # License information for the repository
├── .gitignore # Files and directories to be ignored by Git
└── requirements.txt # Dependencies and requirements for the project
