# movies-analysis
## Author DANIEL KIMUTAI
# Overview
## Microsoft wants to create a new movie studio but since they don't know anything about creating movies.I have been tasked to explore what type of films  are currently doing at best at the box office.I explored the data given and figured out that i needed only two  use data from imdb and box office mojo.My analysis focused on a few aspects of  success in  a movie that is ratings and gross revenue .Using this aspects i formulated my guide questions based on top genres with high ratings,  genres with high gross value and also which month is best fit for  releasing in order for it to sell. Data Visualization tools such as the bar graph was used to give a clear understanding of this concepts.
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
# DATA ANALYSIS
## I used data visualazation ,by using the bargraph and scatter plot  to  bring out clear insights to my questions
 ### a)What type of movie genre is currently performing well based on its rating![bargraph](https://user-images.githubusercontent.com/110474324/187013825-8821a51c-1870-4abb-9e5c-032a0777d716.png)
 ##### According to our data above , we can see that the distribution of genre based on the the top 50 movies based on the top ratings  shows that documentary is the nost popular type of genre with the high ratings and most liked by people.
### c) Which  genres have the highest total gross value ?![633e9837-8334-458a-a1ad-6f42be325636](https://user-images.githubusercontent.com/110474324/187013870-60dbd057-dfa6-469d-8448-e49a9eece180.png)
### According to my analysis, which was  based on checking which genre has the highest gross value .I concluded that most movies with the highest total gross were based on Action,Adventure,Sci-Fi with a  total gross of over 3 billion dollars,followed closely by Action,Adventure,Animation with aroound 2 billion dollars.The total gross was based on addin both the domestic and worldwide gross!
## e) Which is the best month to release  a movie in order for it to sale?

![f9a23d80-dfa2-45fa-b2dd-dedbc7121c53](https://user-images.githubusercontent.com/110474324/187013970-5b4d4e38-56e2-42dc-8d6f-e78379cb10e1.png)
### From the analysis ,our graph shows that April,June and May have the highest total gross value,hence movies released on these months garner alot of gross values
# Conclusion
## This is the summary of my analysis
### 1. Among the the top 50 movies based on the top ratings  shows that documentary is the nost rated type of genre with the high ratings and most liked by people.
### 2.Most movies with the highest total gross were based on Action,Adventure
### 3. April,June and May have the highest total gross value
# Recommendations
### Based on my analysis in order for microsoft to   have a successful movie studio  they should:
### 3.Microsoft should produce movies based on Action,Adventure as they are the top selling movies, with a higher total gross.
### 4.The best release months are April,May and June, Microsoft should basically be releasing movies in this month.
### For Microsoft to set a  foot on the movie industry they should mainly focus on producing Documentary and Action adventure movies.
