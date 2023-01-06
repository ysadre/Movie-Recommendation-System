# Movie Recommendation System (Content-based, item-based and user-based collaborative filtering)
This project is a movie recommendation system that uses a combination of content-based, item-based, and user-based collaborative filtering techniques to make personalized recommendations to users. 

### Data
The system is trained on the open "The Movies Dataset" on Kaggle.

### Techniques
The recommendation system uses a combination of the following techniques:

Content-based filtering: This technique involves recommending movies to a user based on the attributes of the movies they have liked in the past. For example, if a user has liked action movies with a high budget in the past, the system might recommend similar high budget action movies to them.

Item-based collaborative filtering: This technique involves recommending movies to a user based on their similarity to other movies that the user has liked. For example, if a user has liked movies A and B, and movie C is similar to movie A, the system might recommend movie C to the user.

User-based collaborative filtering: This technique involves recommending movies to a user based on the ratings of other users who have similar tastes to the user. For example, if a user has similar ratings to other users who have liked movie D, the system might recommend movie D to the user.

### Results
The recommendation system achieved a root mean squared error (RMSE) of 0.8963 on the test data. This indicates that the predictions made by the system are, on average, less than 0.8963 away from the true ratings given by users.
