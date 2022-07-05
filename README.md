# PySpark-Hands-on
My Hands on exposure to pyspark

# Dataset 
    The dataset we are going to use is the global terrorism dataset. We are going to use transformations on it and try to clean it up for visualization.
    The dataset is going to reside inside /data folder in the project folder. 

## Spark Managed Tables
* Spark Managed tables have persistent metadata and uses Hive metastore to implement this. So we have to enable Hive support in our spark session via .enableHiveSupport() option
* Data in managed tables is available to many other sql compliant tools such as Tableau, Power BI etc via JDBC/ODBC Connector
* We are first going to Create a partitioned Managed Table via Bucketing so our 3 threaded local sparksession can process it simultaneously
* Here are the Partitions 
![partition image](https://i.imgur.com/cEI1ADE.jpeg)
