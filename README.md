# Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository.

This project demonstrates a complete end-to-end data warehousing and analytics solution, covering data ingestion, transformation, modeling, and reporting. It follows industry-standard practices in data engineering and analytics using SQL Server and the Medallion Architecture framework.

---

## 🏗️ Data Architecture

The project follows the **Medallion Architecture** pattern consisting of three layers:

### Bronze Layer

* Stores raw data from source systems.
* Data is loaded directly from CSV files into SQL Server.
* No transformations are applied.
* Serves as the historical source of truth for incoming data.

### Silver Layer

* Performs data cleansing and standardization.
* Handles normalization, data quality improvements, and enrichment.
* Creates consistent and reliable datasets for downstream processing.

### Gold Layer

* Contains business-ready analytical datasets.
* Implements dimensional modeling techniques such as star schemas.
* Supports reporting, dashboarding, ad-hoc analysis, and machine learning use cases.

---

## 📖 Project Overview

This project covers:

### 1. Data Architecture

Designing a modern data warehouse using a layered Medallion Architecture approach.

### 2. ETL Pipelines

Building extraction, transformation, and loading processes to move data through the warehouse layers.

### 3. Data Modeling

Creating fact and dimension tables optimized for analytical workloads.

### 4. Analytics & Reporting

Developing SQL-based reports and analytical queries to generate business insights.

### Key Skills Demonstrated

* SQL Development
* Data Warehousing
* Data Engineering
* ETL Development
* Data Modeling
* Data Analytics

---

## 🛠️ Tools & Technologies

* SQL Server Express
* SQL Server Management Studio (SSMS)
* Git & GitHub
* Draw.io
* CSV Files

---

## 🚀 Project Requirements

### Data Warehouse Development

#### Objective

Build a modern data warehouse that consolidates sales data from multiple source systems into a centralized analytical platform.

#### Specifications

##### Data Sources

* ERP System (CSV Files)
* CRM System (CSV Files)

##### Data Quality

* Clean and standardize source data.
* Resolve data quality issues before analytical processing.

##### Data Integration

* Merge data from multiple systems into a unified analytical model.

##### Scope

* Focus on the latest available dataset.
* Historical tracking is not required.

##### Documentation

* Maintain clear documentation of data structures and transformations.

---

### Analytics & Reporting

#### Objective

Generate SQL-based analytical insights related to:

* Customer Behavior
* Product Performance
* Sales Trends

#### Expected Outcomes

* Customer segmentation and purchasing analysis
* Product performance measurement
* Revenue and sales trend analysis
* Business performance reporting
* Decision-support metrics

---

## 📂 Repository Structure

```text
data-warehouse-project/
│
├── datasets/
│   └── Source CSV files from ERP and CRM systems
│
├── docs/
│   ├── etl.drawio
│   ├── data_architecture.drawio
│   ├── data_catalog.md
│   ├── data_flow.drawio
│   ├── data_models.drawio
│   └── naming-conventions.md
│
├── scripts/
│   ├── bronze/
│   ├── silver/
│   └── gold/
│
├── tests/
│
├── README.md
├── LICENSE
├── .gitignore
└── requirements.txt
```

---

## 🛡️ License

This project is licensed under the MIT License. You are free to use, modify, and distribute it in accordance with the license terms.
