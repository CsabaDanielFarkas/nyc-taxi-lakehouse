\# NYC Taxi Lakehouse Analytics Platform



A production-style data engineering and analytics project built with

Databricks, Apache Spark, Delta Lake, SQL, and Power BI.



\## Business Problem



Build a production-style analytics platform for NYC taxi operations.



The platform ingests taxi trip data, validates and cleans the data,

transforms it through a Bronze–Silver–Gold lakehouse architecture,

creates analytics-ready dimensional models, and serves business

insights through Power BI.



\## Stakeholders



\- Operations Managers

\- Finance Analysts

\- Data Analysts



\## Architecture



Source → Bronze → Silver → Gold → Databricks SQL → Power BI



\## Key KPIs



\- Total trips

\- Total fare revenue

\- Total revenue

\- Average fare

\- Average trip distance

\- Average trip duration

\- Revenue per trip

\- Trips per hour

\- Average tip percentage

\- Busiest pickup locations

\- Busiest dropoff locations

\- Demand by weekday and hour

\- Month-over-month trip growth

\- Month-over-month revenue growth

\- Suspicious trip count

\- Data quality rate



\## Technology Stack



\- Databricks

\- Apache Spark / PySpark

\- Delta Lake

\- Unity Catalog

\- Databricks Workflows

\- Databricks SQL

\- Python

\- SQL

\- pytest

\- Git / GitHub

\- Power BI



\## Project Structure



Reusable transformation logic is stored under `src/`.

Databricks notebooks are used primarily for exploration and demonstrations.

Automated tests are stored under `tests/`.

Infrastructure and Databricks job definitions are stored under `resources/`.



\## Status



🚧 In development

