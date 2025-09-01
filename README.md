# New-public
This repository contains datasets related to the Olympics, including teams, medals, athletes, and coaches. The project demonstrates an end-to-end data pipeline, analysis, and visualization.

🏅 Olympics Mini-Warehouse – End-to-End Data Engineering Project
📌 Project Overview

This project demonstrates an end-to-end data engineering pipeline built on Azure Cloud using the Lakehouse & Medallion Architecture (Bronze → Silver → Gold).
The pipeline ingests Olympic datasets, processes them through multiple transformation layers, and visualizes insights using Power BI.

⚙️ Tech Stack

GitHub → Source of Olympic datasets

Azure Data Factory (ADF) → Data ingestion & orchestration

Azure Data Lake Storage Gen2 → Data storage (Bronze/Silver/Gold layers)

Azure Databricks → Data cleaning, transformation, and aggregation

Delta Lake → Optimized storage format for processed data

Power BI → Reporting & visualization

📂 Datasets

athletes.csv – Athlete details

coaches.csv – Coach details

teams.csv – Team details

medals.csv – Medal information

🏛 Medallion Architecture Workflow

Bronze Layer → Raw CSV data ingested from GitHub into Data Lake

Silver Layer → Cleaned & standardized data (missing values handled, types corrected, joins performed)

Gold Layer → Aggregated reporting tables (e.g., medal counts per country, medal distribution)

📊 Dashboard Highlights (Power BI)

Bar Chart → Top 10 countries by total medal count

Donut Chart → Medal distribution (Gold, Silver, Bronze)

Table → Medal count per country

📄 Project Report

The full detailed documentation of this project is available in the file:
Olympics project.docx (included in this repository).

🚀 How to Use

Clone this repository:

git clone https://github.com/MrAnirudh05/New-public


Explore datasets in CSV format.

Open the project report (Olympics project.docx) for detailed explanation.

✨ This project showcases my skills in Azure Data Engineering, Databricks, Delta Lake, and Power BI reporting using real-world architecture principles.
