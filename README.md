# Enterprise Data Analytics Portfolio 🚀

Welcome to my central data analytics and engineering repository. This space showcases production-grade data pipelines, advanced SQL data transformations, and executive business intelligence assets built to enterprise standards.

## 🛠️ The Core Technical Stack
* **Database Management:** MySql
* **Analytics Engineering:** dbt (Data Build Tool), Snowflake, Google BigQuery
* **Cloud Architecture:** Google Cloud Platform (GCP)
* **Business Intelligence:** Microsoft Power BI (DAX, Power Query)
* **Programming & Automation:** Python (Pandas, BeautifulSoup)

---

## 📈 Active Production Projects


### 1. Advanced PAN Card Validation Engine (SQL)
* **Core Objective:** Cleaned, audited, and validated a staging database containing 10,001 raw Indian PAN Card records. Built data quality guardrails against structurally malformed entries and fraudulent sequence patterns.
* **Tech Stack:** MySQL Workbench, Regular Expressions (`REGEXP_LIKE`)
* **Key Insights & Discovered Data Profile:**
  * **Total Records Processed:** 10,001
  * **Valid PAN entries:** 3,180 (Records passing all strict corporate formatting constraints)
  * **Invalid/Fake entries:** 5,854 (Caught repeating duplicate characters like `AAAAA` or `1111` and straight sequences like `ABCDE` or `1234`)
  * **Missing or Empty rows:** 967 (Isolated using custom `TRIM` and `IS NULL` checking blocks)
* **Core Skills Practiced:** Regular Expression position anchors (`^`, `$`), dynamic character backreferences (`([A-Z])\\1`), and summary metric aggregation handling using `WITH ROLLUP` and `COALESCE()`.

---
## 🎓 Credentials & Certifications Track
* **Microsoft Power BI Data Analyst** (PL-300) — *In Progress*
* **Microsoft Fabric Analytics Engineer** (DP-600) — *In Progress*
* **Google Associate Cloud Engineer** (ACE) — *In Progress*