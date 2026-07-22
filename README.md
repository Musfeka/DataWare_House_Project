# DataWare_House_Project
An end-to-end Data Warehouse project using SQL Server (Medallion Architecture: Bronze, Silver, Gold) and interactive Power BI dashboard for sales analytics.
## 📌 Project Overview
This project demonstrates an **end-to-end Data Warehouse and Business Intelligence solution** built using SQL Server and Power BI. 

The architecture follows the **Medallion Architecture (Bronze, Silver, Gold layers)** to ingest raw data, clean and transform it, and build a Star Schema model for analytical reporting.

### 🏗️ Architecture & Data Pipeline
1. **Bronze Layer (Raw Zone):** Ingested raw datasets (CRM & ERP CSV files) into SQL Server using `BULK INSERT`.
2. **Silver Layer (Cleaned Zone):** Cleaned, standardized, and handled missing values using SQL views and transformations.
3. **Gold Layer (Analytics Zone):** Created dimensional models (Star Schema) with Fact and Dimension tables (`fact_sales`, `dim_customers`, `dim_products`).
4. **Power BI Dashboard:** Connected Gold layer to Power BI to visualize key business KPIs (Sales, Orders, Quantity) and trend analysis.

### 🛠️ Tech Stack & Tools
* **Database:** SQL Server Management Studio (SSMS)
* **Architecture:** Medallion Architecture (Bronze $\rightarrow$ Silver $\rightarrow$ Gold)
* **Data Modeling:** Star Schema Design
* **Business Intelligence:** Power BI (Data Visualization, DAX, Drill-down Analysis)
* **Version Control:** GitHub
