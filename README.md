# 🏛️ SQL Data Warehouse Project  
Building a modern data warehouse with **SQL Server**, including **ETL pipelines**, **data modeling**, and **analytics**

## 📘 Overview  
This project demonstrates the end‑to‑end development of a **modern data warehouse** using SQL Server.  
It includes the full lifecycle of enterprise data engineering:

- Source data ingestion  
- ETL/ELT processing  
- Dimensional modeling  
- Data quality validation  
- Analytics‑ready marts  
- Documentation for reproducibility and scale  

The goal is to showcase practical, production‑aligned data engineering skills used in real organizations.

---

## 🎯 Project Objectives  
- Design a **scalable data warehouse architecture**  
- Build **ETL pipelines** to clean, transform, and load data  
- Implement **star‑schema dimensional models**  
- Create **analytics‑ready tables** for BI tools  
- Ensure **data quality, lineage, and governance**  
- Provide clear documentation for future enhancements  

---

## 🧱 Architecture  
The warehouse follows a layered architecture:



### **Staging Layer**
Raw ingested data with minimal transformations.  
Used for validation, auditing, and reproducibility.

### **Core Layer**
Cleaned, standardized tables with business rules applied.  
Surrogate keys, conformed dimensions, and validated facts.

### **Dimensional Marts**
Star‑schema models optimized for reporting:

- Fact tables (transactions, sales, operations)
- Dimension tables (products, stores, dates, customers)

---

## 🔧 Technologies Used  
- **SQL Server** (primary warehouse engine)  
- **SSMS** for development  
- **T‑SQL** for ETL and modeling  
- **Python / pandas** (optional preprocessing)  
- **Draw.io / Lucidchart** for architecture diagrams  
- **Power BI / Looker** for downstream analytics  

---

## 📦 Features  
### ✔️ ETL Pipelines  
- Source extraction (CSV, API, DB tables)  
- Data cleaning (null handling, deduplication, type enforcement)  
- Business rule transformations  
- Incremental load patterns  

### ✔️ Data Modeling  
- Star schema design  
- Surrogate key generation  
- Slowly Changing Dimensions (SCD Type 1/2)  
- Fact table grain definition  

### ✔️ Data Quality  
- Referential integrity checks  
- Duplicate detection  
- Schema validation  
- Audit logging  

---

## 📁 Repository Structure  
sql-data-warehouse-project/
│
├── sql/                     # SQL scripts for ETL, DDL, DML
├── staging/                 # Staging layer scripts
├── core/                    # Core layer transformations
├── marts/                   # Dimensional models (facts & dims)
├── diagrams/                # Architecture & schema diagrams
└── README.md                # Project documentation
---

## 📊 Example Deliverables  
- Warehouse schema diagram  
- ETL pipeline scripts  
- Fact & dimension table definitions  
- Data validation queries  
- Sample analytics queries  

---

## 🚀 Business Value  
A well‑designed SQL Server data warehouse enables:

- Faster, more reliable reporting  
- Centralized, governed data assets  
- Scalable analytics across departments  
- Reduced manual reporting workload  
- Clear lineage and auditability  

---

## 📌 Future Enhancements  
- Add SSIS or Azure Data Factory pipelines  
- Implement CI/CD for SQL deployments  
- Add role‑based security and row‑level access  
- Introduce incremental refresh logic  
- Build Power BI dashboards on top of marts  

---

## 👤 Author  
**Santos Nwachukwu**  
Data Intelligence Analyst • SQL • ETL • Analytics Engineering  
Lakeland, FL

