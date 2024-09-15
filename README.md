# Crypro Clustering
Clustering of cryptocurrencies with binance, Kmean clustering and Time series Kmeans are used in the work

## Implementation Steps

The work starts with importing the main libraries: 

+ numpy
+ pandas
+ matplotlib
+ tqdm
+ tslearn (for work with time series)
+ sklearn

Next, the function coins_data_USDT is implemented to upload cryptocurrency prices from Binance.

The plot_cluster_tickers function to display graphs for each coin. After, the clustering function implements normalization of incoming data using two methods:

+ MinMax
+ Standart

Also, this function does clustering either using a special method for time series clustering, or using the usual KMeans method from the sklearn library. 
