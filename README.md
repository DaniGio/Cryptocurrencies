# Cryptocurrencies
## Project overview
This project’s goal is to support Accountability Account to analyse the dataset of cryptocurrencies to discover trends to decide if they should or not invest in this new currencies
since bitcoins has increased the price making unaffordable for many new investors

## Resources
Data source: crypto_data.csv

## Summary

After a data set cleaning process, to remove N/As, and zero values, it was created and unsupervised model to understand and learn more about the data.

An Elbow curve was created to identify the numbers of clusters this data set suggests. As image below it is possible to see that 4 or 5 could be a good number of clusters. For this model, it was choose 5.
The idea of clustering is to create groups of data points with similar points.


- ![alt text](
https://github.com/DaniGio/Cryptocurrencies/blob/master/Pics/elbow%20curve.png)

After identifying the number of clusters, k-means was applied with 5 groups. A larger k (number of clusters) creates smaller groups with more granularity, a lower k means larger groups and less granularity.

Results in 3d:
- ![alt text](
https://github.com/DaniGio/Cryptocurrencies/blob/master/Pics/3D%20clusters.png)


Results in 2d:
- ![alt text](
https://github.com/DaniGio/Cryptocurrencies/blob/master/Pics/2d%20cluster.png)


Further investigation is required. Usually unsupervised learning show what it should be analyzed next. It is possible to see that some clusters have a trend. The data is compressed with PCA and it would be interesting to run a supervised learning algorithm to predict more trend.

