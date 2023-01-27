# crowdfunding_ETL
## ETL_Mini_Project

## Overview
In this mini project, I worked in a team to practice building an ETL pipeline using Python, Pandas, Python dictionary methods and regular expressions to extract and transform the data. After transforming the data, I created four CSV files and used the CSV file data to create an ERD and table schema. Finally, I uploaded the CSV file data into a PostgreSQL database. The mini project allowed me to collaborate and communicate with team members as we regularly checked on each other and offered support.
## Resources and Steps
### Create the Category and Subcategory DataFrames
##### Extract and transform the crowdfunding.xlsx Excel data to create a category DataFrame
##### Export the category DataFrame as category.csv and save it to your GitHub repository.
##### Export the category DataFrame as category.csv and save it on GitHub repository.
##### Export the subcategory DataFrame as subcategory.csv and save on GitHub repository.

### Create the Campaign DataFrame
##### Extract and transform the crowdfunding.xlsx Excel data to create a campaign DataFrame
##### Export the campaign DataFrame as campaign.csv and save it on GitHub repository

### Create the Contacts DataFrame
##### Choose one of the following two options for extracting and transforming the data from the contacts.xlsx Excel data:

##### Option 1: Use Python dictionary methods.
##### Option 2: Use regular expressions

If you chose Option 1, complete the following steps:
o	Import the contacts.xlsx file into a DataFrame.
o	Iterate through the DataFrame, converting each row to a dictionary.
o	Iterate through each dictionary, doing the following:
	Extract the dictionary values from the keys by using a Python list comprehension.
	Add the values for each row to a new list.
o	Create a new DataFrame that contains the extracted data.
o	Split each "name" column value into a first and last name, and place each in a new column.
o	Clean and export the DataFrame as contacts.csv and save it to your GitHub repository.
If you chose Option 2, complete the following steps:
o	Import the contacts.xlsx file into a DataFrame.
o	Extract the "contact_id", "name", and "email" columns by using regular expressions.
o	Create a new DataFrame with the extracted data.
o	Convert the "contact_id" column to the integer type.
o	Split each "name" column value into a first and a last name, and place each in a new column.
o	Clean and then export the DataFrame as contacts.csv and save it on GitHub repository.

### Create the Crowdfunding Database
o	Inspect the four CSV files, and then sketch an ERD of the tables by using QuickDBD 
o	Use the information from the ERD to create a table schema for each CSV file.
o	Save the database schema as a Postgres file named crowdfunding_db_schema.sql, and save it on GitHub repository.
o	Create a new Postgres database, named crowdfunding_db.
o	Using the database schema, create the tables in the correct order to handle the foreign keys.
o	Verify the table creation by running a SELECT statement for each table.
o	Import each CSV file into its corresponding SQL table.
o	Verify that each table has the correct data by running a SELECT statement for each.

