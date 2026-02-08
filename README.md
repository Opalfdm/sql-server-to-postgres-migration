# Preface

This project is about migrating enterprise data from SQL Server into PostgreSQL

We'll be using

- SQL
- Python
- Jupyter Notebook


# Pseudocode

## High-level

1. Audit the data in SQL Server (before migration)
2. Extract data from SQL Server (SSMS)
3. Transform the data
4. Load the data into PostgreSQL
5. Validate the data (after migration)
6. Generate a validation report

## Low-level

1. Create a .env file
2. Load env variables 
3. Connect to SQL Server (pyodbc)
4. Connect to PostgreSQL (pyscopg2-binary)
5. Audit the data 
6. For each table (get row count, extract all rows)