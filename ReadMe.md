This is the practice of K-Nearest Neighbours Algorithm

K - Means Clustering is the unsupervised machine learning algorithm. 

# Implementation of KNN

In KNN algorithm, we group the data into different clusters or catergories based on the value of K. One cluster tells us that the data points possess similar properties.
Let us understand with the example of k=2

Steps
 - Lets take two centriods randomly
 - Calculate the distance of ponits from those two centriods. The data point is assigned to its nearest centriod.
 - Now again calculate the mean of centriods. And again adjust the centriod and perform the step2. 
 - The above step is performed until we didn't see any change in data points
 - Now, there are two clusters with the data

We will do the same for every value of K and we can select the best value of k using elbow method.

*Elbow Method* tells that if we can see the steep decline of variation, that is best value of K
Here, variation = (centriod - x)**2

# Prediction

Now the new data point came and how you will tell for which cluster the datapoint belongs?

Now based on the value of K, we will take the k-nearest neighbours. Now we will return the mode of the values.

Practical
- Implemented with Iris Dataset
