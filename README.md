Document Process

Do the following steps in your README.md file. • Discuss the purpose of this database in the context of the startup, Sparkify, and their analytical goals.
The purpose of the database is so Sparkify analytics can do analysis on the songs played on their platform

• How to run the Python scripts

run create_tables.py to create the sparkifydb database, then run etl.py to excute the ETL followed by test.ipynb to see if your records have been added

• An explanation of the files in the repository

song table holds "song_ID", "title", "artist_ID", "year", "duration" - songs in the music database

artist table holds "artist_ID", "name", "location", "latitude", "longitude" - artists in the music database

time table holds hour, day, week, month, year, weekday, start_time - timestamp of each songplay

user table holds 'userID', 'firstname, 'lastname', 'gender', 'level' - users of the app

• State and justify your database schema design and ETL pipeline.

The songplay dataset is used to create a schema which can be used to query
ETL the log_data, to create the time and users, songs and artists dimensional tables


