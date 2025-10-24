# 🏗️ Modern Data Warehouse with SQL Server

## 📘 Project Overview
This project demonstrates how to design and implement a **modern data warehouse** using **Microsoft SQL Server**.  
It integrates data from **multiple source systems** and applies a **three-layer Medallion Architecture (Bronze, Silver, Gold)** to organize and transform data efficiently for analytics and reporting.

---

## 🧩 Architecture: The Medallion Model

| Layer | Purpose | Example Activities |
|-------|----------|--------------------|
| **Bronze (Raw Layer)** | Stores raw data ingested from various source systems (e.g., CSV files, APIs, OLTP databases). | Data extraction, initial loading |
| **Silver (Clean Layer)** | Applies data cleansing, normalization, and joins across datasets to create standardized entities. | Data transformation, deduplication, quality checks |
| **Gold (Curated Layer)** | Contains business-ready, aggregated data for BI tools and dashboards. | Data modeling, KPIs, analytics views |

---

## ⚙️ Technologies Used
- **Microsoft SQL Server**
- **SQL Server Management Studio (SSMS)**
- **T-SQL (Transact-SQL)** for ETL logic
- **SQL Server Agent / SSIS** for automation (optional)
- **Power BI** or other BI tools (optional for visualization)

---

## 🔄 ETL Process
1. **Extract** data from multiple source systems (e.g., sales, customers, inventory).
2. **Transform** data in SQL Server using stored procedures, joins, and CTEs.
3. **Load** transformed data into data warehouse layers (Bronze → Silver → Gold).

---

## 🧠 Key Objectives
- Build a scalable, maintainable **data warehouse**.
- Demonstrate **data integration** from heterogeneous systems.
- Implement **layered ETL design** for clarity, reusability, and performance.
- Prepare **analytical-ready datasets** for BI and decision-making.

---

## 📂 Repository Structure
