# Movie-Dataset_Inferencial-Stats-Project
## Create a report of IMDB dataset
### Data Analysis

### Introduction
To explore the the IMDB dataset and report findinigs on **correlations** between **vote average** of the movies and other features.
The dataset contians 10866 rows with 21 numerical or categorical features. 

[View Report Here](https://github.com/shreyasdhuliya/Movie-Dataset_Inferencial-Stats-Project/blob/master/Movie_dataset_Inferential_stats.ipynb)

### Installations
This project requires Python 2.7 and the following Python libraries installed:
- NumPy
- Pandas
- matplotlib

### Data

The data is taken from kaggle database [clik here to download](https://d17h27t6h515a5.cloudfront.net/topher/2017/October/59dd1c4c_tmdb-movies/tmdb-movies.csv.)
It contains information of 10866 movies.  Few columns have miissing data

columns
- id,imdb_id - index or row number of the movie
- popularity -
- budget,revenue - budget and revenue in Dollars
- revenue
- original_title,cast,homepage - Title of the movie, casts in the movie,website of the movie
- director - Director of the movie
- tagline,keywords - Few words of the movie, keywords separated with |
- overview,runtime - words describing hte plot, runime in minutes
- genres,production_companies - Genres of the movie separated with |, production companies separated with |
- release_date,release_year - Column for release date and release year
- vote_count,vote_average - total count of the votes, average of the overall votes
- budget_adj,revenue_adj
