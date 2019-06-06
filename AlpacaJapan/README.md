# Alpaca Japan Test

by Parul Yamini,<br />
parul.yamini@oracle.com,<br />
6th June 2019<br />

### Introduction To K-Means Clustering
K-means clustering is a type of unsupervised learning, which is used when you have unlabeled data (i.e., data without defined categories or groups). The goal of this algorithm is to find groups in the data, with the number of groups represented by the variable K. The algorithm works iteratively to assign each data point to one of K groups based on the features that are provided. Data points are clustered based on feature similarity. The results of the K-means clustering algorithm are:

The centroids of the K clusters, which can be used to label new data
Labels for the training data (each data point is assigned to a single cluster)


I have implemented code on Jupyter notebook in anaconda environment.
Took a list of values converted into array and using kmeans elbow method tried finding out optimal number of clusters. 

Visualized the resultant centroids,clusters and the points lying in it.

Clusters id are 0,1,2 i.e total 3 clusters in this situation I get and 
Centroid coordinates as [50.01724138 50.03448276] ,[25.1428571419.52380952] and 
[25.0952381  80.04761905]


