# Datasets

This folder contains the datasets used and generated throughout the IBM Data Science Capstone project.

## Contents

| Dataset | Description |
|---|---|
| `dataset_part_1.csv` | Dataset generated from the SpaceX API data collection notebook. It contains cleaned Falcon 9 launch records after filtering and preprocessing. |
| `spacex_web_scraped.csv` | Dataset generated through web scraping Falcon 9 launch records from Wikipedia. |
| `dataset_part_2.csv` | Cleaned and wrangled dataset containing Falcon 9 launch information, mission outcomes, and the binary landing success class. |
| `dataset_part_3.csv` | Processed feature dataset created after exploratory data analysis and one-hot encoding. This dataset is used for machine learning model training. |
| `spacex_launch_geo.csv` | Dataset containing SpaceX launch records with latitude and longitude values for launch site mapping and geospatial analysis. |
| `spacex_launch_dash.csv` | Dataset used to build the interactive Plotly Dash dashboard for visual analytics. |
| `my_data1.db` | SQLite database file used in the SQL analysis notebook. It stores the SpaceX dataset in database format so SQL queries can be performed for launch site, payload, booster, and mission outcome analysis. |

## Purpose

These datasets support different stages of the capstone workflow:

- API-based data collection
- Web scraping
- Data cleaning and wrangling
- SQL analysis
- Exploratory data visualization
- Geospatial mapping
- Interactive dashboard development
- Machine learning prediction

The processed datasets are used to analyze SpaceX Falcon 9 launches and predict the success of first-stage landings.
