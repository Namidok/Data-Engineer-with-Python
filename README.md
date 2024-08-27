# Data-Engineer-with-Python
This project demonstrates how to efficiently read and clean CSV data using Pandas, transforming it to meet specific data model requirements. It then showcases the use of the psycopg2 module to create and manage a PostgreSQL database, including inserting the cleaned data into the database for further use.

# Requirements
1. Jupyter Notebook (I prefer using Anaconda because it almost has all Python modules built in it)
2. Python version 3(or anything above)
3. PostgreSQL
4. pgAdmin4 or Dbeaver CE to have a look a Databases in a detailed manner


# Setup and Imports
1.Install required libraries.
2.Import pandas and psycopg2.
3.Read and Clean Data:
4.Read the CSV file using pandas.
5.Clean the data (handle missing values, correct data types, filter data).
6.Create and Connect to the PostgreSQL Database
7.Establish a connection to PostgreSQL using psycopg2.
8.Create a database and table if they do not exist.
9.Insert Data into PostgreSQL
10.Prepare the SQL insert query.
11.Insert the cleaned data into the database.
12.Close the Connection

Close the database cursor and connection.
Verify the Data:

Use pgAdmin4 or DBeaver CE to check and verify the data in the database.
