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
After applying the above functions, two clusters are returned, which differ in price movement dynamics (the first cluster contains coins whose dynamics are similar to bitcoin, while the second cluster stores coins with different dynamics).

Cluster with coins whose price dynamics is similar to that of bitcoin.

![image](https://github.com/user-attachments/assets/cf68dfe8-787d-4b60-8256-9f2f973e3990)

Cluster with coins whose price dynamics do not coincide with bitcoin dynamics.

![image](https://github.com/user-attachments/assets/759fdfda-0823-4247-9d3f-35c70187956e)


