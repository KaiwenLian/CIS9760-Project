# CIS9760-Project

# IMDB Data Analysis with PySpark on AWS EMR

## Project Description

This project utilizes AWS Elastic Map Reduce (EMR) and PySpark to conduct data analysis on IMDB's extensive datasets sourced from Kaggle. The primary goal is to demonstrate the setup and use of a distributed computing environment to handle and analyze large datasets that exceed the capacity of conventional in-memory data processing.

## Technology Stack

- **AWS Elastic Map Reduce (EMR)**: Utilized for provisioning and managing the Spark cluster. AWS EMR is chosen for its scalability, reliability, and seamless integration with other AWS services.
- **Apache Spark**: A powerful, distributed data processing engine used for big data workloads. Spark is run on the EMR cluster.
- **PySpark**: The Python API for Spark, used here to script our data analysis tasks, enabling data manipulation and query execution in a more accessible language.
- **Jupyter Notebook**: Provides an interactive computing environment where the analysis is performed and documented, allowing for direct execution of PySpark code and immediate viewing of results.

## Setup Instructions

1. **Provision a Spark cluster on AWS EMR**: Configure the cluster to include Spark and JupyterHub.
2. **Access Jupyter Notebook via EMR**: Connect to your JupyterHub instance running on EMR.
3. **Load Data**: Import the IMDB datasets from Kaggle into your Spark cluster's distributed file system.
4. **Run Analysis**: Execute the PySpark scripts in the Jupyter Notebook to analyze the data.

## Expected Outputs

The completion of this project will yield a `Project_Analysis.ipynb` Jupyter Notebook file, containing all the queries and analyses performed, along with their results.

## Conclusion

This setup exemplifies the use of modern cloud-based and big data technologies to address challenges associated with large-scale data analysis. It is a testament to how big data tools can efficiently process and analyze vast datasets in a scalable manner.

---
