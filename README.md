# Anime-Recommendation-System
Anime Recommendation System


Building a recommendation system that will show relevant information of interest to users is more important to any business. In particular, for an online business portal, it is important to show the customers what they would probably be liking, to retain their business with you. The anime recommendation system is intended to show the top 15 anime of interest to an existing user based on their previous interests or based on other similar users and for a new user based on similar users interest. The channel with the better recommendation system will be more probable to become popular, thereby increasing the subscription count to the channel. 


This project is aimed at recommending anime of interest to users, both existing and new, based on similar animes, similar user’s favorite and using LightGBM Ranker.


Data
The dataset contains information about over 17000 anime and over 57M user’s rating information. We have used the following files to develop the recommendation systems in this project.
	Anime - Unique ID, Name of the anime in English and Japanese, Avg Score given by all the users, Genre, Type, Number of Episodes, Broadcasted date	, PG rating info, its Popularity, Number of people Watched, Completed, Kept-onhold, and Dropped watching and some more.
	Rating - contains anime id, user id and the rating of the users who have completed watching the anime.
  
  
 Three models were built for Anime Recommendation:
 Item-based recommendation: 

