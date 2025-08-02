# ssas-data-warehouse

# SSAS BI Cube & Database Design Project

This project was completed as part of my MSc Data Science coursework (COMM051) at the University of Surrey.  
It demonstrates the end-to-end process of **normalizing relational databases**, implementing **stored procedures with transaction control**, and building an **SSAS Tabular BI cube** for multidimensional analysis and reporting.

---

## Project Overview

The goal of this project was to transform raw sales data (Products, Orders, Customers) into a structured and analyzable format. We achieved this by:

1. **Database Normalization (3NF)**  
   - Normalized Order Item, Product, and Customer tables to eliminate redundancy and ensure referential integrity.  
   - Designed ER diagrams and implemented primary, foreign, and surrogate keys.  

2. **SQL Enhancements**  
   - Created **views, stored procedures, and indexes** to improve query performance and ensure data consistency.  
   - Implemented **transaction management with error handling** using `BEGIN TRAN`, `COMMIT`, and `ROLLBACK`.

3. **SSAS Tabular Cube Design**  
   - Built an SSAS cube integrating Product, Customer, and Time dimensions for granular reporting.  
   - Designed hierarchies (e.g., Customer → City → Region → Country; Product → Product Group → Variant).  
   - Created calculated measures (e.g., percentage of cancelled orders, distinct order counts) using DAX.

4. **Business Insights**  
   - Enabled analysis of KPIs such as sales trends, order fulfillment, and cancellation rates across multiple dimensions.

---

## Key Skills Demonstrated

- **Database Design & Normalization:** 3NF, ER diagrams, indexing  
- **SQL Development:** Stored procedures, transactions, error handling  
- **Business Intelligence (BI):** SSAS Tabular, DAX calculations, hierarchies, measures  
- **Data Analytics & Storytelling:** KPI reporting and insights via cube analysis

---

## Deliverables

- [Final Report (PDF)](link-to-report)  
- [Video Walkthrough (YouTube/OneDrive link)](link-to-video)  

---

## How to Use

1. Review the **report** for database schema, normalization details, and BI design decisions.  
2. Watch the **video walkthrough** for an explanation of the SSAS cube, measures, and insights.  
3. Adapt the design concepts for building enterprise-ready BI solutions with SQL Server and Power BI.

---

## About

This project was developed collaboratively by Group 13 (COMM051) as part of MSc Data Science coursework.  
Individual contributions included normalization design, SQL scripting, transaction management, BI cube brainstorming, and presentation.

