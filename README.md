# Weather Data Pipeline for Hamburg Sales Insights

Client: A globally operating food truck company

As part of a data engineering initiative, I was tasked with investigating an unexpected anomaly: sales in Hamburg, Germany dropped to $0 for several days in February. After consulting with data analysts, we suspected weather might be a contributing factor.

To support the analysis and provide real-time weather insights, I built a complete end-to-end data pipeline that integrates sales and weather data, performs analytical transformations, and delivers live visualizations.

## 🔍 Objective

- Investigate the reason behind the drop in Hamburg sales

- Provide analysts with continuous access to real-time weather insights for Hamburg

- Build a scalable data solution that enables ongoing monitoring and analysis


## 🧰 Tech Stack
- Snowflake – Cloud data warehouse for data storage, transformation, and hosting the Streamlit app
- AWS S3 – Source for ingesting raw sales data (CSV files)
- Snowflake Marketplace – Source of live weather data
- SQL – Used for data transformation, view creation, and UDF logic
- Python – Used to build the Streamlit front-end application
- Streamlit (in Snowflake) – Interactive UI for submitting smoothie orders and visualizing data



## 📁 Project Structure

```
Weather-Data-Pipeline-for-Hamburg-Sales-Insights/
│
├── 00_ingestion/solution/
│     ├── copy_into.sql       
│     └── load_tasty_bytes.sql
│
├── 01_transformation/
│     ├── hamburg_sales.sql
│     ├── udf.sql
│     └── updated_hamburg_sales.sql
│ 
├── 02_delivery/
│     └── streamlit.py   
│ 
├── LICENSE
│    
└── README.md
```



## 🛠️ Pipeline Breakdown

### Ingestion

✅ Load live weather data from Snowflake Marketplace

✅ Load sales data from the client’s AWS S3 bucket

### Transformation

🧠 Use SQL for data transformations within Snowflake

📐 Create views optimized for analytical queries

🧮 Build User-Defined Functions (UDFs) for weather-based enrichment calculations

### Delivery

📈 Develop and deploy a Streamlit application within Snowflake (Python-based)

🌤️ Provide live graphs of Hamburg’s weather and link to sales performance

📊 Ensure insights are accessible and interactive for analysts

This project demonstrates my ability to deliver a full-stack data solution from ingestion to visualisation leveraging modern cloud tools like Snowflake, AWS, and Streamlit.

![Screenshot 2025-05-02 at 21 06 01](https://github.com/user-attachments/assets/026bc1cc-3f11-4f48-8e7a-f7617487a7c0)
