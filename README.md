# Cryptocurrencies

## Purpose

Data on cryptocurrencies, including the coin name, trading status, total coins mined, and the total coin supply, were obtained to create a classification system using unsupervised machine learning techniques.  To group the currencies, a clustering algorithm was used.

## Results

The data were cleaned to remove untraded currencies, unworking algorithms and unmined currencies along with dropping rows with null values and this information was formatted into a dataframe.  The data were then divided into three principal components and these dimensions were placed into a new dataframe to hold the results.  Then, an elbow curve was created to find the best K value.  The K-means algorithm groups data into clusters that have some similarity to a centroid, which is data point representing the arithmetic means of the the points in a cluster.  The district groups were visualized in two- and three-dimensional scatter plot and a table was generated showing the currently tradable crytocurrencies.
