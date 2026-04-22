In this assignment, the K-Nearest Neighbors (KNN) algorithm was implemented to classify data based on similarity between instances. The dataset was loaded into a pandas DataFrame and explored to understand its structure.

Before applying the model, feature scaling was performed using StandardScaler to normalize the data. Then, the dataset was split into training and testing sets using train_test_split.

The KNN model was trained and evaluated using a confusion matrix and classification report. To find the optimal value of K, the elbow method was applied by testing multiple values from 1 to 40 and calculating the error rate for each value.

A plot of error rate versus K was generated, and based on the results, the best value of K was selected (K = 31). The model was then retrained using this value, which improved the overall performance.

🎯 Conclusion

This assignment shows that choosing the right K value is very important. Small K values may lead to overfitting, while large values may reduce accuracy. The elbow method helps in finding the best balance.
