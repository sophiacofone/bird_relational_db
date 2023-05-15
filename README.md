# Relational Databases using MySQL: Bird-strikes
This project involves building a database to analyze bird strikes on aircraft using an existing data set from the FAA. The main tasks include creating a logical data model and relational schema, implementing the schema in MySQL, loading the data from a CSV file into the database, executing SQL queries, performing analytics in R, and ensuring code runs efficiently without errors. The project also involves data cleaning tasks such as harmonizing data (flight phases), removing unnecessary data (military flights), and creating a stored procedure to add new incidents to the database. The final deliverables include the completed R Notebook with SQL code, query results, visualizations, and explanations of the code and decisions made throughout the project.

## Task Summary
1. Inspecting the data file and creating a new database schema.
2. Loading the data from the CSV file into the database tables.
3. Displaying parts of each table to verify the data loading.
4. Creating SQL queries to find the top-10 airlines with the most incidents, the flight phase with the above-average number of incidents, and the maximum number of incidents by month.
5. Building a column chart to visualize the number of incidents per year from 2005 to 2011.
6. Creating a stored procedure in MySQL to add a new incident to the database.

## Key skills/learnings
1. Installing and connecting to MySQL from R.
2. Designing a relational schema in at least 3NF (Third Normal Form) for an existing dataset.
3. Loading data from CSV files into a relational database through R.
4. Executing SQL queries against a MySQL database through R.
5. Performing analytics in R using SQL queries.
6. Identifying and resolving programming errors.
7. Creating visualizations using R to present data.
8. Creating and using stored procedures in MySQL.

## How to run
To run this notebook, you will need RMySQL and sqldf. You will also need to set up a MySQL called bird. Then, the notebook should run completely.
