End-to-End Big Data Pipeline + ML Model + Cloud Integration

📖 Overview

This project builds a scalable big data pipeline to analyze and predict Air Quality Index (AQI) using:

Weather Data (Open-Meteo API)
Air Quality Data (Open-Meteo API)
Azure Databricks
CosmosDB (MongoDB API)
PySpark
XGBoost ML Model

📊 Dataset size: ~600,000 records across 25 Indian cities

⚙️ Tech Stack
Python, Pandas
PySpark (Big Data Processing)
Azure Databricks
MongoDB (CosmosDB)
XGBoost
Plotly / Matplotlib

🔄 Pipeline Architecture
API Data Collection
Data Cleaning & Transformation
Storage in CosmosDB
Exploratory Data Analysis
Machine Learning Model

📊 Key Insights
✔ AQI peaks between 1 PM – 2 PM
✔ Worst AQI in Winter (Nov–Jan)
✔ Best AQI in Monsoon (Jun–Aug)
✔ Cities like Delhi show highest pollution levels

🤖 Model Performance
Dataset	RMSE	R² Score
Train	18.23	0.88
Validation	21.63	0.83
Test	21.72	0.82

✔ Hyperparameter tuning improved performance significantly

How to Run
pip install -r requirements.txt

📌 Future Improvements
Real-time AQI prediction API
Dashboard using Streamlit
Deployment on Azure

