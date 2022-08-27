# movies-analysis
## Business Understanding
### Most big companies are creating original video content ,microsoft wants to jump in on the fun.Microsoft have decided to create a new movie studio and since they don’t anything about movies ,i have been tasked to explore what types of movies are currently doing the best at the box office and come up with insights that will help them get into the industry.In order to come up with best insights .In order to assist them to achieve this goal and make successful movies, I looked at the highly performing movies  based on ratings,production budget and  gross value.I formulated a few questions that will help me come up with clear insights
 ### a)What type of movie genre is currently performing well based on its rating
### b).Does runtime affect the ratings /is there any relationship between runtime and the ratings?
### c). Which type of movies have the highest total gross value
 ### d).Which genre has the highest production budget and is there a relationship between the production budget and the total gross
### e). Which is the best month to release  a movie in order for it to sale?

## Data Understanding
### In order to get clear insights based on the questions above i collected  my information from two datasets.
### These datasets are
  ## im.db.zip- This is data  is  contained in a Zipped SQL data base and contains different tables of movie informatiom
  ## bom.movie_gross.csv.gz-This is a csv file,where each record represents,movvie,the release data,domestic gross,production_budget,worldwide gross of each movie.From this dataset I selected the following columns:
### movie  represents various types of movies
### release date- the date where each movie was  released
### domestic gross-local revenue based on the movie locality
### worldwide gross- international revnue  of the movie
### production budget - estimated cost of producing the movie

## Data Preparation and Data Cleaning
## 1.Loading the Data with Pandas and SQL
### I created two dataframes ,imdb_df through SQL and Budgets_df through pandas.Thes
## 2.Perfoming Data cleaning  on imdb_df to my first two questions
### I selected the main columns that i will work on,then  i checked for missing Values and duplicates
## 3.Perfoming Data cleaning on   Budgets_df and merging it to imdb_df
## I cleaned my dataset and I then merged the two data sets to answer my last two questions.

