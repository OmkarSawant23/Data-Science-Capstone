# Dash App

This folder contains the Plotly Dash application developed for the SpaceX Data Science Capstone project.

## Application File

| File | Description |
|---|---|
| `spacex-dash-app.py` | A Plotly Dash web application that provides interactive visual analytics for SpaceX Falcon 9 launches. |

## Dashboard Features

The dashboard includes:

- A launch site dropdown menu to filter results by launch site
- A pie chart showing successful and failed launches
- A payload range slider to filter launches by payload mass
- A scatter plot showing the relationship between payload mass and launch success
- Booster version color grouping for visual comparison

## Purpose

The dashboard allows users to interactively explore SpaceX launch data and answer key business and analytical questions, such as:

1. Which launch site has the largest number of successful launches?
2. Which launch site has the highest success rate?
3. Which payload ranges are associated with higher launch success?
4. Which payload ranges are associated with lower launch success?
5. Which Falcon 9 booster version has the highest success rate?

## How to Run

Install the required packages:

```bash
python3.11 -m pip install pandas dash
