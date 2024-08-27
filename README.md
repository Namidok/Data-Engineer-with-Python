# Data-Engineer-with-Python
This project demonstrates how to efficiently read and clean CSV data using Pandas, transforming it to meet specific data model requirements. It then showcases the use of the psycopg2 module to create and manage a PostgreSQL database, including inserting the cleaned data into the database for further use.

# Requirements
1. Jupyter Notebook (I prefer using Anaconda because it almost has all Python modules built in it)
2. Python version 3(or anything above)
3. PostgreSQL
4. pgAdmin4 or Dbeaver CE to have a look a Databases in a detailed manner


Setup and Imports:

Install required libraries.
Import pandas and psycopg2.
Read and Clean Data:

Read the CSV file using pandas.
Clean the data (handle missing values, correct data types, filter data).
Create and Connect to the PostgreSQL Database:

Establish a connection to PostgreSQL using psycopg2.
Create a database and table if they do not exist.
Insert Data into PostgreSQL:

Prepare the SQL insert query.
Insert the cleaned data into the database.
Close the Connection:

Close the database cursor and connection.
Verify the Data:

Use pgAdmin4 or DBeaver CE to check and verify the data in the database.
