# Machine-Learning-Algorithm
Build various ML algorithm from scratch in Python

To understand the the basics of machine learning algorithm, I have build this repository to upload the ML algorithms on different datasets. While building this algorithm, the performance of the model has been taken care as compared to running of model by using package in Python.

The description of the working of ML models are as follows:

# KNN:
KNN (k-Nearest Neighbors) model is an algorithm that captures all the provided data and predicts the new data based on a specific similarity criterion. This similarity criteria can be calculated in terms of minkowski distance, euclidean distance or manhattan distance. 
To build the whole algorithm of KNN model, knn_model function is made which has 2 input parameters as k-value and p-value. It has been done by following procedure:
1. Counter variables is initialized to count the number of rightly predicted entries
2. Each entry of testing data is picked and compared with each entries of training dataset to find the minkowski distance between them
3. Minkowski distance has been sorted along with heart_condition of training dataset, leading to fetching the minimum distance for more similarity between the two vectors
4. Majority of heart_condition values is calculated, and its condition is predicted and compared with actual value in testing set
5. Accuracy and confusion matrix is being formed from the values of counter values of count_TP, count_TN, count_FP and count_FN
6. After building the whole algorithm, knn_model function has been called with various combinations of p-value and k-value
7. Applying KNN model using library of python for k=3 and p=1 using the python library
