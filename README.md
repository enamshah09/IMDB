# IMDB
Developed a target application which efficiently runs queries on the MovieLens/imdb data and extracts useful information. The primary users for this application will be users seeking for movies and their ratings that match their search criteria. 

It has a user interface that provides the user the available movie attributes such as `genre, country, cast, rating, year and user’s tags and ratings`. Using this application, the user can search for the movies from various categories that have the properties (attributes) the user is looking for. 

The user can filter the search results by available movie attributes such as genre, country, cast, rating, year and user’s tags and ratings. The application should return movie title, genre, tags, year, country, ratings (Critics/Audience) and number of reviews (Critics/Audience), that match the filtering criteria defined by the user.

## Implementation
Wrote the SQL queries to search your database.
- Established connectivity with the DBMS.
- Embedded/executed queries in/from the code. Retrieved query results and parsed the results to generate the output that will be displayed on the GUI.
- Implemented a GUI where the user can,
	* Search for movies that match the criteria given
	* Browse through attributes for the movies; select the movie attributes that user wants to search for
	* Search for the movies that belong to the attributes that user specifies along with user’s tags and ratings
	* The application should be able to search for the movies that have either all the specified attributes (AND condition) or that have any of the attributes specified (OR condition)
	* Select a certain movie in the search results and list the following for that movie(s): movie title, genre, users’ tags, year, country, ratings (critics/audience) and number of reviews (critics/audience)

## Required .sql files:
1. createdb.sql: This file will create all required tables. In addition, it should include constraints, indexes, and any other DDL statements you might need for your application.
2. dropdb.sql: This file will drop all tables and the other objects once created by your createdb.sql file.

