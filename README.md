# Data Warehouse and Analytics Project 🚀

Welcome to the **Data Warehouse and Analytics Project** repository.  
This project demonstrates a complete, **end-to-end data warehousing and analytics solution**, covering everything from raw data ingestion to actionable business insights.

Created as a **portfolio project**, it highlights real-world **data engineering best practices**: data modeling, data quality management, integration of multiple sources, and analytics-ready design. The focus is on **transforming raw data into a structured warehouse** that enables efficient querying, reporting, and decision-making.

The mission is clear: **turn data into insight, not just tables**.

## 🏗️ Data Architecture

The data architecture for this project follows the **Medallion Architecture** with **Bronze, Silver, and Gold layers**:

![image alt](https://github.com/Tahir-Zaman-23DS14/SQL-DataWareHouse-Project/blob/2a048ced2df3507770e073f00c702d79c65e16a0/Helping%20Materials/Data%20Architecture.drawio%20Screen-Short.png)

- **Bronze Layer:** Stores raw data as-is from the source systems. Data is ingested from CSV files into the SQL Server database.  
- **Silver Layer:** This layer performs data cleansing, standardization, and normalization to prepare data for analysis.  
- **Gold Layer:** Houses business-ready data modeled into a **star schema**, optimized for reporting and analytics.


# Project Requirements

## Building the Data Warehouse (Data Engineering)

### Objective
Develop a modern data warehouse using SQL Server to consolidate sales data from multiple sources, enabling analytical reporting and informed decision-making.

### Specifications

- **Data Sources**  
  Import data from two source systems (ERP and CRM) provided as CSV files.

- **Data Quality**  
  Clean and resolve data quality issues before performing analysis.

- **Integration**  
  Combine data from both sources into a single, user-friendly data model optimized for analytical queries.

- **Scope**  
  Focus only on the latest available dataset. Data historization is not required.

- **Documentation**  
  Provide clear documentation of the data model to support business stakeholders and analytics teams.

---

# Links to Project Tools

- **[SQL Server Express](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)**  
  Lightweight server used to host and store your SQL database.

- **[SQL Server Management Studio (SSMS)](https://learn.microsoft.com/en-us/ssms/install/install?view=sql-server-ver16)**  
  GUI tool for managing, querying, and interacting with databases.

- **[Git Repository (GitHub)](https://github.com/)**  
  Used to manage source code, track versions, and collaborate efficiently.

- **[DrawIO](https://www.drawio.com/)**  
  Used to design data architecture, models, workflows, and diagrams.

- **[Notion](https://www.notion.com/)**  
  All-in-one tool for project planning, management, and organization.

---

# My Directory

- **Notion Workspace**  
  I create an overall project plan with a clear view of the whole picture, then break it down into small, manageable tasks.

- **[Download the Draw.io File](Helping Materials/Data Architecture.drawio)**  
  Used to design and visualize the project’s data architecture.  
  Check the **Helping Materials** folder for screenshots of the data architecture.
