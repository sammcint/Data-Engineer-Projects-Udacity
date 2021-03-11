# Data-Engineer-Nanodegree-Projects-Udacity
Repository for all projects completed in the [Data Engineer Nanodegree by Udacity.com](https://www.udacity.com/course/data-engineer-nanodegree--nd027)

### Educational Objectives:
* Create user-friendly relational and NoSQL data models
* Create scalable and efficient data warehouses 
* Work efficiently with massive datasets 
* Build and interact with a cloud-based data lake 
* Automate and monitor data pipelines
* Develop proficiency in Spark, Airflow, and AWS tools 



### Course 1: Data Modeling
------------------------------------------------------------------------------

#### Introduction to Data Modeling
* Understand the purpose of data modeling
* Identify the strengths and weaknesses of different types of databases and data storage techniques
* Create a table in Postgres and Apache Cassandra

#### Relational Data Models
* Understand when to use a relational database
* Understand the difference between OLAP and OLTP databases
* Create normalized data tables
* Implement denormalized schemas (STAR, Snowflake)

#### NoSQL Data Models
* Understand when to use NoSQL databases and how they differ from relational databases 
* Select the appropriate primary key and clustering columns for a given use case
* Create a NoSQL database in Apache Cassandra

**Project 1:** Data Modeling with Postgres 

**Project 2:** Data Modeling with Apache Cassandra

### Course 2: Cloud Data Warehouses 
------------------------------------------------------------------------------

#### Introduction to Data Warehouses 
* Understand Data Warehousing architecture
* Run an ETL process to denormalize a database (3NF to Star)
* Create an OLAP cube from facts and dimensions
* Compare columnar vs row oriented approaches

#### Introduction to the Cloud with AWS
* Understand cloud computing
* Create an AWS account and understand their services 
* Set up Amazon S3, IAM, VPC, EC2, RDS PostgreSQL

#### Implementing Data Warehouses on AWS 
* Identify components of the Redshift architecture
* Run ETL process to extract data from S3 into Redshift
* Set up AWS infrastructure using Infrastructure as Code (IaC)
* Design an optimized table by selecting the appropriate distribution style and sorting key 

**Project 3:** Build a Cloud Data Warehouse
 * Build an ELT pipeline that extracts their data from S3, stages it in Redshift, and transforms the data into a set of dimensional tables.

### Course 3: Spark and Data Lakes 
-------------------------------------------------------------------------------

#### The Power of Spark
* Understand the big data ecosystem 
* Understand when to use Spark and when not to use it

#### Data Wrangling with Sark
* Manipulate data with SparkSQL and Spark Dataframes
* Use Spark for ETL purposes 

#### Debugging and Optimization
* Troubleshoot common errors and optimize their code using the Spark WebUI

#### Introduction to Data Lakes
* Understand the purpose and evolution of data lakes 
* Implement data lakes on Amazon S3, EMR, Athena, and Amazon Glue
* Use Spark to run ELT processes and analytics on data of diverse sources, structures, and vintages

**Project 4:** Build an ETL pipeline for a data lake. The data resides in S3, in a directory of JSON logs on user activity on the app, as well as a directory with JSON metadata on the songs in the app. Load data from S3, process the data into analytics tables using Spark, and load them back into S3. Deploy this Spark process on a cluster using AWS.

### Course 4: Automate Data Pipelines
-----------------------------------------------------------------------------

#### Data Pipelines
* Create data pipelines with Apache Airflow
* Set up task dependencies 
* Create data connections using hooks

#### Data Quality
* Track data lineage 
* Set up data pipeline schedules
* Partition data to omptimize pipelines
* Write tests to ensure data quality

#### Production Pipelines
* Build reusable and maintanable pipelines
* Build your own Apache Airflow plugins 
* Implement subDAGS
* Set up task boundaries 
* Monitor data pipelines

**Project 5:** Create and automate a set of data pipelines. Configure and schedule data pipelines with Airflow and monitor and debug production pipelines
