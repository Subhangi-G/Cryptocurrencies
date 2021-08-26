# Cryptocurrencies

## Overview of Project 

### Purpose

The purpose of this project is perform an analysis on the cryptocurrencies that are on the trading market, and group them to create a classification system, which can be used, by the firm Accountability Accounting, to offer as a cryptocurrency investment portfolio to their customers.

### Resources used
- Data : Resources/crypto_data.csv
- Software : scikit-learn 0.24.1, Numpy 1.20.1, Pandas 1.2.4, hvplot 0.7.3, Plotly 5.1.0

## Summary
The data given was loaded into a DataFrame and viewed. The image of the initial data is shown below.\
(image of the initial dataframe)

Data was first pre-processed. Cryptocurrencies that are being traded, and have a working algorithm were chosen. Those with missing information were removed and then only coins that have been mined were kept. Variables with text-features were changed into columns holding numeric values.\
Data was scaled, and data dimensions were reduced to three principal components by applying PCA.

(imgae of PCA df)

A clustering algorithm, K-Means, was used to group the different cryptocurrencies.\
Below is the graph of the elbow curve showing the best value of K as 4.

(graph showing the elbow curve to find the best value of K)

Below is the picture of the DataFrame with the predictions of the K clusters for the cryptocurrencies.

(clustered df picture)

Below is a picture of the clusters.

(3D picture)

A table of the tradable cryptocurrencies is given below. There are a total of 532 tradable cryptocurrencies.

(Pic of table)

Scatter plot of the cryptocurrencies.

(Plot of scatterplot)