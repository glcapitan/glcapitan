## Hi there, I'm Erwin Glenn 👋

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1200&color=2E9EF7&center=true&vCenter=true&width=720&lines=Data+Analyst+%7C+Business+Intelligence+Developer;SQL+%7C+Power+BI+%7C+PostgreSQL+%7C+Python;Star-schema+modeling+%7C+DAX+%7C+Financial+%26+operational+reporting;Turning+6M%2B+rows+into+decision-ready+dashboards" alt="Typing SVG" />
</div>

<p align="center">
  <a href="https://linkedin.com/in/erwin-glenn-capitan-ii/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin">
  </a>
  <a href="mailto:glcapitan007@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-green?style=for-the-badge&logo=gmail">
  </a>
</p>

---

## 🚀 About Me

I'm a Data / Business Intelligence Analyst who builds **end-to-end analytics solutions** — from SQL data modeling and ETL through to interactive dashboards that drive decisions. I design star schemas, write performance-minded DAX and SQL, and turn large, messy datasets into reporting that's clean, trustworthy, and business-ready.

My recent portfolio work spans **Power BI & SQL** (star-schema semantic models, performance-minded DAX, dashboard design), **PostgreSQL & Python** (a fraud-analytics app on a 6.3M+ row dataset), **Excel FP&A** (Power Query → Power Pivot → DAX, time-intelligence and budget-vs-actual reporting), and **data-warehouse design** using medallion (bronze/silver/gold) architecture. I care about the unglamorous parts that make BI trustworthy — idempotent ETL, grain integrity, and numbers that reconcile end to end.

---

## 📂 Featured Projects

### 💳 [Fintech Fraud Analytics Dashboard](https://github.com/glcapitan/fintech-analytics) — *Streamlit + PostgreSQL*
A BI dashboard on **6.3M+ PaySim transactions**, built around one mandate: cut fraud-investigation false positives without losing catch rate. The headline finding — a single high-precision rule catches **76% of all fraud at 97% precision**, while a second noisy signal inflates flagged volume to 2.5M at near-zero precision — became a concrete recommendation to drop the diluting signal. **[Live dashboard ↗](https://fintech-analytics-ajjjr7c7hzkzkutu9cefgu.streamlit.app)**
<br>`Python` · `PostgreSQL` · `Streamlit` · `Data Modeling`

### 📊 [Financial Performance Dashboard](https://github.com/glcapitan/financial-performance-dashboard) — *Excel FP&A*
A **one-click FP&A reporting dashboard** in Excel: change a single date cell, hit *Refresh All*, and every KPI, variance, and chart updates. **Power Query** unpivots monthly P&L grids into tidy fact tables; a **Power Pivot star schema** (actuals + budget facts over shared date / account / department dimensions) drives **DAX time-intelligence** measures — current month, trailing 3 / 6 / 12, and YTD with prior-period and prior-year comparisons. Surfaces **budget-vs-actual variance**, gross-margin bridges, and operating-expense breakdowns by department and cost type, with KPI tiles and conditional gauges. Includes technical docs and a CFO-style findings memo.
<br>`Excel` · `Power Query` · `Power Pivot` · `DAX` · `FP&A` · `Budget-vs-Actual`

### 📦 [Supply Chain Analytics Dashboard](https://github.com/glcapitan/supply-chain-analytics-dashboard) — *Power BI Case Study*
An end-to-end BI case study for a mid-size omnichannel retailer: raw sales, inventory, and movement data modeled through **DuckDB + Parquet + SQL** into a **Power BI** executive dashboard with a Kimball-style star schema and a leadership-ready findings deck. The analysis resolved an operations-vs-finance dispute by proving the real risk was **overstock, not stockouts** — ~$95K of working capital trapped in slow movers (24 of 40 SKUs over 90 days of cover), framed into a 90-day rebalancing plan worth a **$50–70K** recovery opportunity.
<br>`Python` · `DuckDB` · `Parquet` · `SQL` · `Power BI` · `DAX`

### 📈 [Sales & Customer Performance Dashboard](https://github.com/glcapitan/Tableu-Sales-Customer-Dashboard) — *Tableau*
Two linked **Tableau** dashboards (Sales + Customer) on **9,994 retail transactions (2020–2023)**, tied together by a shared `Select Year` parameter that drives every year-over-year comparison. Built around real findings, not just charts: a **discount margin cliff at 20%** (every tier above it is unprofitable, down to −122.6%), profit concentration far sharper than 80/20 (**8.8% of products drive 80% of profit**, while 301 products quietly destroy $76.7K in margin), and a **57.7% single-purchase customer tail**. Published to Tableau Public.
<br>`Tableau` · `Parameters` · `YoY Analysis` · `Profitability` · `Customer Analytics`

> 📌 More case studies and write-ups are in my pinned repositories below.

---

## 🔭 What I'm Working On

- **An end-to-end analytics-engineering project** on the modern data stack — building production-style ELT and a dimensional model from raw data to tested, query-ready tables. Scope includes:
  - **ELT pipelines** with full and **incremental loading**
  - **Lakehouse** architecture on an open table format (**Delta Lake**)
  - **Apache Spark / PySpark** for large-scale transformation
  - **Relational + dimensional modeling**, including **slowly changing dimensions (SCD)**
  - **Data orchestration** with **Airflow** and **Azure Data Factory**
  - Modular, tested transformations with **dbt on Databricks**
- Polishing **recruiter-ready BI case studies** end to end: SQL model → DAX → dashboard → documentation
- Preparing for **DBT Analytics Engineering Certification**

---

## 🛠️ Technical Skills

### Data Analytics & BI
<p>
  <img src="https://img.shields.io/badge/SQL-Strong-4479A1?style=flat&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/Power%20BI-Strong-F2C811?style=flat&logo=powerbi&logoColor=black">
  <img src="https://img.shields.io/badge/DAX-Hands--On-F2C811?style=flat&logo=powerbi&logoColor=black">
  <img src="https://img.shields.io/badge/Excel-Strong-217346?style=flat&logo=microsoft-excel&logoColor=white">
  <img src="https://img.shields.io/badge/Power%20Query-Hands--On-217346?style=flat&logo=microsoft-excel&logoColor=white">
  <img src="https://img.shields.io/badge/Power%20Pivot-Hands--On-1F3864?style=flat&logo=microsoft-excel&logoColor=white">
  <img src="https://img.shields.io/badge/Tableau-Hands--On-E97627?style=flat&logo=tableau&logoColor=white">
</p>

### Data Engineering & Programming
<p>
  <img src="https://img.shields.io/badge/PostgreSQL-Hands--On-4169E1?style=flat&logo=postgresql&logoColor=white">
  <img src="https://img.shields.io/badge/Python-Hands--On-3776AB?style=flat&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Streamlit-Hands--On-FF4B4B?style=flat&logo=streamlit&logoColor=white">
  <img src="https://img.shields.io/badge/DuckDB-Project%20Based-FFF000?style=flat&logo=duckdb&logoColor=black">
  <img src="https://img.shields.io/badge/ETL-Hands--On-00897B?style=flat">
</p>

### Modeling & Business Focus
<p>
  <img src="https://img.shields.io/badge/Star%20Schema-Data%20Modeling-8E24AA?style=flat">
  <img src="https://img.shields.io/badge/Data%20Warehousing-Medallion-6D4C41?style=flat">
  <img src="https://img.shields.io/badge/Financial%20Reporting-Variance%20%26%20Margin-455A64?style=flat">
  <img src="https://img.shields.io/badge/Row--Level%20Security-Familiar-607D8B?style=flat">
  <img src="https://img.shields.io/badge/Dashboarding-Business%20Focused-1E88E5?style=flat">
  <img src="https://img.shields.io/badge/KPIs-Decision%20Support-F4511E?style=flat">
</p>

---

## 🎯 Career Focus

Open to roles in **Data Analytics**, **Business Intelligence**, and **Data Warehousing**, where I can contribute through SQL analysis, semantic data modeling, dashboard development, and reliable reporting pipelines.

---

## 📫 Let's Connect

<p align="center">
  <a href="https://linkedin.com/in/erwin-glenn-capitan-ii/">
    <img src="https://img.shields.io/badge/LinkedIn-Erwin%20Glenn%20Capitan%20II-blue?style=for-the-badge&logo=linkedin">
  </a>
  <a href="mailto:glcapitan007@gmail.com">
    <img src="https://img.shields.io/badge/Email-glcapitan007%40gmail.com-green?style=for-the-badge&logo=gmail">
  </a>
</p>
