# data-engineering-portfolio
Sanitized examples of data pipeline patterns — BigQuery, GCP Cloud Run, Fivetran/API sync architecture
# Iyanu Adebisi — Data Engineering Portfolio

Data Engineer / Analyst specializing in end-to-end pipeline architecture on Google Cloud Platform.

## Stack
- **Warehouse:** BigQuery
- **ETL/ELT:** Fivetran, custom Python sync pipelines
- **Compute:** Cloud Run (Jobs & Services), Cloud Scheduler
- **Languages:** Python, SQL
- **Visualization:** Looker Studio, custom Flask dashboards

## What I do
I design and build the full data stack for organizations — from raw API/database ingestion through to production dashboards — typically as the sole data engineer/analyst for a company.

**Core competencies:**
- Building resilient ETL pipelines from REST APIs (pagination, rate limiting, incremental syncs, MERGE-based upserts) into BigQuery
- Deploying containerized data services on Cloud Run (Flask + gunicorn + Docker)
- Fixing subtle BigQuery/SQL issues (e.g., re-aggregation errors in BI tools, GROUP BY on computed timestamp columns)
- Building internal dashboards (Flask/Looker Studio) for support ops, marketing, and finance teams
- Cross-dataset/cross-region BigQuery architecture

## Example work (see /examples)
- `sync-pipeline-skeleton/` — generic pattern for paginated API → BigQuery sync with checkpointing
- `dashboard-boilerplate/` — Flask + Cloud Run dashboard pattern (Dockerfile, gunicorn, render_template_string)
- `bigquery-patterns.sql` — reusable SQL patterns (CTE-based timestamp aggregation fix, MERGE upsert template)

## Currently available
Open to contract / fractional data engineering work — GCP, BigQuery, Fivetran, API integrations, dashboarding.
