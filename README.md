# Sales Analytics Dashboard (Power BI + MySQL)

Power BI dashboard project packaged with a MySQL database dump so reviewers can recreate the source data and reproduce the model.

---

## What this repo contains
- Power BI dashboard (`.pbix`)
- MySQL dump (`.sql`) that recreates the dataset locally

---

## How to reproduce (MySQL + Power BI)
1) Restore the database:
   - Create a database in MySQL
   - Import `db_dump.sql`

2) Open the dashboard:
   - `Sales Insight Project.pbix`
   - Point the data source to your local MySQL instance if Power BI prompts for credentials

---

## Files
- `Sales Insight Project.pbix`
- `db_dump.sql`

---

## Review request
Open an Issue titled: **Review: sales-analytics-dashboard-powerbi**  
Feedback wanted: dashboard structure, measure naming, and what a hiring manager would want to see first.
