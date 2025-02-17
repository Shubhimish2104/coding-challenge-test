# coding-challenge-test
Tools used - excel , jupyter or google colab , apache airflow , apache superset , postgres server .Cleaned csv using python , uploaded the csv on my superset postgresdb (only 100 records)
,loaded data on my public record and then made a dag to load data into the table .For postgresql I have used apache superset and queried all the question .Used apache airflow for aggregation ,Dag-cron job for 24 hr ,Created temp table in my dag , checked the existence of the table ,called procedure with task id , delete the temp table . Procedure-used plsql to create procedure . Table -Create the table with schema used in procedure .For dashboard used apache superset with week , priority and category as the filter

