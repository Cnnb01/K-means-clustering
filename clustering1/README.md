**K-MEANS**
The notebook shows a model that analyses movie reviews from 5 usesrs and uses these reviews to classify other users' likes and preferences such that the later users are clustered into the same clusters depending on their reviews.

The model is first fed data from 6 users with their different ratings on different movies.
The movies are then listed out and a dataframe is created displaying the different users, the movies, and their ratings to each of the movies.
A library called cluster is then imported from skitlearn which will help in clustering the users based on their 

To prepare the data for clustering, the 'User' column is dropped as it is not needed for the analysis. The remaining ratings become the input features for the K-Means clustering algorithm.

The scikit-learn library's K-Means algorithm is employed to cluster users based on their movie ratings. The algorithm is initialized with two clusters then the data is fit into k_means. The attribute .labels_ is passed to the variable labels which  returns an array of labels(array([1, 1, 1, 0, 0, 0], dtype=int32)), where each element corresponds to a user in the dataset, indicating the cluster to which they belong. 

We then move to Predicting whereby the trained model can then predict the cluster for new users based on their movie ratings. A set of new users with their movie preferences is introduced to showcase this prediction.

