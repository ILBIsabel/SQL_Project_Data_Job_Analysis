# Introduction
📊 Looking into the data job market. Focusing on data analyst roles, this project dives deep into the job market to investigate which roles offer the highest salaries, which skills are most in demand, and where those two intersect to highlight the most strategic paths for aspiring data analysts.

Check out the SQL queries here: [project_sql folder](/project_sql/) 
# Background
Motivated by the need to better understand and navigate the data analyst job landscape, this project set out to uncover the most valuable skills and the highest-paying roles. Streamlining others work to find optimal jobs.

**Note:** This project uses data from Luke Barousse's [SQL Course](https://lukebarousse.com/sql). Huge shout out to Luke for providing such a great open learning resource!

### Questions answered through my SQL queries:
1. What are the top-paying data analyst jobs?
2. What skills are required for these top-paying jobs?
3. What skills are most in demand for data analysts?
4. Which skills are associated with higher salaries?
5. What are the most optimal skills to learn?
# Tools Used

- **SQL:** For writing queries to explore and analyze the data.
- **PostgreSQL:** My chosen database management system to store and handle the job posting datasets.
- **Visual Studio Code:** My development environment where I wrote and tested my SQL queries.
- **Git & GitHub:** For version control and sharing my SQL scripts and analysis. This ensured collaboration and project tracking.
# The Analysis
Here’s how I approached each question:

### 1. Top Paying Data Analyst Jobs
To identify the top-paying roles, I filtered data analyst job postings by average yearly salary and location, focusing on remote jobs. 

[First Query](/project_sql/1_top_paying_jobs.sql)

Key findings of the top data analyst jobs in 2023:

- **Wide Salary Range:** Top 10 paying data analyst roles range from $184,000 to $650,000, highlighting significant salary potential in the field.
- **Diverse Top Employers:** Companies like SmartAsset, Meta, and AT&T are among those leading in compensation, showing a broad interest across different industries.
- **Job Title Variety:** Job titles vary, from Data Analyst to Director of Analytics, showcasing a range of opportunities and specializations within data analytics.

### 2. Skills for Top Paying Jobs
I joined the job postings with the skills data to discover what tools are needed for these high-paying roles. Providing insights into what employers value for high-compensation roles.

[Second Query](/project_sql/2_top_paying_job_skills.sql)

Key findings of the most demanded skills for the top 10 highest paying data analyst jobs in 2023:

- **SQL** is mentioned with a count of 8.
- **Python** follows closely with a count of 7.
- **Tableau** is also highly sought after, with a count of 6. Other honorable skills like R, Snowflake, Pandas, and Excel show varying degrees of demand.

### 3. In-Demand Skills for Data Analysts
Identify the skills most frequently requested in job postings, with a focus in areas with high demand.

[Third Query](/project_sql/3_top_demanded_skills.sql)

Key findings of the most demanded skills for data analysts in 2023:

- **SQL** and **Excel** remain fundamental, emphasizing the need for strong foundational skills in data processing and spreadsheet manipulation.
- **Programming** and **Visualization Tools** like **Python**, **Tableau**, and **Power BI** are essential, showing the importance of technical analysis in data storytelling and decision support.

### 4. Skills Based on Salary
Analyzed average salaries by skill to find which skills are the highest paying.

[Fourth Query](/project_sql/4_top_paying_skills.sql)

Key findings of the results for top paying skills for Data Analysts:

- **High Demand for Big Data & ML Skills:** Analysts proficient in big data platforms (PySpark, Couchbase), machine learning tools (DataRobot, Jupyter), and Python libraries (Pandas, NumPy), tend to earn the highest salaries—highlighting the industry's emphasis on advanced data processing and predictive analytics skills.
- **Software Development & Deployment Proficiency:** Knowledge in development and deployment tools (GitLab, Kubernetes, Airflow) shows the increasing intersection of data analysis and engineering. These skills are highly valued for their role in automation and managing robust data pipelines, contributing to higher pay.
- **Cloud Computing Expertise:** Familiarity with cloud and data engineering tools (Elasticsearch, Databricks, GCP) point to the shift toward cloud-based analytics environments, suggesting that cloud proficiency is becoming a major driver of increased compensation for data analytics professionals.

### 5. Most Optimal Skills to Learn
Combining insights from demand and salary data, this query pinpointed which skills are both in high demand and have high salaries.

[Fifth Query](/project_sql/5_optimal_skills.sql)

Key findings of the most optimal skills for Data Analysts in 2023:

- **High-Demand Programming Languages:** Python and R are among the most sought-after programming languages, with 236 and 148 mentions respectively. Despite their high demand, their average salaries are around $101,397 for Python and $100,499 for R, their widespread use suggests they are essential but commonly held skills in the field.
- **Cloud Tools and Technologies:** Expertise in specialized technologies such as Snowflake, Azure, AWS, and BigQuery is associated with strong demand and above-average pay. This reflects the increasing reliance on cloud platforms and big data solutions in modern data analysis workflows.
- **Business Intelligence and Visualization Tools:** Tableau and Looker, with demand counts of 230 and 49 respectively, and average salaries around $99,288 and $103,795, highlight the critical role of data visualization and business intelligence in deriving actionable insights from data.
- **Database Technologies:** The demand for skills in traditional and NoSQL databases (Oracle, SQL Server, NoSQL) with average salaries ranging from $97,786 to $104,534, reflects the need for data storage, retrieval, and management expertise.
# What I Learned
Throughout this journey, I significantly expanded my SQL skillset and sharpened my data analysis abilities:

- **Complex Query Crafting:** I gained confidence in constructing complex SQL queries, effectively using WITH clauses to create temporary tables and joining/merging data across multiple tables with precision.
- **Data Aggregation:** I got familiar with GROUP BY and turned aggregate functions like COUNT() and AVG() to extract meaningful summaries from raw data.
- **Analytical Wizardry:** I improved my ability to translate analytical questions into targeted, insightful SQL queries that yield actionable results.
# Conclusions
### Insights
From the analysis, many key insights emerged:

1. **Top-Paying Data Analyst Jobs:** The highest-paying remote data analyst jobs offer a wide salary range, with top positions reaching as high as $650,000!
2. **Skills for Top-Paying Jobs:** High-paying data analyst jobs require advanced proficiency in SQL, suggesting it’s a critical skill for earning a top salary.
3. **Most In-Demand Skills:** SQL is also the most demanded skill in the data analyst job market, thus making it an essential skill for anyone pursuing a career in data analysis.
4. **Skills with Higher Salaries:** Specialized skills, such as SVN and Solidity, are associated with the highest average salaries, suggesting that niche expertise is highly valued in the market
5. **Optimal Skills for Job Market Value:** SQL leads in demand and offers for a high average salary, making it one of the most optimal skills for data analysts to learn to maximize their market value.

### Final Thoughts
This project was more than a technical exercise, it was a deep dive into the data analyst job landscape. It strengthened my SQL skills and delivered valuable insights into what employers are really looking for. As the field of data analytics continues to evolve, staying adaptable and continuously upgrading one’s skillset is key. This analysis provides a clear roadmap for where to focus those efforts. Once again, huge thank you to Luke Barousse for the resources and support!
