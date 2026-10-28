<h1 align="center">Samuel Fernandes</h1>

<p align="center">
  <b>Data Engineering</b> · Python · SQL · PySpark · Azure Databricks<br/>
  Rio de Janeiro, Brazil
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/samuel-fernandes-de"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <img src="https://img.shields.io/badge/Microsoft%20Certified-DP--750-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" alt="Microsoft Certified DP-750"/>
  <img src="https://img.shields.io/badge/AWS%20Certified-AI%20Practitioner-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS Certified AI Practitioner"/>
</p>

---

## About me

I'm a data-focused developer at the **Rio de Janeiro State Government**, where I build and maintain internal systems and handle the data work behind them. Day to day, that means integrating and cleaning inconsistent operational data, writing Python and SQL against relational databases, and working in a team with Git, code review and CI.

I enjoy turning messy data into datasets people can trust, and I'm specializing in the **Lakehouse stack**: Spark, Databricks, Delta Lake and Azure. My goal is to grow as a Data Engineer and, in the long run, into Data Architecture.

## Experience

**Systems & Data Development** — Rio de Janeiro State Government · *Jul 2026 – present*
<br/>Development and maintenance of internal applications (Python, Django, PostgreSQL, Docker), data integration and standardization, and code review.

**IT & Data Support** — Rio de Janeiro State Government · *Apr 2026 – Jul 2026*
<br/>Data organization and support for internal processes.

## Education

- 📚 **Postgraduate Specialization in Data Engineering** — PUC Minas · *2026 – 2027 (in progress)*
- 🎓 **Technologist Degree in Systems Analysis and Development** — Faculdade de Tecnologia Senac Rio · *2023 – 2025*

## Certifications

| Certification | Issuer | Issued |
| --- | --- | --- |
| Azure Databricks Data Engineer Associate (DP-750) | Microsoft | Oct 2026 |
| AWS Certified AI Practitioner (AIF-C01) | Amazon Web Services | Sep 2026 |
| Databricks Fundamentals Accreditation | Databricks Academy | Sep 2026 |
| Data Engineer Associate | DataCamp | Jul 2026 |
| SQL (Intermediate) | HackerRank | Jun 2026 |
| EF SET English Certificate — C1 | EF | Oct 2025 |

🗓️ Next up: **AWS Certified Cloud Practitioner** (Nov 2026)

## Tech stack

**Data & languages**
<br/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
<img src="https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white" alt="SQL"/>
<img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"/>

**Lakehouse & cloud**
<br/>
<img src="https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white" alt="Apache Spark"/>
<img src="https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white" alt="Databricks"/>
<img src="https://img.shields.io/badge/Delta%20Lake-00ADD4?style=flat-square&logo=delta&logoColor=white" alt="Delta Lake"/>
<img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" alt="Azure"/>
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS"/>

**Engineering**
<br/>
<img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white" alt="Django"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git"/>
<img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions"/>
<img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" alt="pytest"/>
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux"/>

**Practices:** ETL/ELT · Medallion architecture · data quality and validation · REST API ingestion · deduplication and idempotent reprocessing · automated testing · CI

## Projects

### 🏞️ [Mini Lakehouse de Vendas](https://github.com/samuelferoli/mini-lakehouse-vendas)
A Medallion pipeline on **Azure Databricks**. Raw sales data lands in Bronze, is cleaned with **PySpark** in Silver and becomes customer metrics with **Spark SQL** in Gold. Every table is stored as **Delta** and registered in **Unity Catalog**.

`Databricks` `PySpark` `Spark SQL` `Delta Lake` `Unity Catalog`

### 📊 [Sales Report Automation](https://github.com/samuelferoli/sales-report-automation)
A modular Python ETL that consolidates inconsistent Excel and CSV reports from several stores. It handles mixed encodings and delimiters, maps different column names to one schema, cleans currency and date values, and sends invalid rows to an audit tab with the reason for each rejection. It also removes duplicate orders and produces a multi-tab Excel report with store and product KPIs. Tested with pytest and GitHub Actions.

`Python` `Pandas` `openpyxl` `Data Quality` `pytest` `CI`

### 📮 [ViaCEP Medallion Pipeline](https://github.com/samuelferoli/viacep-medallion-pipeline)
An end-to-end pipeline over the public ViaCEP API. It ingests data with timeouts and error handling, keeps the raw JSON in Bronze, cleans and deduplicates it with lineage metadata in Silver, and builds aggregations by region, state, city and area code in Gold. It includes tests, CI and a local dashboard.

`Python` `REST API` `Medallion` `Testing` `GitHub Actions`

### 🏃 [Pacelake](https://github.com/samuelferoli/intervals_api_project) · *in design*
A personal training and wellness app built on a data engineering pipeline. Data from Intervals.icu (activities, sleep and wellness) will flow through webhooks into a Delta Lakehouse on ADLS Gen2, be processed with PySpark and served to a Django application. The architecture, decision log and feasibility checks are documented. Implementation starts after the platform checks pass, within a budget of 20 BRL per month.

`Azure` `ADLS Gen2` `PySpark` `Delta Lake` `Django` `PostgreSQL`

## Currently

- 🔨 Running the platform feasibility checks for **Pacelake**
- 📖 Preparing for **AWS Cloud Practitioner** and progressing in my postgraduate program
- ✍️ Writing about data and technology at **BrasaBit**

---

<p align="center">
  Open to <b>Data Engineering</b> opportunities · Rio de Janeiro (on-site or hybrid)<br/>
  <a href="https://www.linkedin.com/in/samuel-fernandes-de">Let's connect on LinkedIn</a>
</p>
