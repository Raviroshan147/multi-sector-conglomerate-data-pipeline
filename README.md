# 🚀 Enterprise-Grade Multi-Sector Relational Data Pipeline

## 📊 Project Overview
This repository contains a production-grade synthetic dataset engineered in a fully decoupled **Star Schema Architecture (Fact & Dimension Model)**. The data spans across **1-Full Year (365 Days)** for 7 diversified business sectors under a single corporate conglomerate framework. 

Designed natively to replicate actual corporate ERP outputs, this pipeline eliminates raw data flattening and establishes clean primary-foreign key relationships optimized for deep **Power BI (DAX)** analysis and **SQL Cloud Warehousing (GCP BigQuery)**.

---

## 🏗️ Data Architecture (Star Schema Design)
Unlike standard flattened spreadsheets, this project enforces relational integrity across 7 key business units. Each sector contains distinct Lookup (Dimension) and Transactional (Fact) datasets:

1. **Digital Marketing Agency Engine**
   * `Dim_Marketing_Clients`: Client corporate profiles, vertical industries, assigned accounts.
   * `Fact_Marketing_Performance`: Daily dynamic funnel impressions, real CTR%, conversions, ad spend, and computed revenue.
2. **Hospital Management System**
   * `Dim_Hospital_Doctors`: Specialized doctors, medical departments, and static consultation structures.
   * `Fact_Hospital_Admissions`: Chronological patient intake metrics, age-gender demographics, dynamic pharmacy and lab billings.
3. **School Performance & Fees Tracker**
   * `Dim_School_Students`: Student records, standard grade levels, financial fee metrics.
   * `Fact_School_Academics`: Academic subject scores, granular student attendance rate %, outstanding fee logs.
4. **Chartered Accountant (CA) Corporate Firm**
   * `Dim_CA_Clients`: B2B legal corporate structures (LLPs, Pvt Ltd), business identifiers.
   * `Fact_CA_Invoices`: Invoicing timelines, automated statutory taxation allocations (GST 18%), ledger compliance states.
5. **Coal Trading Analytics (Dhanbad Energy Market)**
   * `Fact_Coal_Trading_Deals`: High-volume spot and auction market deals, G4-G13 energy grade margins, statutory Clean Energy Cess computation.
6. **Coal Transporter Logistics Fleet**
   * `Fact_Coal_Logistics_Trips`: Real RTO vehicle tracking (JH-10 Dhanbad series format), payload optimization, route-wise diesel cost burns.
7. **Pharmaceutical & Chemist Operations (Flagship Engine)**
   * `Dim_Pharmacy_Products`: Master drug dictionary, therapeutic drug groups, base commercial margins.
   * `Fact_Pharmacy_Sales`: High-fidelity point-of-sale logs, inventory batch codes, chronologically generated active shelf-expiry matrices.

---

## ⚡ Technical Implementations & Features
* **Zero Data Redundancy:** Standardised normalization prevents text duplications across data points.
* **Faker Integration:** Generates authentic global corporate listings and realistic regional logistics frameworks instead of simple incremental dummy tokens.
* **Analytical KPI Fields Built-in:** Includes essential dimensions like dynamic Conversion Rates, Profit Splits, and RTO structural data to support immediate DAX logic application.

## 🛠️ Tech Stack & Deployment
* **Data Engineering:** Python 3.x, Pandas, OpenPyXL, Faker Engine
* **Target Storage Target:** Google Cloud Platform (GCP) BigQuery, Power BI Semantic Model
