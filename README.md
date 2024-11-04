 # ETL data pipeline using Apache Airflow. 

This pipeline extracts data engineering books from Amazon, and stores it in the Postgres Database. 
The pipeline runs on a schedule and pulls data from the website.

This data pipeline is designed to automate the extraction and storage of data engineering books available on Amazon. It uses Docker to containerize the entire workflow, ensuring consistency and ease of deployment across different environments. The pipeline is scheduled to run at regular intervals, periodically pulling data directly from Amazon's website.
