# Recommender-System
## Collaborative Filtering Recommendation
One of the most popular methods for making recommendations is collaborative filtering. In collaborative filtering, I am using the collaboration of user-item recommendations to assist in making new recommendations.

There are two main methods of performing collaborative filtering:

Neighborhood-Based Collaborative Filtering, which is based on the idea that we can either correlate items that are similar to provide recommendations or we can correlate users to one another to provide recommendations.

Model Based Collaborative Filtering, which is based on the idea that we can use machine learning and other mathematical models to understand the relationships that exist amongst items and users to predict ratings and provide ratings.

In this notebook, I will be working on performing neighborhood-based collaborative filtering. There are two main methods for performing collaborative filtering:

User-based collaborative filtering: In this type of recommendation, users related to the user I would like to make recommendations for are used to create a recommendation.

Item-based collaborative filtering: In this type of recommendation, first I need to find the items that are most related to each other item (based on similar ratings). Then I can use the ratings of an individual on those similar items to understand if a user will like the new item.

In this notebook I will be implementing user-based collaborative filtering. However, it is easy to extend this approach to make recommendations using item-based collaborative filtering. First, let's read in our data and necessary libraries.
