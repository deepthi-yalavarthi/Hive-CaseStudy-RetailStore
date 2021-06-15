# RetailStore-Hive-CaseStudy
Hive-CaseStudy using AWS

With online sales gaining popularity, tech companies are exploring ways to improve their sales by analysing customer behaviour and gaining insights about product trends. Furthermore, the websites make it easier for customers to find the products they require without much scavenging. Needless to say, the role of big data analysts is among the most sought-after job profiles of this decade. Therefore, as part of this assignment, we will be challenging you, as a big data analyst, to extract data and gather insights from a real-life data set of an e-commerce company.

You will find the data in the link given below.

- https://e-commerce-events-ml.s3.amazonaws.com/2019-Oct.csv 
- https://e-commerce-events-ml.s3.amazonaws.com/2019-Nov.csv

The implementation phase can be divided into the following parts: 
- Create the Key pair in AWS
- Create S3 bucket and copy the csv data files into s3 bucket
- Create the EMR cluster and launch EMR that utilizes the Hive services
- Move the data from the S3 bucket into the HDFS 
- Creating the database and launching Hive queries on your EMR cluster
- Creating the structure of your database and use optimized techniques like partitioning and bucketing to run your queries as efficiently as possible and Show the improvement of the performance after using optimization on any single query.

Run Hive queries to verify the analysis on given dataset.

Cleaning up:
Drop your database, and Terminate your cluster

Analysis performed on the questions given below.

- Find the total revenue generated due to purchases made in October. 
- Write a query to yield the total sum of purchases per month in a single output. 
- Write a query to find the change in revenue generated due to purchases from October to November. 
- Find distinct categories of products. Categories with null category code can be ignored. 
- Find the total number of products available under each category. 
- Which brand had the maximum sales in October and November combined? 
- Which brands increased their sales from October to November? 
- Your company wants to reward the top 10 users of its website with a Golden Customer plan. Write a query to generate a list of top 10 users who spend the most.

© 2021 GitHub, Inc.
