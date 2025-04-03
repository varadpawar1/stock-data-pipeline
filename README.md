# stock-data-pipeline
End-to-end stock market data pipeline using AWS S3, Snowflake, and PySpark
# Stock Market Data Pipeline

This project demonstrates an end-to-end data engineering pipeline using AWS S3, Snowflake, and PySpark to ingest, process, and analyze historical stock market data (S&P 500).
git 
## 📦 Tools & Technologies
- AWS S3 – Data storage
- Snowflake – Cloud data warehouse
- PySpark – Data processing
- Git & GitHub – Version control
- Power BI (optional) – Visualization

## 📁 Folder Structure
- `data/`: raw datasets (CSV)
- `scripts/`: PySpark processing scripts
- `notebooks/`: analysis notebooks
- `sql/`: Snowflake DDL and queries
- `docs/`: diagrams, setup instructions

## 🔧 Setup
1. Upload data to AWS S3
2. Create Snowflake database, stage, and table
3. Run `COPY INTO` to load data
4. Process with PySpark (optional)
