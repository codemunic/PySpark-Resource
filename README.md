# PySpark-Resource
Pyspark resources and codes

## Create Table in Databricks using the CSV File

CREATE TABLE IF NOT EXISTS table_name
USING CSV
OPTIONS (path 'directory/file.csv', header 'true' inferSchema 'true');

CREATE TABLE IF NOT EXISTS table_name(
column_name1 string,
column_name2 int )
USING CSV
OPTIONS (path 'directory/file.csv', header 'true');
