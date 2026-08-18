E-Commerce Medallion Architecture

Project Overview

E-commerce data pipeline using:

- Python
- PySpark
- Databricks AWS
- Parquet
- Delta Lake
- SQL
- Power BI

Architecture

Source
 ↓
Bronze
 ↓
Silver
 ↓
Gold
 ↓
Power BI

Bronze
Raw data ingestion.

Silver
Data cleaning:
- duplicates
- NULL values
- data types
- invalid records
- standardization

Gold
Business tables:
- Daily Sales
- Customer Analytics
- Product Analytics
- Delivery Performance

Power BI
Interactive dashboard created from Gold data.
