# KNN-Regression-in-R

The concept of KNN regression model is to identify the ‘K’ nearest
neighbours that are closest to the test data  and compute the output/response   based on the response values of its identified
‘K’ neighbours. The factor that helps to estimate the accuracy and the
flexibility of the model is the “Number of Nearest Neighbours: K” and the “Mean
squared error”.

In this R program, kNN regression is performed with different k values k = 2, 5, 10, 20, 30, 50 and 100.

The K value with the most minimum test MSE is considered as the best statistical model for the dataset used. For the above test data, K = 30 gives the minimal test MSE of 17.94852. So K=  30 can be considered as the Best K value as it gives the best statistical model.


Output Plots for Reference:


1.Least Value for Test MSE:

![image](https://user-images.githubusercontent.com/68840596/120881458-4a71e580-c625-11eb-9256-1a14aa2db275.png)



2.Graph Showing Train Dataset and Test Dataset for best KNN (k=30):
![image](https://user-images.githubusercontent.com/68840596/120881330-5c06bd80-c624-11eb-92d5-f5ff83d22633.png)

3.Graph Showing Train, Test and Estimation of Train Dataset for best KNN (k=30):
![image](https://user-images.githubusercontent.com/68840596/120881364-a5570d00-c624-11eb-925e-10a520264197.png)
