# Snowflake Data Model Project

## Files

- `DDL(DataDefinitionLanguage).sql`: SQL script for creating the schema and tables in the Snowflake data warehouse.
- `DML(DataManipulationLanguage).sql`: SQL script for the ETL process to transform the data from the original tables to the target tables in the data model.

## Usage

1. Load the Sakila dataset into Snowflake data warehouse using the `DDL(DataDefinitionLanguage).sql` script.
2. Run the ETL process using the `DML(DataManipulationLanguage).sql` script to transform the data from the original tables to the target tables in the data model.
3. Query the data model using SQL statements to retrieve the information needed for the business requirements.
---

## Project Description
This project is about creating a data model for the Sakila database of an online DVD store, to meet the following business requirements:

1. List the total revenue of each store everyday.
2. List the total revenue of totally everyday.
3. List the top store according to their weekly revenue every week.
4. List top sales clerk who have the most sales each day/week/month.
5. Which film is the top film each week/month in each store/totally?
6. Who are our top 10 customers each month/year?
7. Is there any store the sales is in a decline trend (within the recent 4 weeks the avg sales of each week is declining)

## Project Steps

1. Load original data: Load the Sakila dataset into Snowflake data warehouse using a script.
2. Analyze the business requirements and translate them into technical requirements.
3. Consider the grain of the data model and the atomic row of a fact table.
4. Decide what dimension tables to use in the data model and what columns to include in those dimensions.
5. Define the fact table and determine what columns to include.
6. Create the dimension and fact tables in Snowflake data warehouse, making sure the data model is in a different schema.
7. Write ETL script to transform data from the original tables to the target tables in the data model.



