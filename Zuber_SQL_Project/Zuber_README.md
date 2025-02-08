# Project Title: Zuber SQL Project

[<img src="https://github.com/nbrown5071/Data_projects_TripleTen/blob/main/Zuber_SQL_Project/Zuber%20Relationship%20Table.png" alt="Zuber_Relationship_Table">](https://github.com/nbrown5071/Data_projects_TripleTen/blob/main/Zuber_SQL_Project/Zuber%20Relationship%20Table.png)

### Zuber SQL Project Table of Contents
| File Number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | [Zuber Relationship Table](https://github.com/nbrown5071/Data_projects_TripleTen/blob/main/Zuber_SQL_Project/Zuber%20Relationship%20Table.png) | A .png image file of the relationships between tables for Zuber | 
| 2 | [Zuber SQL Project Description](https://github.com/nbrown5071/Data_projects_TripleTen/blob/main/Zuber_SQL_Project/Zuber%20SQL%20Project%20Description.pdf) | A .pdf file containing the data dictionary, relationship table, and brief project description. | 
| 3 | [Zuber SQL Project Task Answers](https://github.com/nbrown5071/Data_projects_TripleTen/blob/main/Zuber_SQL_Project/Zuber%20SQL%20Project%20Task%20Answers.txt) | A .txt file containing SQL code answers for the project questions | 
| 4 | [Zuber SQL Project Tasks](https://github.com/nbrown5071/Data_projects_TripleTen/blob/main/Zuber_SQL_Project/Zuber%20SQL%20Project%20Tasks.pdf) | A .pdf file containing the questions/ tasks for the project | 
| 5 | [Zuber_README](https://github.com/nbrown5071/Data_projects_TripleTen/blob/main/Zuber_SQL_Project/Zuber_README.md) | Current View, Contains relevant information about the project | 


| Section Title | Description |
| ----------- |----------- |
| Project Description | Details the projects intended purpose and describes requirements. |
| About the Data | Describes the data used in the project. |
| Process | Briefly describes methodology. |
| Reflection | Challenges, Improvements, what I learned, etc. | 

### Project Description 
Zuber is a fictional, new ride-sharing company that's launching in Chicago. We were tasked to find patterns in the available information in order to help Zuber understand passenger preferences and the impact of external factors on rides by completing six SQL query questions. This project was executed on the TripleTen SQL platform. Each question/ task was designed to test our advanced SQL skills; subqueries, joins, case statements, etc. In order to move to the next task, your query statement and query results had to perfectly match the TripleTen platform. 

### About the Data
This project was executed on the TripleTen SQL platform. No data was able to be downloaded. TripleTen provided a [data dictionary and relationship table](https://github.com/nbrown5071/Data_projects_TripleTen/blob/main/Zuber_SQL_Project/Zuber%20SQL%20Project%20Description.pdf). 
The Zuber Database consisted of the following:
- Four tables: trips, cabs, weather_records, & neighborhoods


### Process
Even though this project was more of a test of skills vs. analysis with findings, I still performed exploratory analysis. First, I reviewed the data dictionary and relationship table. Next, I ran some test queries to identify tables that may need to be manipulated. For example, start_ts and end_ts are formatted as "time" but they both contain "date" data. This means I might need to perform a "cast" function in a query in order to get the desired results.


### Reflection
SQL will always test your ability to break down and translate a question into SQL language. I found most of the tasks for this project to be farely straight forward except for task 3. At first, I kept trying to use a subquery to get the desired results. Then, I realized I needed to use a case statement because the task is asking you to breakdown rides between two cab companies.


