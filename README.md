🚀 Project Overview
This project is an ETL pipeline built using Apache Airflow to automate the process of extracting raw sales data from a CSV file, transforming it into a clean and structured format, and loading it into a MySQL database. The goal is to make the data ready for analysis and reporting.

The workflow is organized as a daily-scheduled Airflow DAG, with clear modular tasks for Extract, Transform, and Load phases. This setup ensures reusability, scalability, and visibility into every step of the pipeline execution.

🧰 Tools & Technologies Used
Apache Airflow – to orchestrate and schedule the ETL workflow

Python – for scripting and logic in ETL tasks

Pandas – to transform and clean the data

MySQL – as the target database to store structured sales data

Docker & Docker Compose – to containerize and manage Airflow and MySQL environments
