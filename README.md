# Mod-4-Project

## Predicting The Next Movie You Should Watch

Nowadays many consumers find movies to watch based on advertisements or word of mouth. Utilizing data science, we are able to build algorithms to predict movies which will correlate more closely to the consumer. Rather than a consumer having to hear about a movie from a neighbor or friend, the moment they are done watching a similar film on Netflix, with the correct recommendation system in place, we can recommend a similar movie for them to watch.

## Data Cleaning, EDA, Feature Selection and Feature Engineering

Our team was thrilled to see how clean this dataset was. It is a rare occasion to have dataset of over 100,000 so clean. We initially looked at the distribution of the Average Rating Score and Number of Movies, as well as the Ratings and the Number of Review.



# INSERT PICTURE 





## Engines

Utilizing Surprise, which is a Scikit building and analyzing recommender system, we were quickly able to build a system where we would be able to predict a user’s rating, as well as most importantly, recommend specific movies for them.

Even though this works well, we decided to dive deeper into the system and create our own.

## Our New Recommendation System

We chose a user from over 100,000 rating entries and compared his/her ratings to potential movies he/she might enjoy. Using the SVD method (since it performed the best compared to Knns), we were able to accurately predict five additional movies based on genre for them to enjoy. 

We were able analyze and understand this using the RMSE and MAE score of Knns and SVD models. Understanding that the lower the RMSE and MAE scores are, the better performance, we were able to use SVD while building our own recommendation system.

## Conclusion 

Our recommendation system successfully predicted the top five suggestions for our test consumer. We were able to utilize the given dataset and use the ratings, genre, and MovieId to directly correlate additional movies pertaining to the test user. SVD was the model we used successfully for this.

Link to our presentation: https://docs.google.com/presentation/d/1Ay-GE_9JvIzQfznrwhSda6TfjU0ubFkhJNdlA5TKugY/edit#slide=id.g9746472248_0_523
