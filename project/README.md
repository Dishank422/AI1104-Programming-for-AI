This project tries to build a system for giving anime recommendation using collaborative filtering.

The dataset used is rating_complete.csv taken from kaggle. It can be found at 

"https://www.kaggle.com/hernan4444/anime-recommendation-database-2020?select=rating_complete.csv"

First, the dataset is reduced in size using data_size_reduction.ipynb
Then knn.ipynb and knn_with_svd.ipynb are used to give recommendations

knn.ipynb implements K nearest neigbour algorithm on the data

knn_with_svd.ipynb implements a the knn algorithm but on data of lower dimensionality. The dimensions are reduced using Singular Value decomposition

knn.ipynb works better than a random recommender but is still not good enough
knn_with_svd.ipynb has same performance as that of aa random recommender

For evaluation purposes, please consider only knn.ipynb. Subsequently, I have not written comments in knn_with_svd.ipynb. 
