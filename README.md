# Movie-Recommender-System

Here in this notebook, I designed a model of Movie Recommendation System with TMDB dataset in three parts:

	Part I. Getting movies that are similar to a chosen one. I tried two possible variants of movie similarity metrics. First: cosine similarity of movie description and taglines. Second: cosine similarity of director, cast, keywords and genres. As a result, I chose second one, because you still get similar by keywords and description movies, and some films from the same director, genres and cast.

	Part II. Creating a Collaborative Filtering System. With a help of amazing Surprise library, I build a model that can predict user rating of a chosen movie, based on user's previous ratings and ratings of other users that have watched this film.

	Part III. Making a Hybrid Recommendation System. For a given user and chosen movie, get similar films from Part I system. After that sort them by predicted user rating.

As a result, we can get different movie recommendations for a different users, based on their interest.

I was inspired by Rounak Banik and kinopoisk.ru recommendations.
