 # ETL data pipeline using Apache Airflow. 

This data pipeline is designed to automate the extraction and storage of data engineering books available on Amazon. It uses Docker to containerize the entire workflow, ensuring consistency and ease of deployment across different environments. The pipeline is scheduled to run at regular intervals, periodically pulling data directly from Amazon's website.
To enhance the readability and usability of the README, you could add a diagram to visually represent the data pipeline. Here’s a suggested README description with an added image section:

---

# Data Engineering Books Extraction Pipeline

This repository hosts a Dockerized data pipeline designed to automate the extraction of data engineering book listings from Amazon and store them in a PostgreSQL database. Scheduled runs ensure the database is continuously updated with the latest listings.

### Key Features
- **Automated Web Scraping**: Retrieves book data, including title, author, price, ratings, and publication date.
- **Database Storage**: Data is stored in a PostgreSQL database for easy querying and further analysis.
- **Scheduled Runs**: The pipeline operates on a schedule, keeping the dataset up-to-date.
- **Dockerized Setup**: All components are containerized for easy deployment and portability.

---

## Architecture Diagram

![Data Pipeline Architecture](pipeline_design.png)

The diagram below illustrates the architecture and flow of the data pipeline, including each component's role in the data extraction, storage, and scheduling process.

- **Scraper Container**: Gathers data from Amazon at scheduled intervals.
- **PostgreSQL Database Container**: Stores structured book data.
- **Scheduler (e.g., Airflow)**: Manages and automates scraping intervals.

To generate the diagram, I can create an illustrative image if you’d like. Just confirm any specifics you'd like shown!
