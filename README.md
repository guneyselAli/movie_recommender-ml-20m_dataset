# Movie Recommender System

## Overview

This project implements a Movie Recommender System with multiple recommendation methods, including Popularity, Content Filtering, Collaborative Filtering, Matrix Factorization, and Hybrid techniques. These methods are applied to the MovieLens 20M Dataset


## Methods

### Popularity
The Popularity method recommends movies based on their overall popularity, irrespective of user preferences.

### Content Filtering
Content Filtering suggests movies based on the genres of the given movie. It basically finds movies with similar genres and then returns back most popular ones amongs them.

### Collaborative Filtering
Collaborative Filtering recommends movies by analyzing user interactions, finding similarities between users, and suggesting items based on the preferences of similar users. The function takes a movie name as an input, and then find the users who liked this movie. After that the function finds other movies liked by these users and picks the commonly liked ones.

### Matrix Factorization
Matrix Factorization is implemented using the Surprise library to decompose the user-item rating matrix and make personalized recommendations. The function takes an userId as an input and returns desired amount of movies. 

### Hybrid
The Hybrid method combines content filtering and collaborative filtering recommendation techniques to provide more accurate and diverse movie suggestions.

