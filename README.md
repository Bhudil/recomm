# Movie Recommendation System

The following model is used to recommend a list of movies to the user according to correlation with the user's favorite films. The parameters of 'ratings' and 'number of ratings' is also taken in consideration when suggesting a movie to the user. A combination of three datasets is used to create the perfect pivot table and give satisfying results.

STEPS-

1) The u.data, u.item and Movie_titles datasets are merged and a Master Dataframe is created

2) New columns like 'no of ratings' are Feature Engineered and Visualized using Seaborn

3) A pivot table is created to combine all the entries.

4) Two of the user's favorite movies are selected (eg- StarWars and LiarLiar)

5) A list of movies are outputted which have best correlation with the chosen movies (high ratings are also considered)
