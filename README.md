# Simulated an ETL process into a data warehouse using Excel, SSMS, and SSIS.

# 🎯 Project Objectives
- Simulate a real-world ETL workflow using enterprise tools
- Extract source data from Excel files
- Transform and clean data using SSIS
- Load processed data into a structured star schema in SQL Server
## 🧰 Technologies Used
- **Microsoft Excel** – Source data files  
- **SQL Server Management Studio (SSMS)** – Manage and query the data warehouse  
- **SQL Server Integration Services (SSIS)** – ETL process design and automation  
- **Star Schema** – Data warehouse schema design
## 🗂️ Schema Design

The data warehouse uses a **star schema** with:
- Fact table: `Fact Orders`
- Dimension tables: `DimLocation`, `DimCustomer`, `DimTime`,'DimProduct'.
<img width="894" height="507" alt="image" src="https://github.com/user-attachments/assets/85458de5-9593-41f3-92bd-1b409bb28a2a" />

