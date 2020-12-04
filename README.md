Introduction
A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analysis team is particularly interested in understanding what songs users are listening to. Currently, there is no easy way to query the data to generate the results, since the data reside in a directory of CSV files on user activity on the app.
They'd like a data engineer to create an Apache Cassandra database which can create queries on song play data to answer the questions, and wish to bring you on the project. Your role is to create a database for this analysis. You'll be able to test your database by running queries given to you by the analytics team from Sparkify to create the results.

Project Overview
In this project, you'll apply what you've learned on data modeling with Apache Cassandra and complete an ETL pipeline using Python. To complete the project, you will need to model your data by creating tables in Apache Cassandra to run queries. You are provided with part of the ETL pipeline that transfers data from a set of CSV files within a directory to create a streamlined CSV file to model and insert data into Apache Cassandra tables.

We have provided you with a project template that takes care of all the imports and provides a structure for ETL pipeline you'd need to process this data.

There are to get started to create the files create_tables.py and sql_queries.py and for that, a schema will be created where every part of files about songs and data which will be defined through the next schema that it will be in start which gets the next part:

1.	sonplays: this part is used to associate the datas which song which is play.
2.	users: in this part, it can watch the user of the app
3.	songs: in this part, it can watch the songs in the database.
4.	artists: in this part are the artists in the database.
5.	time: in this part, it can watch the time about every song
 
 
 
 
 
