# SQLAlchemy-Challenge

Module 10: Advanced SQL

This project uses Python and SQLAlchemy to do basic data exploration and analysis of a SQLite climate database. All analysis was done using SQLAlchemy (ORM queries), Pandas, and Matplotlib. It also provides an Flak API to query this climate data.

# Part I: Exploratory Climate Analysis
This part of the project analyzes Hawaii precipitation and weather station data to produce visualizations of rainfall and temperature patterns. It also supports the planning of visits to Hawaii with:

- Local precipitation summaries for each of the local weather stations 
- Temperature diaries for a flexible range of trip dates

It consists of:

- A SQLite database (Resources/Hawaii.sqlite)
- A Jupyter notebook (sqlalchemy-challenge/climate_analysis.ipnyb) that uses SQLAlchemy, Python Pandas and MatPlotlib to analyze and visualize this data.
- Bar charts, a histogram and an area chart that are visible within the notebook and also stored as .png files in the sqlalchemy-challenge folder.

# Part II: Climate App

This part of the project utilizes several SQLAlchemy precipitation and temperature queries in an API using a Python Flask app:

Home page
/api/v1.0/precipitation
Daily precipitation totals for last year
/api/v1.0/stations
Active weather stations
/api/v1.0/tobs
Daily temperature observations for the WAIHEE weather station
/api/v1.0/trip/yyyy-mm-dd
Min, average & max temperatures for the range beginning with the provided start date through 08/23/17
/api/v1.0/trip/yyyy-mm-dd/yyyy-mm-dd
Min, average & max temperatures for the range beginning with the provided start - end date range

It consists of:
- A SQLite database (Resources/Hawaii.sqlite)
- A Flask App (sqlalchemy-challenge/app.py)

# Resources
1. Modules 10: In Class Activities
2. Collaborated with fellow classmates
3. Class Instructor: Arooj A Qureshi
4. TA Instructor: Abdelrahman "Abdo" Elewah
5. 2 x Ask BCS Learning Assistants
6. Tutor: Limei Hou
