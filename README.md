# Anomaly-Detection-and-Recommender-Systems
In this repository I implemented the anomaly detection algorithm and apply it to detect failing servers on a network. In the second part, I used collaborative filtering to build a recommender system for movies.

ex8data1.mat - First example Dataset for anomaly detection
<br>ex8data2.mat - Second example Dataset for anomaly detection
<br>ex8_movies.mat - Movie Review Dataset
<br>ex8_movieParams.mat - Parameters provided for debugging
<br>multivariateGaussian.m - Computes the probability density function for a Gaussian distribution
<br>visualizeFit.m - 2D plot of a Gaussian distribution and a dataset
<br>checkCostFunction.m - Gradient checking for collaborative filtering
<br>computeNumericalGradient.m - Numerically compute gradients
<br>fmincg.m - Function minimization routine (similar to fminunc)
<br>loadMovieList.m - Loads the list of movies into a cell-array
<br>movie_ids.txt - List of movies
<br>normalizeRatings.m - Mean normalization for collaborative filtering
<br>estimateGaussian.m - Estimate the parameters of a Gaussian distribution with a diagonal covariance matrix
<br>selectThreshold.m - Find a threshold for anomaly detection
<br>cofiCostFunc.m - Implement the cost function for collaborative filtering
