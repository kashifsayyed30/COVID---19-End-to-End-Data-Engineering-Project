# COVID---19-End-to-End-Data-Engineering-Project
This project outlines an end-to-end data engineering project focused on analyzing COVID-19 data using AWS services. This project aims to uncover patterns, trends, and risk factors associated with SARS-CoV-2 infection using data mining techniques.

* Key takeaways:
    * The project uses a dataset available on AWS Open Dataset.
    * The architecture involves several AWS services: S3, Crawler, AWS Athena, Glue ETL, Amazon Redshift, and AWS QuickSight, mostly within a VPC for security.
    * The workflow consists of 12 steps, including:

        * Data cleaning and uploading to S3
        * Using Crawler to create metadata tables
        * Analyzing data with Athena
        * Creating a dimensional model using Star Schema
        * Data transformation using Python and Pandas
        * Creating fact and dimension tables
        * Storing processed data in S3
        * Creating schemas and tables in Redshift
        * Copying data from S3 to Redshift
        * Creating a Glue Job
        * Visualizing data with QuickSight
* This project demonstrates a comprehensive approach to handling big data, from ingestion and processing to analysis and visualization, all within the AWS ecosystem.
* It showcases the integration of various AWS services to create a robust data pipeline for COVID-19 data analysis.


Project Credit: @Darshil Parmar
