# MLB SQL Analysis

This project presents a structured analysis of Major League Baseball (MLB) data using SQL. The analysis is performed on multiple tables containing player, school, and salary information, and is divided into four key areas: school analysis, salary trends, player career progression, and attribute comparisons.

---

## Project Structure

The SQL script is organized into four main parts:

| Part | Topic | Key Analyses |
|------|-------|--------------|
| **I** | School Analysis | • Join `schools` + `school_details`<br>• Count schools by decade<br>• Top 5 schools overall<br>• Top 3 schools per decade |
| **II** | Salary Analysis | • View salary data<br>• Top 20% teams by average spend<br>• Cumulative salary over years<br>• Year teams surpassed $1B |
| **III** | Player Career Analysis | • Age at debut and final game<br>• Career length in years<br>• Start and end teams<br>• 10+ years on same team |
| **IV** | Player Comparison Analysis | • Players with shared birthdays<br>• Batting style breakdown by team<br>• Debut height/weight by decade<br>• Decade-over-decade differences |

---

## File

- [`mlb_analysis.sql`](final_project.sql): Main SQL script containing all structured queries and analysis.

---

## Tools Used

- MySQL (or compatible SQL engine)
- Maven Analytics MLB dataset
- SQL window functions, CTEs, joins, and aggregates

---

## Key Skills Demonstrated

- Analytical SQL for real-world data exploration
- Use of CTEs and window functions (`ROW_NUMBER`, `NTILE`, `LAG`)
- Data summarization and pivot-style aggregation
- Decade-based time series analysis

---

## Getting Started

To run the analysis:

1. Import the database `maven_advanced_sql` into your SQL environment.
2. Open and execute the queries in `mlb_analysis.sql` step by step.
3. Explore and extend each section based on your analytical needs.

---

## Acknowledgments

This project uses data from the Maven Analytics Advanced SQL course. It was created for educational and portfolio purposes.

