# Supply Chain Data Platform

A learning project for building an end-to-end data engineering pipeline using a retail orders dataset.

The goal is to simulate a supply-chain analytics platform with a medallion architecture:

- Bronze: raw ingested data
- Silver: cleaned and standardized data
- Gold: business-ready tables for analytics, forecasting and dashboarding

## Planned stack

- Python
- SQL
- PySpark
- Azure Databricks
- Delta Lake
- Power BI

## Dataset

The project starts from a retail orders dataset containing customers, orders, products and regions in Parquet format.

Later iterations may add a synthetic inventory table to support supply-chain use cases such as stockout risk and reorder recommendations.