This project implements a complete end-to-end automated data pipeline for stock market analytics using:

Apache Airflow for orchestration 

yfinance for data extraction

dbt for ELT transformations

Superset for dashboard visualization

yfinance → Airflow ETL DAG → Snowflake RAW  → Airflow ELT (dbt) DAG 
→ Snowflake ANALYTICS → Superset Dashboards


The pipeline processes historical stock data, transforms it into analytical models, and visualizes insights using BI dashboards.
