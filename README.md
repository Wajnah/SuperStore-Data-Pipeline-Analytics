# SuperStore Analytics: End-to-End Data Pipeline & Executive Dashboard

An end-to-end data analytics project that demonstrates the entire data lifecycle: from raw data extraction and preprocessing using Python, to warehousing and structured querying in a local SQL database, culminating in a highly optimized, dual-page executive Power BI dashboard.

---

## Project Architecture & Workflow

1. **Data Preprocessing (Python):** Cleaned raw CSV files, handled missing values, formatted data types, and prepared the dataset for database injection using `Pandas` and `NumPy`.
2. **Data Warehousing (SQL):** Designed relational table structures, loaded the cleaned data into a local SQL database, and wrote optimized SQL queries to validate metrics.
3. **Data Visualization (Power BI):** Developed a dynamic data model, implemented complex DAX measures, and designed a custom dark-themed executive dashboard focused on performance and business insights.

---

## Tech Stack & Tools

- **Languages:** Python, SQL
- **Libraries:** Pandas, sqlite3و openpyxlو xlrd
- **Database:** Local SQL Server / PostgreSQL
- **BI Tool:** Power BI Desktop

---

## Dashboard Insights & Features

The Power BI dashboard consists of two strategically divided pages to provide actionable insights for decision-makers:

### 1. Executive Insights (Revenue & Profitability)
Focuses on financial health, margins, and performance distribution across sub-categories and regions.
- Includes a **Scatter Chart** for product profitability analysis (a clean, non-cluttered alternative to Treemaps).
- High-level KPI cards with month-over-month (MoM) trends.




### 2. Operational & Risk Analysis (Returns & Logistics)
Focuses on operational efficiency, supply chain bottlenecks, and root cause analysis for product returns.
- Features an advanced **Decomposition Tree** allowing users to drill down into the root causes of returns by shipping mode and category.
- Features a **Line Chart** tracking the return rate by month to monitor operational stability over time.




---

## Repository Structure

```text
├── 1-Data-Extraction-Preparation/   # Raw CSV files and source data
├── 2-Python-ETL/                    # Python scripts/Notebooks for data cleaning
├── 3-SQL-Database/                  # SQL scripts, DDL, and verification queries
└── 4-PowerBI-Dashboard/            # .pbix file and dashboard screenshots
