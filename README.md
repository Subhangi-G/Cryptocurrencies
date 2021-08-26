# Cryptocurrencies

## Overview of Project 

### Purpose

The purpose of this project is perform an analysis on the cryptocurrencies that are on the trading market, and group them to create a classification system, which can be used, by the firm Accountability Accounting, to offer as a cryptocurrency investment portfolio to their customers.

### Resources used
- Data : Resources/crypto_data.csv
- Software : scikit-learn 0.24.1, Numpy 1.20.1, Pandas 1.2.4, hvplot 0.7.3, Plotly 5.1.0

## Summary
The data given was loaded into a DataFrame and viewed. The image of the initial data is shown below.

![Initial_Table](https://user-images.githubusercontent.com/71800628/131037053-33480c99-7dbc-4330-9ebf-77413355b7aa.png)

Data was first pre-processed. Cryptocurrencies that are being traded, and have a working algorithm were chosen. Those with missing information were removed and then only coins that have been mined were kept. Variables with text-features were changed into columns holding numeric values.\
Data was scaled, and data dimensions were reduced to three principal components by applying PCA.

![PCA_df](https://user-images.githubusercontent.com/71800628/131037341-ad43b682-618d-4168-82a1-c6cdeb392245.png)

A clustering algorithm, K-Means, was used to group the different cryptocurrencies.\
Below is the graph of the elbow curve showing the best value of K as 4.

![Elbow_Curve](https://user-images.githubusercontent.com/71800628/131037482-f7942132-e5b1-4fa2-90d9-b564f06bc6e9.png)

Below is the picture of the DataFrame with the predictions of the K clusters for the cryptocurrencies.

![Clustered_df](https://user-images.githubusercontent.com/71800628/131038130-47f248f0-a144-43a0-88af-ff485cfec4ef.png)

Below is a picture of the clusters.

![3D_plot_cluster](https://user-images.githubusercontent.com/71800628/131037687-aa55747a-c23d-4b5b-aac9-fe5174a95890.png)

A table of the tradable cryptocurrencies is given below. There are a total of 532 tradable cryptocurrencies.

![Table](https://user-images.githubusercontent.com/71800628/131037763-ee4f54ce-6927-4d24-8ce5-60f7792dcf42.png)

Scatter plot of the cryptocurrencies.

![Scatter_Plot](https://user-images.githubusercontent.com/71800628/131037808-7c7d6cc5-ff21-40fc-92cd-ced56c020890.png)
