# K-means-clustering

K-means clustering is one of the simplest and popular unsupervised machine learning algorithms.
A cluster refers to a collection of data points aggregated together because of certain similarities.
Every data point is allocated to each of the clusters through reducing the in-cluster sum of squares.
In other words, the K-means algorithm identifies k number of centroids, and then allocates every data point to the nearest cluster, while keeping the centroids as small as possible.
The ‘means’ in the K-means refers to averaging of the data; that is, finding the centroid.

How it works: 
To process the learning data, the K-means algorithm in data mining starts with a first group of randomly selected centroids, which are used as the beginning points for every cluster, and then performs iterative (repetitive) calculations to optimize the positions of the centroids
It halts creating and optimizing clusters when either:
 -The centroids have stabilized — there is no change in their values because the clustering has been successful.
 -The defined number of iterations has been achieved.
