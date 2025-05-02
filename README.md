# 📊 Weather Impact Analysis on Sales — End-to-End Data Pipeline

Client: A globally operating food truck company

As part of a data engineering initiative, I was tasked with investigating an unexpected anomaly: sales in Hamburg, Germany dropped to $0 for several days in February. After consulting with data analysts, we suspected weather might be a contributing factor.

To support the analysis and provide real-time weather insights, I built a complete end-to-end data pipeline that integrates sales and weather data, performs analytical transformations, and delivers live visualizations.

## 🔍 Objective

- Investigate the reason behind the drop in Hamburg sales

- Provide analysts with continuous access to real-time weather insights for Hamburg

- Build a scalable data solution that enables ongoing monitoring and analysis

## 🛠️ Pipeline Breakdown

Ingestion

✅ Load live weather data from Snowflake Marketplace

✅ Load sales data from the client’s AWS S3 bucket

Transformation

🧠 Use SQL for data transformations within Snowflake

📐 Create views optimized for analytical queries

🧮 Build User-Defined Functions (UDFs) for weather-based enrichment calculations

Delivery

📈 Develop and deploy a Streamlit application within Snowflake (Python-based)

🌤️ Provide live graphs of Hamburg’s weather and link to sales performance

📊 Ensure insights are accessible and interactive for analysts

This project demonstrates my ability to deliver a full-stack data solution—from ingestion to visualization—leveraging modern cloud tools like Snowflake, AWS, and Streamlit.
