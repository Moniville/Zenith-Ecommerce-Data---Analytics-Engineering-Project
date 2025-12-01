# Zenith E-Commerce: Data & Analytics Engineering Project

**Title:** Scaling Zenith E-Commerce: Strategic Data Modeling and Performance Optimization (Snowflake & Power BI)

**Category:** Data Engineering & Business Intelligence

**Client:** Zenith E-Commerce (High-Growth Retail Startup)

**Project Lead:** Monivi Hope Ogidi

**Date:** November 2025


---

## The Problem: Addressing Analytical Scalability

Zenith E-Commerce, a high-growth online retailer, was struggling to support its massive transactional volume with slow, fragmented data. The analytics environment lacked the fundamental structure necessary to answer key business questions accurately and at scale.

The objective was to transition the company from raw operational data to a **secure, query-optimized, and high-performance data warehouse** to mitigate risks like stock-outs, inaccurate reporting, and missed growth opportunities.

---

## The Solution: End-to-End Cloud-Native Architecture

This project involved providing basic Data Engineering expertise to build a complete, resilient analytics pipeline, from data ingestion to visualization.

### Key Technology Stack:
* **Cloud Data Warehouse:** Snowflake (for scalable storage and processing).
  
* **Data Modeling:** Star Schema (for optimized BI performance).
  
* **Visualization:** Power BI (for executive reporting).
  
* **Transformation:** Complex SQL (CTEs, joins, aggregations).

### Core Implementation Steps:
1.  **Snowflake Infrastructure Setup:** Created databases, warehouses, and implemented **Role-Based Access Control (RBAC)** to ensure data governance and secure access.
2.  **Star Schema Modeling:** Transformed raw transactional data into a **Star Schema** centered on the `FACT_SALES` table, linked to `DIM_CUSTOMERS`, `DIM_PRODUCTS`, and `DIM_DATES`.
3.  **Analytics Layer Development:** Developed **8 key analytical SQL queries** to extract critical business intelligence for visualization.
4.  **BI Connectivity:** Configured Power BI to securely connect to Snowflake for report generation.

---

## The Result: Actionable Insights & Optimized Operations

The project successfully delivered a robust analytics platform that empowers executives and operational teams with immediate, accurate insights, driving tangible business value:

| Key Finding | Business Impact |
| :--- | :--- |
| **Inventory Risk Mitigation** | Pinpointed the highest-revenue product with stock critically low (8 units left), **avertable a potential revenue loss** from stock-outs. |
| **Customer Value Segmentation** | Identified the Most Valuable Customer (MVC), **Adriana Knox**, who generated over **$91.8K** in lifetime revenue, enabling highly targeted loyalty programs. |
| **Operational Benchmarking** | Confirmed **Q4 2024** as the peak quarter (\$770.4M in revenue), establishing clear performance targets and capacity planning requirements. |
| **Payment Strategy** | Found that **Bank Transfer and PayPal** are the preferred methods in top revenue regions, guiding optimization for the checkout funnel. |

This architecture provides Zenith E-Commerce with the foundation needed to maintain its high-growth trajectory and transition to **proactive, data-driven decision-making.**

---

### 📂 Repository Contents
* **`SQL_Queries_Zenith.sql`:** All 8 analytical queries used in Snowflake.
* **`Findings_Summary.md`:** Tabulated output of the analytical queries supporting the findings above.
* **`Zenith_Data_Model.png`:** Diagram of the Star Schema architecture.
* **`Zenith_PowerBI_Report.pdf`:** The final executive report, including the Cover Page and key dashboards.
