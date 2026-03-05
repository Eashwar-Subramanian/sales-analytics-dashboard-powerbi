# Sales Analytics Dashboard (Power BI + MySQL)

Power BI sales dashboard packaged with a MySQL database dump so reviewers can recreate the source data locally and reproduce the model.

## What’s in this repo
- `Sales Insight Project.pbix` — Power BI dashboard
- `db_dump.sql` — MySQL dump that recreates the dataset

## How to reproduce (MySQL → Power BI)
### 1) Restore the database
Use any MySQL client (Workbench / DBeaver / CLI) and run:

1. Create a database (example name: `sales_analytics`)
2. Import `db_dump.sql` into that database

### 2) Open the dashboard
1. Open `Sales Insight Project.pbix`
2. If Power BI prompts for credentials:
   - Point the data source to your local MySQL instance
   - Select the restored database (the one you imported the dump into)

## Feedback I want
Open a GitHub Issue titled: **Review: sales-analytics-dashboard-powerbi** and tell me:
1) Whether the dashboard structure is easy to understand in under 30 seconds  
2) Which visuals feel redundant vs essential  
3) What a hiring manager would want to see first on the landing page
