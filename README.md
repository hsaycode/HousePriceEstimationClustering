# HousePriceEstimationClustering
PClubTask1:House Price Estimation and Clustering Challenge

My approach to the predict the house trend is:
1. I read in the testing and training csv files
2. I chose a few column attributes which seemed relevant
3. Then i encoded the column attributes which had non numerical values so as to train the model
4. Then i created the training and testing arrays
5. I preproccessed the arrays to standardize the data
6. Then i split the training data into train test sets to train the model
7. The using KNN i fit the training data into the ML model and predicted the values
8. Then I used the r2 score to determine the accuracy of the model
9. I found out the most suitable value of k neighbors
10. Ran predicitions of the provided test data frame
11. Using Clustering i clustered the training data into 3 clusters and visualized the clusters using multiple plots like scatter plot and 3D plot
12. Then using gradio i deployed the user interface


Insight and Observation:
1.The first scatter plot highlights the centroids of the 3 clusters and marks the three clusters in different colours

2. The SalePrice vs LotArea scatter plot shows that the SalePrice doesnt increase with increase in lot area abd hence the sale price depends on various other factors of the house.

3. The 3D plot offers a dynamic comparison between the lotarea, lotfrontage and the saleprice
