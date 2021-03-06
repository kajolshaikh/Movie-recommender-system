# Movie-recommender-system

Data:
The data to be used for this project will contain 3 datasets.
 The first dataset (ratings.csv) contains 26 million ratings from 270,000 users for all 45,000 movies. Ratings are on a scale of 1-5 and have been obtained from the official GroupLens website along with 3 additional columns namely Movie ID, User ID and timestamp. 
The second dataset (movies.csv) consists movies released on or before July 2017. This dataset contains 24 columns such as cast, crew, plot keywords, budget, revenue, posters, release dates, languages, production companies, countries, TMDB vote counts etc for 45,000 movies. 
The third dataset (credits.csv) used contains 3 columns cast, crew and id which gives the cast and crew information for all movies.
Algorithms:
We will use 2 algorithms here.
1.Popularity Based Recommendation System: This system as the name suggests will recommend the trend i.e. the most watched movies and TV shows at that point of time. For the sake of our project, we will feature a movie in the recommendation system only if the movie’s rating will be higher than 90% of the remaining dataset.
2.Collaborative Filtering: This system will recommend movies to a user based on his historic choices. It updates and recommends movies based on the user’s selection of movies from the last recommendation.
