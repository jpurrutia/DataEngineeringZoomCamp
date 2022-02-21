# Data Engineering ZoomCamp by DataTalks Club

I am participating in Data Engineering Zoom BootCamp by DataTalks Club and am tracking what I am learning as well as my progress throughout the course.

## High Level Architecture and Process of the course

![Architectural Diagram](./images/architectual_diagram.jpeg)

## Overview
- Price: $0
- Duration: 9 Weeks <br>
## Topics Covered and Tools used:
- Week 1: Introduction & Pre-requisites with Docker, PostgreSQL, Terraform & Google Cloud Platform
- Week 2: Data Ingestion and Workflow Orchestration with Docker and Apache Airflow
- Week 3: Data Warehousing in Google BigQuery
- Week 4: Analytics Engineering with dbt
- Week 5: Batch Processing with Apache Spark
- Week 6: Streaming with Apache Kafka
- Weeks 7/8/9: Final Project <br>

## Week 1 
Topics:
- Understanding the Hierrachies withing a host machine and its environment
- Important Concepts to understand for Data Engineering
- Docker

In this week, the course covered a lot. 
- The basics of Docker and using containerized applications
- running data pipelines locally in a jupyter notebook environment but also running a scripting pipeline in a different environment.
- Setting up an environment for PosgtgreSQL both locally and in a containerized environment
- Interacting with PostgreSQL in both a command line interface using pgcli and a user interface with PgAdmin
- Creating tables and populating data in those tables with a data pipeline
- Setting up and using Google Cloud Platform which is the console or suite for devloping in the cloud similar to AWS and Azure
- Using IAM to create a service account with the right roles and permissions to create a project
- Finally, an Intro to Terraform - using terraform and Infrastructure as code to spin up cloud instances and resources by bypassing the user console

Week 1 took some work to ensure environments were configured correctly and to establish a foundation for the rest of the course but there was a lot to learn about and a lot that served as a refresher from my past projects. I'm looking forward to the coming weeks. <br>

## Week 2
Topics:
- Workflow Orchestration
- Understanding the steps in a data pipeline workflow (ETL/ELT)
- Setting Up Airflow with Docker-Compose
- Setting up Direct Acyclic Graphs (DAGs)
- Extracting CSVs, converting to Parquet, and uploading to GCS buckets to imitate a Data Lake

Airflow is a tool that I really like using. It's a way to automate tasks and as some have put it, "cronjobs on steroids." I've been working a lot lately in workflow and I enjoyed this week and looking at different persepctives in DAG building.

