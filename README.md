# End-to-End Data Engineering Project - FMCG Domain
Project Overview
This project simulates a real-world industry scenario where a major sports equipment manufacturer (Atlan) acquires a smaller startup (Sports Bar). The goal is to consolidate data from both companies into a single, reliable Lakehouse architecture for streamlined business insights.

Key Challenges
Merging structured ERP data from the parent company with unstructured, messy data (spreadsheets, APIs) from the startup.
Setting up an ELT pipeline within the Databricks ecosystem.
Ensuring the solution is scalable and reliable for long-term use.
Technical Stack
Cloud Platform: Databricks (Free Edition), Amazon S3 (Data Lake)
Languages: Python (PySpark), SQL
Data Modeling: Medallion Architecture (Bronze, Silver, Gold layers) 
Orchestration: Databricks Workflows
BI & Analytics: Databricks Dashboards, Genie
Pipeline Architecture
Ingestion: Raw data from Sports Bar (spreadsheets, etc.) is uploaded to Amazon S3.
Bronze Layer: Raw data ingestion into Databricks tables.
Silver Layer: Data cleaning, transformation, and handling business rules.
Gold Layer: Creating business-ready dimensional and fact tables.
Consolidation: Merging child company gold data with parent company gold data.
Dashboard & Insights
Created a comprehensive Databricks dashboard to track KPIs such as:

Total Revenue and Quantity Sold.
Revenue share by channel (Retailer vs. Direct).
Monthly trends for consolidated data.
Learning Outcomes
Configured Databricks connectivity with AWS S3.
Implemented Incremental Data Load strategies.
Mastered PySpark for data transformations and cleaning.
