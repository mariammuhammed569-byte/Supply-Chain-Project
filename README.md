# 📊 Enterprise Business Intelligence Dashboard (Power BI)

An end-to-end Power BI project designed to analyze and visualize corporate data across multiple departments. This dashboard transforms raw operational data into actionable strategic insights for executive management using a structured data pipeline.

## 🚀 Live Demo & Screenshots
(Tip: Drag and drop your dashboard images here to display them)

## 🏗️ Data Architecture (Medallion Framework)
To ensure high data quality, reliability, and traceability, the data pipeline follows the *Medallion Architecture* framework:
* *Bronze Layer (Raw):* Ingested the raw, unprocessed data directly from source files, maintaining the original structure without modifications.
* *Silver Layer (Cleaned & Enriched):* Cleaned the raw data using Power Query. This stage involved filtering out anomalies, handling missing values, standardizing text inputs (e.g., merging duplicate delivery statuses), and enforcing data types.
* *Gold Layer (Curated for Business):* Created business-level aggregates, star schema relationships, and optimized fact/dimension tables tailored specifically to power the 8 dashboard pages efficiently.

## 🧩 Dashboard Structure
The project consists of 8 interconnected dynamic pages:
1. *Executive Dashboard:* Overview of total revenue ($33.05M), profit, and on-time delivery rates.
2. *Financial Dashboard:* In-depth look at profit margins (12%) and total discounts.
3. *Sales Dashboard:* Analysis of revenue broken down by departments and payment types (Debit, Cash, Transfer).
4. *Orders Dashboard:* Track unique orders and total units sold by region and month.
5. *Supply Chain Efficiency:* Monitor late shipments, delivery risks, and delay days.
6. *Customer Value Dashboard:* Breakdown of average spend per customer and geographic distribution.
7. *Salesman KPI:* Performance tracking and evaluation metrics for the sales team.
8. *Forecasting Dashboard:* Advanced time-series forecasting for revenue and sales trends.

## 🛠️ Tech Stack & Skills Demonstrated
* *Data Engineering:* Medallion Framework (Bronze, Silver, Gold).
* *ETL & Data Cleaning:* Power Query (Data cleaning, handling duplicates, and transformations).
* *Data Modeling:* Star Schema design with proper fact and dimension table relationships.
* *Calculations:* Advanced DAX measures for custom KPIs and time intelligence.
* *Data Visualization:* Custom UI theme, visual hierarchies, and interactive slicers.
