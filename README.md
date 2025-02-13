# sales-data-pipeline-project

## Project Goal
The goal of this project is to build an automated data analytics pipeline to manage and visualize sales data across multiple regions (USA, UK, India) for a global retail business. The pipeline collects, processes, and visualizes raw sales data, providing insights for data-driven business decisions.

## Tools Used
- **Google Cloud Storage (GCS):** Stores uploaded CSV files.
- **Cloud Functions:** Triggered by file uploads to process data and load it into BigQuery.
- **BigQuery:** Data warehouse for storing and querying transformed sales data.
- **Looker Studio:** Used for creating interactive dashboards and visualizations.
- **Python (Flask):** Powers the web portal for CSV file uploads.
- **Kaggle Data:** Used as a sample dataset for testing.

## The Process
1. **Data Upload via Web Portal:** Shop managers upload CSV files via a Flask-based portal.
2. **Storage in GCS:** Uploaded files are stored in a GCS bucket.
3. **Triggering Cloud Functions:** Cloud Functions automatically trigger when files are uploaded, extracting and transforming the data.
4. **ETL (Extract, Transform, Load):** Data is processed and loaded into BigQuery.
5. **Data Analysis & Reporting:** Sales data is visualized in Looker Studio to track performance by region and provide insights for business decisions.

## Architecture
https://github.com/monikavaddineni/sales-data-pipeline-project/blob/ef754d34df8eef61c42e1874bd1cd1ffbff43d7d/salesetl.png

## Outcome
- **Automated pipeline** for collecting, transforming, and loading sales data.
- **Scalable solution** for handling large datasets (from 2000 to 100,000+ records).
- **Interactive dashboards** in Looker Studio provide actionable insights into regional sales performance.
- **Cost-effective** solution leveraging serverless Google Cloud services.

This project demonstrates a fully automated and scalable data pipeline, offering a streamlined approach to sales data management and real-time analytics for businesses.
