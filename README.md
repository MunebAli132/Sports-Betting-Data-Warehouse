# Sports Betting Data Warehouse

## Overview

This project is a data engineering case study for designing and implementing a **star schema data warehouse** based on sports betting data. The goal is to enable efficient analytics on:

- Betting patterns  
- Customer behavior  
- Sports performance  


## Raw Data

The raw data is organized into several CSV files:

- `raw_betting_activity.csv` – Records of individual bets placed.
- `raw_customers.csv` – Information about registered customers.
- `raw_matches.csv` – Details about sports matches.
- `raw_leagues.csv` – Metadata about sports leagues.
- `raw_sports.csv` – Information about the different types of sports.

## Objectives

- Design a **star schema** data warehouse.
- Build dimension and fact tables from raw data.
- Enable queries for business insights such as:
  - Most popular sports
  - Customer betting trends
  - Match and league performance
  - Revenue analysis

## Technologies

- Python / Pandas / SQL
- PostgreSQL / SQLite
- dbt (for modeling)
- Jupyter Notebooks (for exploration)

