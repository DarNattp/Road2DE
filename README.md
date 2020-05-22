# Online Road to Data Engineer Workshop

[![overview.jpg](https://i.postimg.cc/vDFc0mtr/overview.jpg)](https://postimg.cc/jncx5t92)

## Workshop 1 - Data Colection with Python
### Overview: Extract transaction data from MySQL and conversion rate (pound to baht) from REST API. Then save it into CSV file (dataset)
Step 1: Install pymysql >> ! pip install pymysql;  
step 2: Config DB credential to access configuration to database.  
step 3: Connect to DB >> import pymysql.cursors and connect to the datdabase.  
step 4: Query Table by using with statement instead cursor.close().  
step 5: Convert to Pandas >> "import pandas as pd" and process along notebook.  
step 6: Get data from REST API >> "import requests" to get conversion rate table as string type.  
step 7: Load String type to dict type >> json.loads("table.text").And convert to pandas.  
step 8: Backup invoice time stamp, then processing datt time of both table for merge.  
step 9: Merge both by left join.  
step10: Create column "THBPrice" by multiply column "UnitPrice" and "Rate" any rows.  
step11: Save file to CSV.  

## Workshop 2 - Data Cleansing with Spark
### Overview: Cleansing data with PySpark, SparkSQL and Pandas.

## Workshop 3 - Upload into Data Lake
### Overview: Upload file into data lake on Google Cloud Storage.

## Workshop 4 - Automated Data Pipeline with Airflow
### Overview: Automated data pipeline with Airflow on Cloud Composer.
step 1: Install python packages in Composer >> pymysql, requests, pandas.  
step 2: Create pipeline.  

## Workshop 5 - Building a Big Data Warehouse with BigQuery
### Overview: Building data warehouse on Google BigQuery.

## Workshop 6 - Data Visualisation
### Overview: Using Google Data Studio to created dashboard for presentation the information.
[Complete Dashboard](https://datastudio.google.com/u/0/reporting/f80a0de9-3103-4b78-9a0f-9d1c03294cd6/page/rY7FB)