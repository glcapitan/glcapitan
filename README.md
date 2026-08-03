## Hi there, I'm Erwin Glenn 👋

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1200&color=2E9EF7&center=true&vCenter=true&width=720&lines=Data+Analyst+%7C+Business+Intelligence+Developer;SQL+%7C+Power+BI+%7C+PostgreSQL+%7C+Python;Azure+Data+Factory+%7C+Databricks+%7C+Delta+Lake;Star-schema+modeling+%7C+DAX+%7C+Slowly+changing+dimensions;Turning+6M%2B+rows+into+decision-ready+dashboards" alt="Typing SVG" />
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

I'm a Data / Business Intelligence Analyst who builds **end-to-end analytics solutions** — from cloud data pipelines and SQL modeling through to interactive dashboards that drive decisions. I design star schemas, write performance-minded DAX and SQL, and turn large, messy datasets into reporting that's clean, trustworthy, and business-ready.

My portfolio spans **Azure data engineering** (incremental ELT with Data Factory, a medallion lakehouse on Databricks, SCD Type 2 dimensions), **Power BI & SQL** (star-schema semantic models, performance-minded DAX, dashboard design), **PostgreSQL & Python** (a fraud-analytics app on a 6.3M+ row dataset), and **Excel FP&A** (Power Query → Power Pivot → DAX, time-intelligence and budget-vs-actual reporting). I care about the unglamorous parts that make BI trustworthy — idempotent ETL, grain integrity, and numbers that reconcile end to end.

---

## 📂 Featured Projects

### ☁️ [Azure Incremental Lakehouse](https://github.com/glcapitan/azureproject) — *ADF + Databricks + Delta Live Tables*
An end-to-end Azure data platform: **watermark-driven incremental extraction** from Azure SQL into a medallion lakehouse on **ADLS Gen2**, governed by **Unity Catalog** with managed-identity access — no keys or SAS tokens in code. A single **metadata-driven ADF pipeline** loads five tables by iterating a JSON parameter array, with a conditional branch that cleans up the empty files ADF writes on no-op runs. **Auto Loader** streams bronze → silver; **Delta Live Tables** builds a star schema with **SCD Type 2** dimensions so a stream event joins to whichever subscription tier a user held *at the time*. Validated rather than assumed: 509 gold rows resolving to 500 current + 9 superseded versions, with an integrity check confirming exactly one open row per key.
<br>`Azure Data Factory` · `Databricks` · `Delta Live Tables` · `Unity Catalog` · `PySpark` · `Delta Lake` · `SCD Type 2`

### 💳 [Fintech Fraud Analytics Dashboard](https://github.com/glcapitan/fintech-analytics) — *Streamlit + PostgreSQL*
A BI dashboard on **6.3M+ PaySim transactions**, built around one mandate: cut fraud-investigation false positives without losing catch rate. The headline finding — a single high-precision rule catches **76% of all fraud at 97% precision**, while a second noisy signal inflates flagged volume to 2.5M at near-zero precision — became a concrete recommendation to drop the diluting signal. **[Live dashboard ↗](https://fintech-analytics-ajjjr7c7hzkzkutu9cefgu.streamlit.app)**
<br>`Python` · `PostgreSQL` · `Streamlit` · `Data Modeling`

### 📦 [Supply Chain Analytics Dashboard](https://github.com/glcapitan/supply-chain-analytics-dashboard) — *Power BI Case Study*
An end-to-end BI case study for a mid-size omnichannel retailer: raw sales, inventory, and movement data modeled through **DuckDB + Parquet + SQL** into a **Power BI** executive dashboard with a Kimball-style star schema and a leadership-ready findings deck. The analysis resolved an operations-vs-finance dispute by proving the real risk was **overstock, not stockouts** — ~$95K of working capital trapped in slow movers (24 of 40 SKUs over 90 days of cover), framed into a 90-day rebalancing plan worth a **$50–70K** recovery opportunity.
<br>`Python` · `DuckDB` · `Parquet` · `SQL` · `Power BI` · `DAX`

### 📊 [Financial Performance Dashboard](https://github.com/glcapitan/financial-performance-dashboard) — *Excel FP&A*
A **one-click FP&A reporting dashboard** in Excel: change a single date cell, hit *Refresh All*, and every KPI, variance, and chart updates. **Power Query** unpivots monthly P&L grids into tidy fact tables; a **Power Pivot star schema** (actuals + budget facts over shared date / account / department dimensions) drives **DAX time-intelligence** measures — current month, trailing 3 / 6 / 12, and YTD with prior-period and prior-year comparisons. Surfaces **budget-vs-actual variance**, gross-margin bridges, and operating-expense breakdowns by department and cost type, with KPI tiles and conditional gauges. Includes technical docs and a CFO-style findings memo.
<br>`Excel` · `Power Query` · `Power Pivot` · `DAX` · `FP&A` · `Budget-vs-Actual`

### 📈 [Sales & Customer Performance Dashboard](https://github.com/glcapitan/Tableu-Sales-Customer-Dashboard) — *Tableau*
Two linked **Tableau** dashboards (Sales + Customer) on **9,994 retail transactions (2020–2023)**, tied together by a shared `Select Year` parameter that drives every year-over-year comparison. Built around real findings, not just charts: a **discount margin cliff at 20%** (every tier above it is unprofitable, down to −122.6%), profit concentration far sharper than 80/20 (**8.8% of products drive 80% of profit**, while 301 products quietly destroy $76.7K in margin), and a **57.7% single-purchase customer tail**. Published to Tableau Public.
<br>`Tableau` · `Parameters` · `YoY Analysis` · `Profitability` · `Customer Analytics`

> 📌 More case studies and write-ups are in my pinned repositories below.

---

## 🔭 What I'm Working On

- **Extending the pipeline stack beyond a single cloud** — an orchestration-focused build pairing **Apache Airflow** (Docker) with **dbt Core on Databricks**, covering DAG design, scheduling, dependency management, and tested modular transformations
- Polishing **recruiter-ready BI case studies** end to end: SQL model → DAX → dashboard → documentation
- Preparing for **DP-700: Microsoft Fabric Data Engineer Associate**

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

### Cloud & Data Engineering
<p>
  <img src="https://img.shields.io/badge/Azure%20Data%20Factory-Project%20Based-0078D4?style=flat&logo=microsoftazure&logoColor=white">
  <img src="https://img.shields.io/badge/Databricks-Project%20Based-FF3621?style=flat&logo=databricks&logoColor=white">
  <img src="https://img.shields.io/badge/Delta%20Lake-Project%20Based-00ADD4?style=flat&logo=delta&logoColor=white">
  <img src="https://img.shields.io/badge/PySpark-Project%20Based-E25A1C?style=flat&logo=apachespark&logoColor=white">
  <img src="https://img.shields.io/badge/Unity%20Catalog-Project%20Based-FF3621?style=flat&logo=databricks&logoColor=white">
  <img src="https://img.shields.io/badge/ADLS%20Gen2-Project%20Based-0078D4?style=flat&logo=microsoftazure&logoColor=white">
</p>

### Programming & Databases
<p>
  <img src="https://img.shields.io/badge/PostgreSQL-Hands--On-4169E1?style=flat&logo=postgresql&logoColor=white">
  <img src="https://img.shields.io/badge/Python-Hands--On-3776AB?style=flat&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Streamlit-Hands--On-FF4B4B?style=flat&logo=streamlit&logoColor=white">
  <img src="https://img.shields.io/badge/DuckDB-Project%20Based-FFF000?style=flat&logo=duckdb&logoColor=black">
  <img src="https://img.shields.io/badge/ETL%20%2F%20ELT-Hands--On-00897B?style=flat">
</p>

### Modeling & Business Focus
<p>
  <img src="https://img.shields.io/badge/Star%20Schema-Data%20Modeling-8E24AA?style=flat">
  <img src="https://img.shields.io/badge/Slowly%20Changing%20Dimensions-Type%201%20%26%202-8E24AA?style=flat">
  <img src="https://img.shields.io/badge/Data%20Warehousing-Medallion-6D4C41?style=flat">
  <img src="https://img.shields.io/badge/Incremental%20Loading-Watermark%20Based-6D4C41?style=flat">
  <img src="https://img.shields.io/badge/Financial%20Reporting-Variance%20%26%20Margin-455A64?style=flat">
  <img src="https://img.shields.io/badge/Dashboarding-Business%20Focused-1E88E5?style=flat">
  <img src="https://img.shields.io/badge/KPIs-Decision%20Support-F4511E?style=flat">
</p>

---

## 🎯 Career Focus

Open to roles in **Data Engineering**, **Analytics Engineering**, **Business Intelligence**, and **Data Warehousing** — where I can contribute through pipeline development, dimensional modeling, SQL analysis, and reporting people can trust.

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
