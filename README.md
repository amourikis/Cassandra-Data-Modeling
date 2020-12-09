# Project summary
This is the second project of Udacitys Data Engineering Nanodegree. For this project, I am working for the startup company which is called Sparkify. On this company they have been collecting data on songs and user acivity with their new music streaming app. My task is to create a Apache Casandra database with tables designed to optimize queries on song play analysis. 

## Content
- The Data
- Creating Tables, ETL Pipeline, and Quality Check
- Run

### The Data
For this project, I worked with one dataset: event_data. The directory of CSV files partitioned by date. The first part of this process was to get our data into a readable version so that we are able to process it. We want to process all data files and log them in a .csv file to be  processed from there.

### Creating Tables, ETL Pipeline, and Quality Check
When creating tables with a NOSQL database it is import too know what queries you are going to implement. We want tables to be specific to the query that we search. The queries I selected are as follows:

    1. Give me the artist, song title and song's length in the music app history that was heard during sessionId = 338, and itemInSession = 4
    2. Give me only the following: name of artist, song (sorted by itemInSession) and user (first and last name) for userid = 10, sessionid = 182
    3. Give me every user name (first and last) in my music app history who listened to the song 'All Hands Against His Own'

### Run
I am running this program with jupyter notebook through terminal. Prerequisites for running the project is python 3.x and Apache cassandra installed.

## How to run
1. Run Jupiter notebook using terminal.
2. After succesfully open the Jupiter noteboomk,execute the "Pipeline.ipynb" file.
