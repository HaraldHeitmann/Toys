#Playing with Movielens 
A subset of Movielens dataset(info about the dataset in README file).

The ipynb file uses pandas, numpy, matplotlib and sklearn libraries.

To use K-means, we use One hot encoding (OHE) on the genres features of each movie. 
Then to each user we assign a vector ussing some function of the ratings the  user has given, to the OHE space,
and there we use K-means algorithm to cluster the users. 
Finally, we find the movies most and best rated from each cluster, which might be good racommendations to users of that cluster.

An important note is that the data has not been cleaned, nor separated on a parameter setting/testing/training sets,
so there isn't a good way to evaluate the quality of the method applied.

