# CryptoClustering
Module 19 Challenge

In this challenge, Python and unsupervised learning  was used to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

## Instructions
The work is divided into the following subsections:

1. Prepare the Data
2. Find the Best Value for k Using the Original Scaled DataFrame
3. Cluster Cryptocurrencies with K-means Using the Original Scaled Data
4. Optimise Clusters with Principal Component Analysis
5. Find the Best Value for k Using the PCA Data
6. Cluster Cryptocurrencies with K-means Using the PCA Data
7. Visualise and Compare the Results

## Results and summary

Both the complete data sets and the Principal Component Analysis manage to cluster the coins. About 89.5% of the total variance is condensed into the 3 PCA variables. Both of the Elbow Charts are very similar and suggest using 4 clusters. There are 2 coins that fall on their own cluster (namely Celsius-Degree-Token and Ethlend). The rest of the coins fall in one of 2 groups.


![image](/Price_Changes_Coins.png)

![image](/Elbow_Curve_Full.png)

![image](/Elbow_Curve_PCA.png)

![image](/ScatterPlot_Full.png)

![image](/ScatterPlot_PCA.png)

![image](/ScatterPlot_Full_3D.png)

![image](/ScatterPlot_PCA_3D.png)


## Submission

1. Submitted and available in GitHub under https://github.com/lcardsvr/CryptoClustering

2. Jupyter Notebook available in GitHub under https://github.com/lcardsvr/CryptoClustering/blob/main/Crypto_Clustering.ipynb

