#  E-Commerce Orders Data Pipeline with PySpark

A PySpark-based big data project that simulates a real-world data engineering workflow. This project reads raw e-commerce data, transforms it, and writes aggregated insights to Parquet.

## 📁 Files
- `ecommerce_pipeline.py`: Main script
- `data/`: Contains orders, customers, products CSV files
- `output/`: Parquet results for revenue and top customers

## 🛠 Features
- Joins multiple datasets
- Revenue calculations
- Top N customers
- Category-level analytics
- Output written in partitioned Parquet format

## 🔧 Technologies
- PySpark
- Pandas (for dummy data)
- CSV, Parquet

## 📊 Output Includes
- Revenue per product
- Revenue per category
- Top 5 customers by revenue
