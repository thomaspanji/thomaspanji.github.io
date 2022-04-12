# Data Engineer's Portfolio

Hi! I'm Thomas. This page shows you all mini projects I made about data engineering. Some of them were built when I took an online class on data engineering. After graduation, I try to implement the knowledge I have by doing several projects that leverage any data engineering tools, like Python, Apache Spark, Apache Kafka, Apache Airflow, and many more.

Here are some project explanations. Please click on the link in the project title which directs you to the appropriate Github repository.

1. [Create an End-to-end Data Pipeline to build Google BigQuery Data Warehouse ](https://github.com/thomaspanji/final-project-digitalskola)

    This is the final project from the online class I took from Digital Skola. The main idea of the project is creating a data pipeline to process raw files and create tables for a data warehouse. I played with Google Cloud Platform to run the pipeline. To be specific, the processes consist of these steps:
    * Upload raw files to Google Cloud Storage.
    * Create a Dataproc cluster to host Spark environment.
    * Run a PySpark application to convert the raw files to Parquet.
    * Load the Parquet files as external tables in Google BigQuery
    * Aggregate all necessary data from the external tables to create a data warehouse.

    To run the steps automatically, I used Apache Airflow as a workflow orchestrator which was provided by Google Composer. The workflow can be visualize like the image below.
    
    ![workflow](https://github.com/thomaspanji/final-project-digitalskola/blob/main/img/airflow-dag.png)

2. [Streaming ISS position data using Apache Kafka](https://github.com/thomaspanji/streaming-iss-kafka)

    
