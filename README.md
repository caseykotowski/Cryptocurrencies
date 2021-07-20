# Cryptocurrencies
Unsupervised machine learning for cryptocurrency choices

## Purpose

I am working with an investment bank, and they want to start working with cryptocurrencies. 
They're not sure where to start, so they brought me on to group tradable currencies into potential investment groups. I chose to work with unsupervised learning algorithms to group these coins

## Method
* Preprocess data for PCA
  * I removed unncecessary columns, and rows with null values 
* Use PCA to reduce data dimensions
  *  Principal component analysis takes all factors and reduces to the desired number of dimensions
  *  I reduced to three dimensions 
* Cluster with K-means
  * I first plotted the inertia of the model with an elbow plot to find the ideal number of clusters
  * Then I applied the k-means algorithm to make cluster predicitons 
* Visualize the Results
  * I created a 3D plot of the clusters of coins
  * Then I scaled the data to show how the clusters appear when comparing coin supply vs coins mined
