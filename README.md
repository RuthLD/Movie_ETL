# Movie_ETL
Using the ETL process to clean and merge data.
## Goal
📽️ Extract the movie data from [Wikipedia](https://github.com/RuthLD/Movie_ETL/blob/main/Resources/movies_metadata.csv) and [Kaggle](https://github.com/RuthLD/Movie_ETL/blob/main/Resources/ratings.csv) from their respective files, transform the datasets by cleaning them and merging them together, then load the cleaned dataset into a SQL database.

## ETL Process
Two examples of how the movie information from Wikipedia was cleaned is the identifican of alternate titles for the films and the standardization of the column names.
* ![alt_titles.png](https://github.com/RuthLD/Movie_ETL/blob/main/Resources/alt_titles.png)
* ![column_names.png](https://github.com/RuthLD/Movie_ETL/blob/main/Resources/column_names.png)


One other way the information was condesned was to filter out TV programs using a if statement.
* ![no_tv.png](https://github.com/RuthLD/Movie_ETL/blob/main/Resources/no_tv.png)

## Tables in Database
The "movies" table contains 6,052 rows based on the kaggle and wikipedia data.
* ![movie_query.png](https://github.com/RuthLD/Movie_ETL/blob/main/Resources/movies_query.png)


The "ratings" table includes 26,024,289 rows of data. 
* ![ratings_query.png](https://github.com/RuthLD/Movie_ETL/blob/main/Resources/ratings_query.png)
