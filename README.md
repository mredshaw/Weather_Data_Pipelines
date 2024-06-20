# Weather Data Pipelines

## Project Overview
This project involves creating three data pipelines to optimize delivery routes using distance and weather data. The pipelines will pull data from various weather APIs, process it, and store it in a PostgreSQL database. The data pipelines are designed to be scheduled to run daily, updating the database with current and forecasted weather data.

## Objectives
1. Identify an API that provides historical weather data, current weather, weather forecasts, and weather alerts.
2. Create an uploads schema in your own database within the PostgreSQL server.
3. Prepare a data ingestion pipeline for each data source, designed to be scheduled and updated daily.
4. Include data cleaning and feature engineering in each pipeline.
5. Create new tables in the uploads schema to capture the weather data.

## Data Sources
- **Historical Weather Data**
- **Current Weather**
- **Weather Forecasts**
- **Weather Alerts:** Data available at [https://dd.weather.gc.ca/](https://dd.weather.gc.ca/)

## Contents
- `Weather_Data_Pipelines.ipynb`: Jupyter Notebook containing the entire data pipeline process, including API integration, data ingestion, cleaning, feature engineering, and storing data in PostgreSQL.
- `README.md`: This file, containing project details and instructions.

## Tools and Libraries Used
- Python
- Pandas
- NumPy
- Requests
- PostgreSQL
- SQLAlchemy

## How to Run
1. Ensure you have access to the PostgreSQL server.
2. Clone this repository: `git clone https://github.com/mredshaw/Weather_Data_Pipelines.git`
3. Open the Jupyter Notebook: `Weather_Data_Pipelines.ipynb`
4. Execute the cells in the notebook to set up the data pipelines and create the necessary tables in the PostgreSQL database.

## Key Insights
This project provides a comprehensive solution to optimizing delivery routes using weather data. By automating the data ingestion process and ensuring daily updates, it enables efficient and effective decision-making based on the latest weather information.
