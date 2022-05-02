# 18_Cryptocurrencies
Module 18 Unsupervised Machine Learning Challenge


## Overview
To show understanding of unsupervised machine learning, a report was created that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for investment.

## Deliverable 1 - Preprocessing the Data for PCA
- `crypto_df` DataFrame created 
  - with only cryptocurrencies that are being traded listed
  - rows with null values removed
  - rows with no coing being mined removed
  - The `CoinName` column is dropped
- `crypto_names_df` Data Frame Created storing Coin Names
-  `X` DataFrame created 
    - with variables for the text features
    - features standardized using the StandardScaler `fit_transform()` function

## Deliverable 2 - Reducing Data Dimensions Using PCA
- PCA algorithm reduces the dimensions of the `X` DataFrame down to three principal components
- The `pcs_df` Data Frame created

## Deliverable 3 - Clustering Cryptocurrencies Using K-means
- An elbow curve is created using `hvPlot`
- Predictions are made on the K clusters of the cryptocurrencies' data
- `clustered_df` DataFrame created adding predictions to the other cryptocurrency data

## Deliverable 4 - Visualizing Cryptocurrencies Results
- Clusters are plotted on a 3D scatter plot
- A sortable table with tradeable cryptocurrencies is created
- `plot_df` DataFrame created with cryptocurrency information and the scaled data
- A `hvplot` scatter plot is created
