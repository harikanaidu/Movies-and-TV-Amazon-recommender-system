# Movies-and-TV-Amazon-recommender-system
Recommender system based on Amazon product reviews using Collaborative filtering and hyperparameter tuning techniques

Dataset page: https://cseweb.ucsd.edu/~jmcauley/datasets/amazon_v2/ Amazon Review Data(2018)
As part of the final class project for CAP-5778, we have designed a collaborative filtering recommender system using Pivoting and correlation table, Singular Value Decomposition algorithm and tuning its parameters to obtain the optimised performance measured in MAE and RMSE.

Pivoting and Matrix Factorisation:
To perform matrix factorisation, it's important to represent the users and items in a lower dimensional latent space. This can be achieved with the help of a pivot table, where unique users are represented by rows, unique items as columns and values representing the ratings for those items. This way, we can decompose the user-item interaction matrix and understand the underlying relationships between users and items.
One popular matrix factorisation technique is Singular Value Decomposition(SVD).

Upon training the fine-tuned model, we have then obtained the top-10 unseen movies/TV items for each user based on ratings given by similar users to movies.
