# Clustering
clustering techniques to a real-world dataset.

Project Overview

This project is based on clustering the Iris dataset using two unsupervised machine learning algorithms
KMeans Clustering
Hierarchical Clustering

The main aim is to group the Iris flowers into different clusters and compare the results of both methods


The following Python libraries were used:

Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
SciPy
Jupyter Notebook

Data Preprocessing

First the Iris dataset was loaded and checked for missing values. There were no missing values in the dataset.
The features were then standardized using StandardScaler because clustering algorithms use distances between data points.
The scaled data was used for both KMeans and Hierarchical Clustering


What is KMeans Clustering?


KMeans is an unsupervised machine learning algorithm that is used to divide data into a certain number of groups, which are called clusters

The basic steps of KMeans are:
It first selects some points as the **cluster centers (centroids)
Each data point is then assigned to the nearest centroid
After that, the centroids are recalculated based on the assigned data points
These steps are repeated until the clusters become stable and there are no major changes
For the Iris dataset we can use 3 clusters because the dataset contains three different types of Iris flowers

---

Why is KMeans suitable for the Iris dataset?


KMeans is a good choice for the Iris dataset because it contains numerical features like **sepal length, sepal width, petal length, and petal width
Since these values are numerical, we can measure the distance between the data points, which is important for the KMeans algorithm.
The Iris dataset also has three different types of flowers, so using **3 clusters** makes sense for this dataset. KMeans can help us group the flowers based on the similarities in their features.


What is Hierarchical Clustering


Hierarchical clustering is an unsupervised method that groups similar data points and builds a hierarchy of clusters
It starts with each data point as its own cluster, then slowly merges the most similar clusters
This continues until all points form one large cluster

A dendrogramis used to visually show this process



Why is Hierarchical Clustering suitable for the Iris dataset?

Hierarchical clustering is suitable for the Iris dataset because it contains numerical features such as sepal length, sepal width, petal length, and petal width These features can be used to find similarities between different flowers.
Another advantage is that we can use a **dendrogram** to easily visualize how the different data points are related to each other and how they form clusters.



Conclusion

Both KMeans and Hierarchical Clustering were successfully applied to the Iris dataset
KMeans provided a simple way to divide the flowers into three clusters
Hierarchical Clustering helped us understand the relationship between the data points using a dendrogram
Overall, both methods were able to find meaningful groups in the Iris dataset

