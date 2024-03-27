# CryptoClustering
The repository contains code for the following requirements:

Use the StandardScaler() module from scikit-learn to normalize the data from the CSV file in the Resources folder.
Use the elbow method to find the best value for k means algorithm by plotting a line chart with all the inertia values
cluster the cryptocurrencies for the best value for k on the original scaled data
Create a scatter plot using hvPlot as follows:
Set the x-axis as "price_change_percentage_24h" and the y-axis as "price_change_percentage_7d".
Color the graph points with the labels found using K-means.
Add the "coin_id" column in the hover_cols parameter to identify the cryptocurrency represented by each data point.

Using the original scaled DataFrame, perform a PCA and reduce the features to three principal components.
Use the elbow method on the PCA data to find the best value for k
cluster the cryptocurrencies for the best value for k on the PCA data
Create a scatter plot using hvPlot as follows:
Set the x-axis as "PC1" and the y-axis as "PC2".
Color the graph points with the labels found using K-means.
Add the "coin_id" column in the hover_cols parameter to identify the cryptocurrency represented by each data point.
