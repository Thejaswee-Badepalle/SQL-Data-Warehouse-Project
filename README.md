# SQL Data Warehouse Project

Welcome to the **SQL Data Warehouse Project** repository! 🚀

This project demonstrates a comprehensive data warehousing solution using **SQL Server**, from ingesting raw data from multiple source systems to building a business-ready data warehouse.

---

# 🏗️ Data Architecture

The project follows the **Medallion Architecture**, which consists of **Bronze**, **Silver**, and **Gold** layers.

![Data Architecture](docs/data_architecture.png)


### Bronze Layer
- Stores raw data from the source systems.
- Loads CRM and ERP CSV files into SQL Server.
- Preserves the original source data without transformations.

### Silver Layer
- Cleans and standardizes the data.
- Resolves data quality issues.
- Applies data transformations and normalization.
- Prepares data for analytical processing.

### Gold Layer
- Stores business-ready data.
- Implements Fact and Dimension tables.
- Uses a Star Schema optimized for analytical queries.

---

# 🚀 Project Requirements

## Objective

Develop a modern Data Warehouse using SQL Server to consolidate sales data from multiple source systems into a centralized repository for analytical reporting and business decision-making.

## Specifications

- Import data from CRM and ERP source systems.
- Load raw data into the Bronze layer.
- Clean and transform data in the Silver layer.
- Integrate data from multiple sources.
- Build Fact and Dimension tables in the Gold layer.
- Focus on the latest available dataset (historical tracking is out of scope).
- Document the data model and architecture.

---

# 🛠️ Tools & Technologies

- **SQL Server** – Database platform
- **SQL Server Management Studio (SSMS)** – GUI for managing and interacting with databases.  
- **GitHub** – Repository hosting and version control. 
- **Draw.io** – Architecture and data model diagrams

---

# 📂 Repository Structure

```text
SQL-Data-Warehouse-Project/
│
├── datasets/                     # CRM and ERP source datasets
│   ├── source_crm/
│   └── source_erp/
│
├── docs/                         # Project documentation
│   ├── data_architecture.drawio
│   ├── data_flow.drawio
│   └── data_models.drawio
│
├── scripts/                      # SQL scripts
│   ├── bronze/                   # Raw data loading
│   ├── silver/                   # Data cleansing & transformation
│   └── gold/                     # Fact & Dimension tables
│
├── tests/                        # Data validation and quality checks
│
└── README.md
```

---

# 📌 Project Highlights

- Designed a Data Warehouse using the Medallion Architecture.
- Built ETL pipelines using SQL Server.
- Imported CRM and ERP data from CSV files.
- Performed data cleansing and transformation.
- Integrated multiple data sources.
- Developed Fact and Dimension tables.
- Implemented a Star Schema for analytical reporting. 
