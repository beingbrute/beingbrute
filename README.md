## Aditya Ranjan

**Data Analyst | SQL · Python · Power BI · Tableau**

I build end-to-end analytics solutions — from raw data and SQL through to dashboards that answer a specific business question. Based in Noida, India. Open to relocation, available to join immediately.

**Portfolio:** https://beingbrute.github.io

**LinkedIn:** https://www.linkedin.com/in/aditya-ranjan-data

**Email:** adityaranjan17302215@gmail.com

---

### Featured Projects

#### Payment Transaction Controls & Fraud Risk Analytics

`Databricks` `PySpark` `SQL` `Alteryx` `Python` `Power BI` `Tableau` `Excel` — https://github.com/beingbrute/payment-fraud-risk-analytics

2,770,409 transfer/cash-out transactions run through a Bronze/Silver/Gold Databricks pipeline, five rule-based fraud controls (two cross-validated exactly against an independent Alteryx rebuild), a leakage-aware fraud-model comparison, and a 4-page Power BI dashboard.

**Key finding:** the random forest's 100% precision is a red flag, not a win — it's reading the same balance-draining pattern PaySim uses to simulate fraud internally, not a generalizable fraud signal; the simpler rule-based controls (70%/65% precision) and logistic regression give a more trustworthy read on real-world performance.

#### Customer Revenue & Retention Analytics

`Python` `Snowflake` `Tableau` `local LLM` — https://github.com/beingbrute/Customer-Revenue-Retention-Analytics

1,033,036 retail transactions through a three-layer Snowflake warehouse (RAW, STAGING, ANALYTICS), with row counts and revenue totals reconciled across every layer. RFM segmentation, monthly cohort retention, and product classification using a locally hosted LLM.

**Key finding:** the Champions segment is 24.74% of identified customers but generates 74.04% of identified-customer net revenue.

#### Loan Default Risk Analysis

`Power BI` `DAX` `Power Query` — https://github.com/beingbrute/Loan-Default-Risk-Analysis

A four-page risk report on a 255,347-loan portfolio covering borrower risk drivers, financial exposure and portfolio trends, built on a governed semantic model with YoY and YTD time intelligence.

**Key finding:** defaulted loans carry above-average balances — 13.15% of portfolio value against an 11.61% default rate.

#### Inventory Demand & Supply Analysis

`SQL Server` `MySQL` `Power BI` `DAX` — https://github.com/beingbrute/Inventory-Demand-Supply-Analysis

Inventory fulfillment analysis including a production data-quality remediation and a SQL Server to MySQL reporting migration, revalidated after the source change.

**Key finding:** $97.37K in revenue at risk, ranked differently by shortage volume than by financial exposure.

---

### Tech Stack

**Languages & Querying:** SQL (Snowflake, Databricks, SQL Server, MySQL), Python (Pandas, NumPy, scikit-learn), DAX, Power Query

**BI & Visualisation:** Power BI, Tableau, Advanced Excel, Matplotlib, Seaborn

**Data Engineering:** ETL pipelines, data warehousing, dimensional modeling, medallion architecture (Bronze/Silver/Gold), data validation and reconciliation

**Analytics:** RFM segmentation, cohort retention analysis, KPI development, time intelligence, ABC analysis, fraud control testing, predictive modeling

**Tools:** Jupyter Notebook, Git, GitHub, VS Code, Ollama, Alteryx Designer

---

### How I work

**Start with the business question.** What decision does this need to support?

**Make the numbers trustworthy.** Validate, reconcile across layers, document assumptions.

**Make the insight usable.** Clear dashboards, with the limits of the analysis stated plainly.

Every project above includes the underlying SQL and DAX, full documentation, and the reasoning behind each decision.
