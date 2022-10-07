# Cryptocurrencies

## Purpose

Data on cryptocurrencies, including the coin name, trading status, total coins mined, and the total coin supply, were obtained to create a classification system using unsupervised machine learning techniques.  To group the currencies, a clustering algorithm was used.

## Results

The data were cleaned to remove untraded currencies, unworking algorithms and unmined currencies along with dropping rows with null values and this information was formatted into a dataframe.  The data were then divided into three principal components and these dimensions were placed into a new dataframe to hold the results.  Then, an elbow curve was created to find the best K value.  The K-means algorithm groups data into clusters that have some similarity to a centroid, which is data point representing the arithmetic means of the the points in a cluster.  The district groups were visualized in two- and three-dimensional scatter plot and a table was generated showing the currently tradable crytocurrencies.

The following visualizations did not appear when posting the Jupyter Notebook file on GitHub.  These screen shots show these visualizations:

*Elbow Curve*

![image](https://user-images.githubusercontent.com/106293233/194448926-6d06ba1a-7014-45e5-8f39-9e2d1a9d5d62.png)

*3D-Scatter with the Principal Component Analysis and the Clusters*

![image](https://user-images.githubusercontent.com/106293233/194449150-dfef254a-f065-41c5-a879-a7c47041a6c1.png)

*Tradable Cryptocurrency Table*

![image](https://user-images.githubusercontent.com/106293233/194449317-5cec6833-bd35-4c4b-8134-5b35fd77647b.png)

*Scatter Plot with Total Coins Mined and Total Coin Supply*

![image](https://user-images.githubusercontent.com/106293233/194449549-f74fbacc-993a-41e7-9349-4f17f0a83394.png)
