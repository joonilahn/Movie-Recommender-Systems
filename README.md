# Movie Recommender Systems
==============================
## Overview
This project is to implement **Movie Recommender Systems** for [MovieLens 100k dataset](https://grouplens.org/datasets/movielens/).

## Type of Recommendation Systems
### 1. Popularity-based Recommendation
This might be the most simple idea to build the recommender system. This algorithm finds the items which are liked by most number of users, and recommend the same set of items to every user. In other words, the recommended items are not personalized for each user.

### 2. Content-based or Collaborative Filtering
In general, recommender systems are based on one of two different strategies, *content filtering* and *collaborative filtering*, respectively.

#### 2.1. Content Filtering
*Content filtering* approach uses profiles of users and/or products. A movie profile may include its genre, directors, actors and etc, while a user profile might include user's age, gender, demographic information and etc.

#### 2.2. Collaborative Filtering
Another strategy for recommender systems relies on past users' behaviours such as previous activities or product ratings, and use those data for recommending items. This strategy is called *collaborative filtering*.
We can build several different models using collaborative filtering such as **User-User Collaborative filtering**, **Item-Item Collaborative filtering** and **Matrix Factorization model**.

## What we are using for this project
We are going to use **collaborative filtering** based algorithms to build simple recommender systems because it is powerful and also used by many big companies like Amazon and YouTube. (They use a lot more complicated algorithms though)

We are going to explore three different collaborative filtering-based algorithms, **1) Item-Item Collaborative filtering**, **2) Matrix Factorization model** and **3) Neural Network**.

## MovieLens 100k Dataset
The MovieLens dataset has been collected by the GroupLens Research Project at the University of Minnesota. The dataset consists of

- 100,000 ratings (1-5) by 943 users on 1682 movies.
- Demographic infomations for the users (age, gender, occupation and zip)
- Genres of movies

The *u.data* file contains movie ratings information which were rated by the users.

<img src='https://www.analyticsvidhya.com/wp-content/uploads/2016/06/2.-ratings.png' width=480>

