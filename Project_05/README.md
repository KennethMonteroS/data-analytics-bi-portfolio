# Project 05 – Baseball Data Analysis (Advanced SQL)

## Overview
This project analyzes baseball data using advanced SQL techniques to explore player careers, team spending patterns, and school contributions.

The analysis focuses on extracting insights from relational data using joins, aggregations, CTEs, and window functions.

Data Source: Public baseball dataset.

---

## Objectives
- Analyze school contributions to professional players over time  
- Evaluate team spending patterns and top spenders  
- Examine player career length and progression  
- Identify trends in player attributes across decades  

---

## Database Structure
The analysis is based on the following main tables:

| Table | Description |
|------|-------------|
| players | Contains player information such as name, birth date, debut, final game, height, and weight. |
| salaries | Stores player salary data by team and year. |
| schools | Links players to the schools they attended. |
| school_details | Contains descriptive information about schools. |

---

## Key Analysis
- School production trends by decade  
- Top schools producing professional players  
- Top 20% highest-spending teams (`NTILE`)  
- Cumulative team spending over time  
- Player career length and team transitions  
- Batting distribution by team (pivot analysis)  
- Trends in height and weight using `LAG`  

---

## Key Insights
- A small number of schools consistently produce the most players  
- Team spending is highly concentrated among top teams  
- Career lengths vary significantly, with some exceeding a decade  
- Player physical attributes show gradual changes over time  

---

## Repository Structure
- [mlb_analysis.sql](mlb_analysis.sql) – SQL queries used for analysis
- `mlb_database_creation.sql` – Project documentation  

---

## Skills Demonstrated
- Advanced SQL  
- CTEs and Window Functions  
- Data Aggregation  
- Data Transformation  
- Analytical Thinking
