# IMDB-Movie-analysis
Project's Title:
-IMDB Movie Analysis

Project Description:
-analyzing Excel file contains one sheet named "IMDB_Movies" to recommend what country is best to invest in.

The columns in the "IMDB_Movies" sheet of the dataset are as follows:

-director_name: The name of the movie's director.
-num_critic_for_reviews: The number of critic reviews.
-gross: The gross earnings of the movie.
-genres: The genres associated with the movie.
-actor_1_name: The name of the first actor listed.
-movie_title: The title of the movie.
-num_voted_users: The number of users who voted/rated the movie.
-plot_keywords: Keywords related to the movie's plot.
-num_user_for_reviews: The number of user reviews.
-language: The language of the movie.
-country: The country where the movie was produced.
-budget: The budget for making the movie.
-title_year: The year the movie was released.
-imdb_score: The IMDb rating of the movie.

Calculated columns:

-earning: the total amount of money earned 
-%of income: the  percentage of money earned according to budget
-financial loss: show that if the movie got earn money more than the budget or not

Issues in the dataset:

.formatted issues:

-movie_title:has a letter "Â" in the end of every movie. (removed)

.Missing Values:

-plot_keywords: 30 missing values. (removed)
-language: 3 missing values and 1 value with none value. filled with "English" according to mode 

duplicated Values:

found in movie title that all row are the same except one column (removed)

Pivots:
1-total earning for country in year, USA was the most country in earning with 48408259834,south Korea was the most losing country in making -12307595627 
2-number films and it's language that filtered by year , English was the most language with 3329 film and the highest in 2002 with 176 film  
3-number of films in the country  USA was the most country making films by 2773 film 
4-avarage and max score for movie by country and year ,"The Shawshank Redemption" was the highest rate with 9.3 in 1994 made by USA 
5-sum of budget according to years , USA was the most country bay in movies making with total budget  113,111,456,678 ,"Pirates of the Caribbean: At World's End" was the most budget with 300,000,000 

visuals:

1-a plot graph between critical review and user review that show a very weak correlation between them that lead to understand their is no relation between them

2-a bar graph that represent the max score for movie in a country and in which year and average score for the country movies 


summary:

if u wanna to Invest in the film industry u should invest in USA country has most earning in film industry and don't invest in south Korea it lost about 1,230,759,567

for users we recommend to watch USA movies cause has the highest average rate for movies and most of films are English

