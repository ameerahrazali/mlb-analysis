# MLB SQL Analysis

This project presents a structured analysis of Major League Baseball (MLB) data using SQL and visualized through Tableau dashboards. The analysis spans player statistics, school affiliations, and team salary trends, offering multi-perspective insights into the MLB landscape.

---

## Project Structure

The SQL and dashboard components are organized into four key areas:

| Part | Topic | Key Analyses |
|------|-------|--------------|
| **I** | School Analysis | • Join `schools` + `school_details`<br>• Count schools by decade<br>• Top 5 schools overall<br>• Top 3 schools per decade |
| **II** | Salary Analysis | • View salary data<br>• Top 20% teams by average spend<br>• Cumulative salary over years<br>• Year teams surpassed $1B |
| **III** | Player Career Analysis | • Age at debut and final game<br>• Career length in years<br>• Start and end teams<br>• 10+ years on same team |
| **IV** | Player Comparison Analysis | • Players with shared birthdays<br>• Batting style breakdown by team<br>• Debut height/weight by decade<br>• Decade-over-decade differences |

---

## Files Included

- [`final_project.sql`](final_project.sql): Main SQL script containing all structured queries and insights.
- `assets/` folder:
  - `MLB_Salary.gif`: Animated preview of the salary dashboard.
  - `MLB_Players.gif`: Animated preview of the player analysis dashboard.
  - `MLB_School.gif`: Animated preview of the school-level dashboard.
  - [`Major League Baseball Analysis.twb`](assets/Major%20League%20Baseball%20Analysis.twb): Tableau Workbook file containing all dashboards.

> _Note: Tableau dashboards were created using Tableau Desktop and are not hosted on Tableau Public due to publishing limitations._

---

## Tableau Dashboard Themes

### 1. MLB Salary Landscape  
_Spending, Trends & Top Earners_

- Top 10 highest-paid players  
- KPI cards on salary spending  
- Salary trend by year and team  

![MLB Salary Dashboard](assets/MLB_Salary.gif)

---

### 2. MLB Player Careers  
_Debuts, Longevity & Profiles_

- Career spans across decades  
- Player debut patterns  
- KPI cards and highlight metrics  

![MLB Player Dashboard](assets/MLB_Players.gif)

---

### 3. MLB School Impact  
_School Contributions & Legacy_

- Player origins by school and state  
- Total salary by school  
- Career duration and performance funnels  

![MLB School Dashboard](assets/MLB_School.gif)

---

## Tools Used

- **MySQL** 
- **Tableau Desktop** (for dashboard creation)  
- **Maven Analytics MLB dataset**  
- SQL window functions, CTEs, aggregates  

---

## Key Skills Demonstrated

- Analytical SQL for real-world data exploration  
- Use of `ROW_NUMBER`, `NTILE`, `LAG`, and other advanced functions  
- Data summarization, blending, and transformation  
- Custom dashboard storytelling using Tableau  

---

## Getting Started

To explore or reproduce the analysis:

1. Import the database `maven_advanced_sql` into your SQL environment.  
2. Run the queries from `final_project.sql` step by step.  
3. Open `Major League Baseball Analysis.twb` in Tableau Desktop to view dashboards.  
4. Preview dashboards from the GIFs in the `assets` folder.  

---

## Acknowledgments

This project uses data from the Maven Analytics Advanced SQL course. It was created for educational and portfolio purposes.
