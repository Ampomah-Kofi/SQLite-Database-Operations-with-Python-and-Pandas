# SQLite Database Operations with Python and Pandas

## Overview
This project demonstrates how to work with a SQLite database using Python and pandas.  
The script loads instructor data from a CSV file into a SQLite database, performs SQL queries, appends new records, and verifies database updates.

It reflects common database workflows used in data engineering and analytics tasks.

## Project Description
The script connects to a SQLite database, creates a table from a CSV file, executes multiple SQL queries, and appends new data to the existing table.  
All operations are handled using pandas and SQLite without external database servers.

## Data Source
Input data is read from a CSV file containing instructor records.

## Database Schema
Table name: `INSTRUCTOR`

Columns:
- ID  
- FNAME  
- LNAME  
- CITY  
- CCODE  

## Workflow

### Load Data
- Connect to a SQLite database  
- Read instructor data from a CSV file  
- Load the data into a SQLite table  
- Replace existing table data on initial load  

### Query Data
- Retrieve all records from the table  
- Retrieve only the first name column  
- Count the total number of records  

### Append Data
- Create a new instructor record  
- Append the record to the existing table  
- Re run the row count query to confirm insertion  

### Close Connection
- Safely close the SQLite database connection  

## Technologies Used
- Python  
- Pandas  
- SQLite  

## Files Used
- `INSTRUCTOR.csv` – Source data  
- `STAFF.db` – SQLite database  
- `INSTRUCTOR` – Database table  

## How to Run
1. Ensure the CSV file path is correct  
2. Install required Python libraries  
3. Run the Python script  
4. Review printed query results  

## Skills Demonstrated
- SQLite database creation and management  
- CSV to database loading  
- SQL querying with pandas  
- Data insertion and validation  
- End to end database workflow in Python  

## Why This Project Matters
This project mirrors real world analytics and ETL database tasks.  
It shows how to move data from flat files into relational storage and interact with it using SQL and Python.
