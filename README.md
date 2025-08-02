# SSAS BI Cube & Database Design Project

This project was completed as part of the **COMM051 Database Systems** module (MSc Data Science) at the University of Surrey.  
It demonstrates end-to-end work in **database design, optimization, and business intelligence (BI)** using SQL Server and SSAS Tabular Cubes.

---

## Context

The project was based on a case study for **MumsNet**, a leading UK retail brand specializing in maternity and baby products.  
The company required improvements to its existing database structure and the introduction of a BI platform to analyze sales and customer data.

**Objectives:**
- Normalize historic order, product, and customer tables to 3NF.
- Implement stored procedures with transactional support and error handling.
- Design an SSAS Tabular Cube with product, customer, and time hierarchies for multidimensional analysis.
- Provide insights such as cancellation rates, order fulfillment, and sales trends.

---

## Project Overview

1. **Database Normalization (3NF)**
   - Normalized `OrderItem`, `Product`, and `Customer` tables to 3NF to eliminate redundancy.
   - Introduced primary/foreign keys, surrogate keys, and ER diagrams for referential integrity.

2. **SQL Enhancements**
   - Created **views, stored procedures, and indexes** for order processing.
   - Implemented transaction control (`BEGIN TRAN`, `COMMIT`, `ROLLBACK`) with error handling.

3. **SSAS Tabular Cube Design**
   - Built cube with **Customer, Product, and Time dimensions** and calculated measures (e.g., % cancellations, distinct orders).
   - Added hierarchies (Customer → City → Region → Country; Product → Product Group → Variant).

4. **Business Insights**
   - Enabled analysis of KPIs such as sales trends, order fulfillment, and cancellation rates across multiple dimensions.

---

## Key Skills Demonstrated

- **Database Design & Optimization:** 3NF, ER diagrams, indexing
- **SQL Development:** Stored procedures, transactions, error handling
- **Business Intelligence (BI):** SSAS Tabular, DAX calculations, hierarchies, measures
- **Data Storytelling:** KPI reporting and insights via cube analysis

---

## Deliverables

- [Final Report (PDF)](link-to-report)
- [Video Walkthrough (YouTube/OneDrive link)](link-to-video)

---

## How to Use

1. Review the **report** for database schema and BI design decisions.  
2. Watch the **video walkthrough** for an explanation of the SSAS cube and insights.  
3. Adapt the design principles for enterprise-ready BI solutions using SQL Server and Power BI/Tableau.

---

## About

Developed collaboratively as part of Group 13 (COMM051).  
My contributions included normalization design, stored procedures, transaction management, BI cube brainstorming, and presentation.
