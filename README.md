# Movies and Jokes
Developed in the Pattern Recognition in Data Mining course by: Stephanie Riff and Kevin Reyes.
## Objectives
- Recommend movies and jokes to a user based on their preferences.
- Apply collaborative filtering recommendation methods based on users and items.
- Assess how many nearby neighbors to use to get a good recommendation.
- Compare user-based and item-based collaborative filtering methods.

## Description
Movie and joke recommender system using collaborative filtering methods based on users and items.

## Conclusions
- In user-based collaborative filtering methods, if the user has watched known movies, they will receive known movie recommendations. As for jokes, it is verified that if the user likes jokes associated with professions, then more users related to professions will be recommended.
- Item-based collaborative filtering may perform better in real systems where the number of items is << than the number of users.
- It is very important to consider the bias of each user when making recommendations.

## Technology stack
- Pandas.
- Numpy.
- Scikit-learn.