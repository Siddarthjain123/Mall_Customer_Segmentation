
# Mall_Customer_Segmentation
 ## Title : Mall Customers Segmentation into multiple groups 
 
 ## Data : 
 Data has been taken from kaggle dataset Mall Customer Segmentation Data, corresponding csv file is present in Data folder of this repo. Link to download data: https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python/download
 
 ## Overview :
 The purpose of this project is to cluster customers in a mall into multiple groups on the basis of age, spending capability, spending score etc. This can provide us useful insights into what are the requiremetns of each group and accordingly marketing strategies and policies can be built to optimize spending score of the customers. 
 
## Clustering Algorithms Implemented
Elbow technique is used to find optimal number of customers and clusters are generated using K-means clustering.

Agglomerative Hierarchial is used for generating clusters, optimal number of clusters is obtained using Dendogram method.

DBSCAN stands for density-based spatial clustering of applications with noise. It is able to find arbitrary shaped clusters and clusters with noise (i.e. outliers). The main idea behind DBSCAN is that a point belongs to a cluster if it is close to many points from that cluster.

 
 ## Summary 
 
 
 Executed Data Visualization (Histogram, Pie Chart, Box Plot) to get an understanding on the input features
 
 Applied KMeans, Agglomerative Hierarchical Clustering and DBSCAN algorithm to cluster the data points
 
 Performed Elbow Technique , Silhouette Score and Davies-Bouldin techniques to find number of clusters which is equal to 5.
