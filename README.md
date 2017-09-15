# MovieRecommenderSystem


This is a Movie Recommender System which can recommend the most suitable movies to users. Recommender System is a algorithm which can predict the rating of every movie of a user and recommend some high rated movies.

Downloaded a dataset with 100k features and split the dataset into training set and testing set. Trained the dataset using K Nearest Neighbor CF. Used Global Baseline Estimate to improve the drawbacks of KNN CF. Used Matrix Factorization and Stochastic Gradient Descent method to train a model. Added bias parameters into loss function in order to handle biases. Compared and analyzed different methods and concluded that Matrix Factorization model works better than KNN CF.