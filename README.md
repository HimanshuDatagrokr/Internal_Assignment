# Internal Assignment

## Task: Fetching Data from JSON Files and Storing in SQL Database

### Overview
The objective of this assignment is to write a Python script that fetches data from JSON files and stores it in an SQL database using Pandas and Psycopg2.

### SECTION 1
1. Ensure that Python, Pandas, and Psycopg2 are installed in your environment.
2. Write a Python script to fetch data from JSON files and store it in an SQL database.
   - Import the necessary libraries.
   - Read the JSON files using Pandas.
   - Connect to the PostgreSQL database using Psycopg2.
   - Write the data to an SQL table.
   - Close the database connection.
3. Adjust the file names, database connection parameters, and table names based on your specific requirements.

### SECTION 2
Write a python code to create dimension tables from above created fact table,  

  1. dim_batters: contains name , match_number, team, played_against_team ,total_runs_scored  
  2. Dim_bowlers: name, match_number, team, played_against_team , no_of_bowls, runs_conceeded, extras, wickets, maiden_overs 
  3. Dim_co_ordinators: umpires, commentors, match location ,match_number, toss 
