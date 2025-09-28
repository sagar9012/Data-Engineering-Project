# Data-Engineering-Project

This project implements an end-to-end data engineering pipeline for analyzing the sentiment of news titles. The pipeline is built using Azure Data Services and demonstrates key concepts of data ingestion, transformation, incremental loading, and visualization.

The goal is to identify positive vs. negative sentiments in news titles and analyze their distribution across time (e.g., weekdays) using Power BI dashboards.

# Data Ingestion

    Raw news titles ingested from source (CSV/JSON/API) into Azure Data Lake.

# Data Transformation

    Cleaned and transformed using PySpark in Azure Databricks.
    
    Sentiment analysis applied (Positive, Negative, Neutral).

# Incremental Load

    Implemented incremental load logic to process only new/changed records.
    
    Loaded curated data into Azure SQL Database.

# Visualization (Power BI)

    Built interactive dashboards to analyze:
    
    Distribution of news titles by weekday.
    
    Positive vs Negative sentiment comparison.
    
    Overall sentiment trends over time.
