# MLB SQL Analysis

This project presents a structured analysis of Major League Baseball (MLB) data using SQL. The analysis is performed on multiple tables containing player, school, and salary information, and is divided into four key areas: school analysis, salary trends, player career progression, and attribute comparisons.

---

## Project Structure

The SQL script is organized into four main parts:

### Part I: School Analysis
Analyze the educational background of MLB players:
- Count of schools producing MLB players per decade
- Top schools overall and by decade
- School data enrichment via `school_details`

### Part II: Salary Analysis
Explore salary trends and team-level spending:
- Top 20% highest-spending teams
- Cumulative salary spending over time
- Teams crossing the $1 billion mark

### Part III: Player Career Analysis
Understand individual player trajectories:
- Starting and ending ages and career length
- First and last teams played for
- Players loyal to a single team for over 10 years

### Part IV: Player Comparison Analysis
Compare player attributes and behaviors:
- Players sharing birthdays
- Batting style distribution by team
- Decade-over-decade changes in debut height and weight

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

---

