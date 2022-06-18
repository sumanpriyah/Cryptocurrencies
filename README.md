# Cryptocurrencies

## Overview of the analysis: 

The purpose of this analysis is to use unsupervised learning by cleaning and processing the data, cluster and reducing the dimensions and reduce the components using PCA, prepare cryptocurrency portfolio for customers. We are helping to
create a report that includes what all cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

## Deliverables

1: Preprocessing the Data for PCA
2: Reducing Data Dimensions Using PCA
3: Clustering Cryptocurrencies Using K-means
4: Visualizing Cryptocurrencies Results


## Summary: 
### 1. First we cleaned the data for PCA. 
All cryptocurrencies that are not being traded are removed
All the rows that have at least one null value are removed
All the rows that have at least one null value are removed
The CoinName column is dropped


![](https://github.com/sumanpriyah/Cryptocurrencies/blob/main/Images/crypto_df.png)


### 2. Reduced the dimensions using PCA
Reduced the dimensions to 3 principal components
Created new dataframe with 3 components

![](https://github.com/sumanpriyah/Cryptocurrencies/blob/main/Images/df%20with%203%20pinciple%20components.png)

### 3. Clustered Cryptocurrencies Using K-means
created elbow curve and found best value for k
Ran the K-means algorithm make predictions of the K clusters for the cryptocurrencies’ data
Merged the dataframes and added the class that holds the predictions

![](https://github.com/sumanpriyah/Cryptocurrencies/blob/main/Images/clustered_df.png)

![](https://github.com/sumanpriyah/Cryptocurrencies/blob/main/Images/Elbow%20curve.png)


### 4. Visualizing Cryptocurrencies Results
Created a 3D-Scatter with the PCA data and the clusters
created scatter plot to visualize the distinct groups that correspond to the three principal components

![](https://github.com/sumanpriyah/Cryptocurrencies/blob/main/Images/3D-scatter.png)

![](https://github.com/sumanpriyah/Cryptocurrencies/blob/main/Images/hvplot_table.png)


![](https://github.com/sumanpriyah/Cryptocurrencies/blob/main/Images/scaled_df.png)

## Conclusion
 There are 4 clusters and from the graph the coins which are close clustered are good to buy, the one are mined.  


![](https://github.com/sumanpriyah/Cryptocurrencies/blob/main/Images/scaled%20hv%20plot.png)


