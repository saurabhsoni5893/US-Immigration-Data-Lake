# US Immigration Data Lake
## Data Engineering Capstone Project
#### **Goal:** To support U.S Customs & Border Protection Department to make better decisions on Immigration Policies

<img src="https://github.com/saurabhsoni5893/US-Immigration-Data-Lake/blob/master/images/DataLake.png" align="centre">

## Overview

The purpose of this data engineering capstone project is to give students a chance to combine what they've learned throughout the program. This project will be an important part of learners portfolio that will help to achieve data engineering-related career goals. We could choose to complete the project provided by the Udacity team or define the scope and data ourselves. I took the first approach in building the Data Lake on the data on immigration to the United States provided by Udacity.

## Business Scenario

A business consulting firm specialized in data warehouse services through assisting the enterprises with navigating their data needs and creating strategic operational solutions that deliver tangible business results is contacted by U.S Customs & Border Protection Department. Specifically, they want help with the modernization of department's data warehousing infrastructure by improving performance and ease of use for end users, enhancing functionality, decreasing total cost of ownership while making it possible for real-time decision making. In total, the department is asking for a full suite of services includes helping department with data profiling, data standardization, data acquisition, data transformation and integration.

The U.S. Customs and Border Protection needs help to see what is hidden behind the data flood. The consulting firm aim to model and create a brand new analytics solution on top of the state-of-the-art technolgies available to enable department to unleash insights from data then making better decisions on immigration policies for those who came and will be coming in near future to the US.

## The Architecture

The whole solution is cloud based on top of **Amazon Web Services (AWS)**. First, all the datasets were preprocessed with **Apache Spark** and stored in a staging area in **AWS S3 bucket**. Then, it is loaded into a **Amazon Redshift** cluster using an **Apache Airflow** pipeline that transfers and checks the quality of the data to finally provide the department a Data Lake for their convenient analysis.

#### The Data Model

![](https://github.com/saurabhsoni5893/US-Immigration-Data-Lake/blob/master/images/star-schema.PNG)

## Structure of the Project

Following the Udacity guide for this project, the structure is as shown below:

 - Step 1: Scope the Project and Gather Data
 - Step 2: Explore and Assess the Data
 - Step 3: Define the Data Model
 - Step 4: Run ETL to Model the Data
 - Step 5: Complete Project Write Up

**To explore all these steps in details, please go to 
Link: [US_Immigration_Data_Lake](https://github.com/saurabhsoni5893/US-Immigration-Data-Lake/blob/master/US_Immigration_Data_Lake.ipynb)