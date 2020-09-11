# Mod-4-Project

## Predicting The Next Movie You Should Watch

Nowadays many consumers find movies to watch based on advertisements or word of mouth. Utilizing data science, we are able to build algorithms to predict movies which will correlate more closely to the consumer. Rather than a consumer having to hear about a movie from a neighbor or friend, the moment they are done watching a similar film on Netflix, with the correct recommendation system in place, we can recommend a similar movie for them to watch.

## Data Cleaning, EDA, Feature Selection and Feature Engineering

The dataset of movies that was used was the MovieLens Latest Dataset from the GroupLens research lab at University of Minnesota. Our team was thrilled to see how clean this dataset was. It is a rare occasion to have dataset with over 100,000 observations be so clean. We initially looked at the distribution of the Average Rating Score and Number of Movies, as well as the Ratings and the Number of Review.


![Alt text](https://github.com/jbillet/Mod-4-Project/blob/master/Distribution%20of%20Movies%20by%20their%20Avg.%20Rating.png)



![Alt text](https://github.com/jbillet/Mod-4-Project/blob/master/User%20Ratings%20Given%20for%20Movies.png)



## Engines

Utilizing Surprise, which is a Scikit building and analyzing recommender system, we were quickly able to build systems with knns and SVD where we would be able to predict a user’s rating, as well as most importantly, recommend specific movies for them. The model in which we used SVD ended up providing more accurate predictions than the knns model.

After testing our models, we decided to dive deeper into the system and create our own recommendation system.


## Our New Recommendation System

We chose a user from the movie dataset and compared his/her ratings to potential movies he/she might enjoy. Using the SVD method (since it performed the best compared to Knns), we were able to accurately predict five additional movies based on average ratings and genre for them to enjoy.
We were able analyze and understand this using the RMSE and MAE score of Knns and SVD models. Understanding that the lower the RMSE and MAE scores are, the better performance, we were able to use SVD while building our own recommendation system.


## Conclusion 

Our recommendation system successfully predicted the top five suggestions for our test consumer. We were able to utilize the given dataset and use the ratings, genre, and MovieId to directly correlate additional movies pertaining to the test user. SVD was the model we used successfully for this.

Link to our presentation: https://docs.google.com/presentation/d/1Ay-GE_9JvIzQfznrwhSda6TfjU0ubFkhJNdlA5TKugY/edit#slide=id.g9746472248_0_523
