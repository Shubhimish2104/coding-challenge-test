# coding-challenge-test
Tools used - excel , jupyter or google colab , apache airflow , apache superset , postgres server 
Cleaned csv using python 
Uploaded the csv on my superset postgresdb (only 100 records)
Loaded data on my public record and then made a dag to load data into the table
For postgresql I have used apache superset and queried all the questions
Used apache airflow for aggregration 
For aggregation -
Dag-
cron job for 24 hr 
Created temp table in my dag 
Checked the existence of the table
Called procedure with task id 
Delete the temp table 
Procedure-
Used plsql to create procedure 
Table -
Create the table with schema used in procedure 
For dashboard used apache superset with week , priority and category as the filter

