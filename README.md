# ETL Pipeline Project: Fetch and Store Amazon Book Data on PostgreSQL

This project implements an **ETL (Extract, Transform, Load)** pipeline using **Apache Airflow** to fetch book data from Amazon, clean it, and store it in a PostgreSQL database. The pipeline leverages **PythonOperator** and **PostgresOperator** to manage the workflow.

## Features
- **Data Extraction**: Scrapes Amazon for data engineering books.
- **Data Transformation**: Cleans and formats the fetched data to remove duplicates.
- **Data Loading**: Creates a PostgreSQL table (if it doesn’t exist) and inserts the cleaned data.
