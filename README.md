# PySpark-Hands-on
My Hands on exposure to pyspark
<<<<<<< HEAD

# Dataset 
    The dataset we are going to use is the global terrorism dataset. We are going to use transformations on it and try to clean it up for visualization.
    The dataset is going to reside inside /data folder in the project folder. 

## Spark Managed Tables
* Spark Managed tables have persistent metadata and uses Hive metastore to implement this. So we have to enable Hive support in our spark session via .enableHiveSupport() option
* Data in managed tables is available to many other sql compliant tools such as Tableau, Power BI etc via JDBC/ODBC Connector
* We are first going to Create a partitioned Managed Table via Bucketing so our 3 threaded local sparksession can process it simultaneously
* Here are the Partitions 
![partition image](https://i.imgur.com/cEI1ADE.jpeg)
=======
# Dataset
 The dataset we are exploring in this Hands-On is Global Terrorism dataset from Kaggle. The idea is to explore it and the clean it up if and where required. The dataset will be located in the /data folder.

# Using Jupyter Notebooks to Explore the Dataset
>>>>>>> 8c71cc9bb8d565a1beeb36239fb06f0d486f05bc
