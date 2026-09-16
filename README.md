# Financial Ledger Audit & Automated Reconciliation

An end-to-end financial data pipeline demonstrating automated transaction auditing, relational SQL variance analysis, and multi-source bank reconciliation using Python, Pandas, and SQLite.

---

## Portfolio Architecture

### Milestone 1: Ledger Audit & Anomaly Detection
* **File:** `Milestone_1_Ledger_Audit_Automation.ipynb`
* **Technologies:** Python, Pandas, Data Cleaning Pipelines
* **Core Functions:**
  * Ingested unstructured and messy ledger records containing missing invoice identifiers and duplicate postings.
  * Automated data type enforcement and missing-value handling across high-volume transaction sets.
  * Extracted duplicate transaction entries to prevent duplicate payments and audit discrepancies.

### Milestone 2: Relational SQL Financial Analysis
* **File:** `Milestone_2_SQL_Financial_Analysis.ipynb`
* **Technologies:** SQLite, SQL Window Functions, Aggregations, Matplotlib
* **Core Functions:**
  * Designed an in-memory relational schema (`general_ledger`) to capture cross-departmental expenditures.
  * Executed SQL aggregation queries to compute total expenditure, department-level burn, and vendor concentration.
  * Visualized departmental budget variance and expenditure patterns for executive reporting.

### Milestone 3: Bank Reconciliation & Exception Pipeline
* **File:** `Milestone_3_Financial_Reconciliation.ipynb`
* **Technologies:** Python, Pandas Outer Joins, Financial Reconciliation Logic
* **Core Functions:**
  * Automated cross-matching between internal general ledger entries and external banking statements.
  * Classified transactions into cleared balances, unrecorded bank charges, and outstanding checks.
  * Generated an automated exception report to streamline month-end close audit cycles.

---

## Technical Competencies
* **Languages & Querying:** Python (Pandas, NumPy), SQL (SQLite)
* **Financial Controls:** General Ledger Verification, Bank Reconciliation, Duplicate Audit
* **Reporting:** Automated Exception Reporting, Visual Budget Variance Analysis
