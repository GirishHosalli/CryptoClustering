# Crypto Clustering 

### In this challenge K-means algorithm and Principal COmponent Analysis (PCA) is used to classify crypto currencies price fkuctuations across various timeframes. Specifically, it will examine price changes over intervals spanning 24 hours, 7 days, 30 days, 60 days, 200 days, and 1 year.

### It will use ***StandardScalar()*** module from ***scikit-learn*** to normalize the data from CSV file. 
### Then it will get the best K value for using the original scaled dataframe. This will be done by drawing a line chart of inertia values for cluster size from 1 to 10. 
### Using KMeans model get predicted cluster values for original scaled dataframe. 
### Observe clusters by drawing a line plot for above dataframe.
### Then optimize the original number of features in original dataframe. This will return a dataframe with specified number of columns(features).
### For PCA optimized dataframe find the best k values using PCA analysis
### Cluster Cryptocurrencies with K-Means Using the PCA Data
### Create scatter plot of PCA1 vs PCA2 data
### Then finally it will determine the weights of each feature on each Prinical Component. 

