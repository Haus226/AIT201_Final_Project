# AIT201_Final_Project
Final Project of course AIT201 Applied Machine Learning using dataset (Boston Airbnb) https://www.kaggle.com/datasets/airbnb/boston
- The aim of our project is trying to solve three problems with the given Boston Airbnb dataset from two aspects, the hosts and the travellers. The problems are listed out below:
    - Help the host to decide the price based on the features of their listings provided
    - Help the travellers to choose the listings based on the non-null text features in listings dataset
    - Help the travellers to choose the listings based on the location and also the overall review scores
- We will try some regressors to solve the first problem and find the best regressor while k-mean algorithm to solve the second and the third.
- So basically, the first problem needs to solve with supervised learning model while the second and third can be solved using unsupervised learning
## Price Prediction
- Task : Decide the price based on the features of the listing
- Performance : rmse between predicted values and true values
- Experience : A merged dataset after preprocessing listings.csv, reviews.csv, calendar.csv
- For detail, read the [Price_Prediction.ipynb](AIT201/Price_Prediction.ipynb) carefully
## Clustering the listings based on non-null text features
- Task : Clustering the listings on text
- Performance : Use some metrics provided in sklearn which can measure the performance of K-means learning without ground truth
- Experience : Non-null text features data in listings dataset
- For detail, read the [Clustering_Text.ipynb](AIT201/Clustering_Text.ipynb) carefully
## Clustering based on latitude, longitude and overall review scores
- Task : Clustering the listings based on latitude, longitude and overall review scores
- Performance : Use some metrics provided in sklearn which can measure the performance of K-means learning without ground truth
- Experience : Latitude, longitude and review scores in listings dataset
- For detail, read the [Clustering_Latitude_Longitude.ipynb](AIT201/Clustering_Latitude_Longitude.ipynb) carefully


