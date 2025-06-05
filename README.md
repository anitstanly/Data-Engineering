# Data-Engineering
# 🌍 Automated City, Weather, and Flight Data Collection

This project automates the process of collecting, storing, and analyzing real-world data using web scraping, APIs, Google Cloud Platform (GCP), and SQL. It integrates multiple data sources to create a reliable and scalable data pipeline.

## 📌 Project Overview

- **Objective**: To collect and automate the processing of city demographics, current weather conditions, and flight status data for analysis and reporting.
- **Tech Stack**:
  - Python (requests, BeautifulSoup, Pandas)
  - APIs (weather and flight data)
  - Web Scraping (city data)
  - Google Cloud Platform (BigQuery, Cloud Storage)
  - SQL (data querying and transformation)

## 🔧 Features

### 1. 🏙️ City Data Collection
- Extracted relevant information about cities (e.g., population, region) using web scraping.
- Parsed and cleaned raw HTML data using BeautifulSoup and Pandas.

### 2. 🌦️ Weather Data via API
- Integrated with a public weather API to fetch real-time weather data (e.g., temperature, humidity, conditions).
- Automated the collection using scheduled scripts.

### 3. ✈️ Flight Data via API
- Used a flight tracking API to retrieve flight schedules, statuses, and delays.
- Merged flight data with weather conditions for analysis.

### 4. ☁️ Automation with GCP
- Stored raw and processed data in Google Cloud Storage.
- Loaded data into Google BigQuery for efficient querying and analysis.
- Scheduled regular ETL jobs to maintain up-to-date data.

### 5. 🗃️ SQL for Data Transformation
- Wrote complex SQL queries to transform, filter, and join data.
- Created analytical views for reporting and visualization.

## 📊 Use Cases
- Analyze the impact of weather on flight delays.
- Visualize city-specific travel trends.
- Build predictive models using clean, structured data.

## 📁 Project Structure
