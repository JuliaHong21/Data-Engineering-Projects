# Project 1: Data Modeling with Postgres - ETL

## Introduction
A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analytics team is particularly interested in understanding what songs users are listening to. Currently, they don't have an easy way to query their data, which resides in a directory of JSON logs on user activity on the app, as well as a directory with JSON metadata on the songs in their app.

They'd like a data engineer to create a Postgres database with tables designed to optimize queries on song play analysis, and bring you on the project. Your role is to create a database schema and ETL pipeline for this analysis. You'll be able to test your database and ETL pipeline by running queries given to you by the analytics team from Sparkify and compare your results with their expected results.


## Schema for Song Play Analysis

### Fact Table
##### 1. songplays - records in log data associated with song plays i.e. records with page NextSong
  * songplay_id, start_time, user_id, level, song_id, artist_id, session_id, location, user_agent

##### Dimension Tables
 2. users - users in the app
  * user_id, first_name, last_name, gender, level
 3. songs - songs in music database
  * song_id, title, artist_id, year, duration
 4. artists - artists in music database
  * artist_id, name, location, latitude, longitude
 5. time - timestamps of records in songplays broken down into specific units
  * start_time, hour, day, week, month, year, weekday


## Project Steps
 1. Create Tables
 2. Build ETL Processes
 3. Build ETL Pipeline


