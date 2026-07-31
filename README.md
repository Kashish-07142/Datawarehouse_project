# SQL-Based Data Warehouse and Reporting

This project shows the complete process of building a data warehouse and creating useful business insights from it. It covers everything from loading raw data to preparing data for reporting and analytics. It is designed as a portfolio project to demonstrate practical data engineering and data analytics skills.

---

## 🏗️ Data Architecture

This project uses the **Medallion Architecture**, which has three layers:

### **Bronze Layer**

* Stores the raw data exactly as it is received from the source systems.
* Data is imported from CSV files into SQL Server without any changes.

### **Silver Layer**

* Cleans and prepares the data.
* Tasks include removing errors, standardizing formats, handling missing values, and making the data consistent.

### **Gold Layer**

* Stores business-ready data.
* Data is organized into a **Star Schema** (Fact and Dimension tables) to support reporting and analytics.

---

## 📖 Project Overview

This project includes the following steps:

* Designing a modern data warehouse using the **Bronze, Silver, and Gold** layers of the Medallion Architecture.
* Building ETL pipelines to extract, transform, and load data into SQL Server.
* Creating a star schema with fact and dimension tables for faster analytical queries.
* Writing SQL queries to generate reports and business insights.

This project is useful for anyone who wants to demonstrate skills in:

* SQL Development
* Data Warehousing
* Data Engineering
* ETL Development
* Data Modeling
* Data Analytics

---

## 🚀 Project Requirements

### Data Warehouse Development (Data Engineering)

#### Objective

Build a modern data warehouse in SQL Server by combining sales data from different source systems. The goal is to create a single, reliable source of data for reporting and business analysis.

#### Requirements

* Import data from two source systems (**ERP** and **CRM**) provided as CSV files.
* Clean and fix data quality issues before loading the data.
* Merge data from both systems into one easy-to-use analytical data model.
* Use only the latest available data. Historical data tracking is not required.
* Document the data model clearly so that both business users and technical teams can understand it.

---

### Analytics and Reporting (Data Analysis)

#### Objective

Create SQL-based reports that provide valuable insights into:

* Customer Behavior
* Product Performance
* Sales Trends

These reports help businesses understand their data and make better decisions.
