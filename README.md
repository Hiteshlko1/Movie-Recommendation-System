#  🎥 ***Movies Recommender System***🎥 


**Dataset:📂**

https://www.kaggle.com/rounakbanik/movie-recommender-systems/data

Dataset:📂

https://www.kaggle.com/rounakbanik/movie-recommender-systems/data

**About the Dataset**:🎬

The dataset consists of  metadata for all 45,000 movies listed in the Full MovieLens Dataset. The dataset consists of movies released on or before July 2017. Data points include cast, crew, plot keywords, budget, revenue, posters, release dates, languages, production companies, countries, TMDB vote counts and vote averages.


![image](https://user-images.githubusercontent.com/96238505/162626548-4c3ed631-2f5a-4877-9590-d2392ff0cd67.png)

**Dataset Description**: 📝

This dataset consists of the following files:

⚡ **movies_metadata.csv**: 

The main Movies Metadata file. Contains information on 45,000 movies featured in the Full MovieLens dataset. Features include posters, backdrops, budget, revenue, release dates, languages, production countries and companies.

⚡ **keywords.csv**:

 Contains the movie plot keywords for our MovieLens movies. Available in the form of a stringified JSON Object.


⚡ **credits.csv**: 

Consists of Cast and Crew Information for all our movies. Available in the form of a stringified JSON Object.


⚡ **links.csv**: 

The file that contains the TMDB and IMDB IDs of all the movies featured in the Full MovieLens dataset.

⚡ **links_small.csv**: 

Contains the TMDB and IMDB IDs of a small subset of 9,000 movies of the Full Dataset.


⚡ **ratings_small.csv**: 

The subset of 100,000 ratings from 700 users on 9,000 movies.


# Problem Statement:❓
Using different techniques of Machine Learning, we need to build a Recommender System that recommends movies based on “ Cast, Genre, Reviews, TMDB/IMDB ratings”

Using different types of recommendation techniques like:
1. Popularity based recommender system
2. Content based Recommender System
3. Collaborative Recommender System







# **Conclusion**

In this notebook, we have built 3 different recommendation engines based on different ideas and algorithms. They are as follows:

▶ Simple Recommender: This system used overall TMDB Vote Count and Vote Averages to build Top Movies Charts, in general and for a specific genre. The IMDB Weighted Rating System was used to calculate ratings on which the sorting was finally performed.

▶ Content Based Recommender: We built two content based engines; one that took movie overview and taglines as input and the other which took metadata such as cast, crew, genre and keywords to come up with predictions. We also deviced a simple filter to give greater preference to movies with more votes and higher ratings.

▶ Collaborative Filtering: We used the powerful Surprise Library to build a collaborative filter based on single value decomposition. The RMSE obtained was less than 1 and the engine gave estimated ratings for a given user and movie.




