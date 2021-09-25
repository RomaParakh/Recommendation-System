# Recommendation-System
Project: Recommendation System for entertainment platforms (moivies and shows).

Program: B.Tech CSBS

SAP ID: 70362019156

Domain: Machine Learning

Description: A recommendation system predicts the possibility that a user would favour few products over other. This system aims at providing recommendation for movies and TV-shows which user might like, based on user’s historical preferences. This system is a content based recommender system which focuses on the attributes such as genre, title, cast etc. and suggests a movie or show which user might like to watch. Recommender system helps in prioritising and personalising content as per one’s interest.

Technique Used: With this system we suggest the movies and shows based on 5 features: genres, type, title, director and cast.First we create a data frame with the selected features and generate count matrix for the combined features using CountVectorizer (converts a collection of text to a matrix of token counts). Next we compute cosine similarity (to find distance between vectors (text)) based on the count matrix. Once the input is taken we get its index from title, then we display top 20 similar movies in descending order on basis of their similarity score.

Dataset Link: https://www.kaggle.com/shivamb/netflix-shows
