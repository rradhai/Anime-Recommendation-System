# Anime-Recommendation-System
Anime Recommendation System

Building a recommendation system that will show relevant information of interest to users is more important to any business. In particular, for an online business portal, it is important to show the customers what they would probably be liking, to retain their business with you. The anime recommendation system is intended to show the top anime of interest to an existing user based on their previous interests or based on other similar users and for a new user based on similar users interest. The channel with the better recommendation system will be more probable to become popular, thereby increasing the subscription count to the channel. 


This project is aimed at recommending anime of interest to users, both existing and new, based on similar animes, similar user’s favorite and using LightGBM Ranker.


Data: 

The dataset contains information about over 17000 anime and over 57M user’s rating information. We have used the following files to develop the recommendation systems in this project.
	Anime - Unique ID, Name of the anime in English and Japanese, Avg Score given by all the users, Genre, Type, Number of Episodes, Broadcasted date	, PG rating info, its Popularity, Number of people Watched, Completed, Kept-onhold, and Dropped watching and some more.
	Rating - contains anime id, user id and the rating of the users who have completed watching the anime.
  
  
 Three models were built for Anime Recommendation:
 
 1. Item-based recommendation: This has been done using 3 different approaches: the Nearest Neighbors algorithm (the distance of the returned anime list has been more than .9), Tfidf Vectorizer with Linear Kernel (using the Synopsis of the anime) and Count Vectorizer with Cosine Similarity (using all the other text columns of the Anime). The results returned has been compared with the user data and found the records are matching with the user interests. 
 1. User-based recommendation: A custom recommendation model has been built to find the similar users interest and recommend the anime. This recommendation can be made if we know an anime of interest to the user in request.
 1. LightGBMRanker: Using this free, open-source, distributed, gradient-boosting framework, Classification, Ranking and Various other machine learning tasks can be performed with commendable accuracy. Using the Ranking feature, we have built this anime recommendation model. The hyperparameter tuning framework, Optuna has been used for optimizing the hyperparameters of this model. This model ranks the anime with NDCG score of 0.9862. 
 
 

	
