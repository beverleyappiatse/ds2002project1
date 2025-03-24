# ds2002project1

# Agriculture Data ETL Processor

This project processes fruit and vegetable price data from two different sources (CSV files and an API), performs necessary transformations, analyzes the data, and stores the results in an SQLite database.

## Project Overview

The ETL (Extract, Transform, Load) processor performs the following tasks:
1. **Extracts** data from two CSV files (`Fruit-Prices-2022.csv` and `Vegetable-Prices-2022.csv`) and an external API (USDA QuickStats).
2. **Transforms** the data by cleaning, merging, and summarizing it.
3. **Loads** the transformed data into an SQLite database for easy storage and retrieval.

## Features

- Loads and merges data from CSV files (`Fruit-Prices-2022.csv` and `Vegetable-Prices-2022.csv`) and an external API.
- Processes data to generate summaries such as the number of records and columns.
- Saves the processed data to an SQLite database.
- Visualizes the data using bar and scatter plots to show average prices and price vs. yield for fruits and vegetables.
- Implements error handling for failed data operations.
- Supports both CSV and JSON data formats.


## Setup & Usage

1. Upload Fruit-Prices-2022.csv and Vegetable-Prices-2022.csv to Google Colab.
2. Run the notebook to execute the ETL process.
3. The processed data will be stored in agriculture_data.db.

## Dependencies
This project requires the following Python libraries:

- pandas
- sqlite3
- requests

In Google Colab, these dependencies are pre-installed.

## Notes
- Ensure you have a valid USDA QuickStats API key before running the script.
- Error handling is implemented for missing files, API failures, and database operations.



Beverley Appiatse
