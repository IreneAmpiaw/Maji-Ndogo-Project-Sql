# Maji Ndogo Project: SQL Data Analysis for Water Crisis

This project analyzes the water crisis in the fictional country of Maji Ndogo using SQL and Jupyter Notebooks. The analysis is based on a comprehensive database containing information about water sources, employee activities, locations, and survey visits. The goal is to uncover insights and propose data-driven solutions to improve water access and infrastructure.

## Project Overview

The project is divided into two main parts:

1. **Data Exploration and Cleaning**: Initial exploration of the database, cleaning and updating key fields (such as employee emails and phone numbers), and understanding the structure of the data.
2. **Analytical Deep Dive**: Advanced SQL analysis using window functions and aggregations to:
   - Summarize water source types and usage
   - Rank and prioritize infrastructure repairs
   - Analyze queue times for water collection
   - Identify trends and provide actionable insights

## Key Features

- **Database Connection**: Connects to a MySQL database using Jupyter Notebook magic commands and PyMySQL.
- **Data Cleaning**: Updates employee emails and phone numbers for consistency and future communication.
- **Exploratory Queries**: Examines tables such as `employee`, `visits`, `location`, and `water_source` to understand the data landscape.
- **Aggregations and Window Functions**: Uses SQL queries to rank water sources, calculate averages, and identify high-priority repairs.
- **Queue Analysis**: Investigates queue times by day and hour to highlight peak demand periods.
- **Actionable Insights**: Provides recommendations for infrastructure improvements based on data analysis.

## How to Use

1. Open the provided Jupyter Notebooks (`Maji_Ndogo_project_sql_1.ipynb` and `Maji_Ndogo_project_sql_2.ipynb`).
2. Ensure you have access to the required MySQL database and update connection credentials as needed.
3. Run the cells sequentially to:
   - Connect to the database
   - Explore and clean the data
   - Perform advanced analysis and view insights

## Notebooks

- **Maji_Ndogo_project_sql_1.ipynb**: Initial data exploration and cleaning (see notebook for details).
- **Maji_Ndogo_project_sql_2.ipynb**: In-depth analysis, including clustering, ranking, and queue time analysis.

## Requirements

- Python (Jupyter Notebook environment)
- MySQL database (with the Maji Ndogo dataset)
- Required Python packages: `pymysql`, `ipython-sql`

## Insights and Outcomes

The analysis provides a clear picture of the water crisis in Maji Ndogo, highlighting:
- The distribution and usage of water sources
- Key bottlenecks such as long queue times for shared taps
- Priority areas for infrastructure repair and investment

These insights can guide decision-makers in targeting interventions that will have the greatest impact on the population's access to clean water.
