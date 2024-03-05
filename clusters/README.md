The dataset is loaded using the pandas library and displayed with a few analysizing here and there so as  to provide an initial understanding of the data set.Data visualization is also used not only to view how the initial clusters are subdivided but also to determine the number of clusters to create based on the values of the highest and the lowest value.

A K-Means clustering model is created using the scikit-learn library. The model is set to create 11 clusters (n_clusters=11) with a maximum of 100 iterations

The K-Means model is trained on the dataset using the fit method.

Each data point is assigned a cluster label based on the trained model using the predict method. The cluster labels are added as a new column named "Cluster" in the dataset.

A scatter plot is created to visualize the clusters formed by the K-Means algorithm. Each cluster is assigned a unique color for clarity.