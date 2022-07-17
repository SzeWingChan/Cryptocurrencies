# Cryptocurrencies

## Background
A prominent investment bank is considering to offer a new cryptocurrency investment portfolio for the customers.  Since there are many cryptocurrencies in the market, we are tasked to review the options available and how they could be grouped accordingly.  

## Description
- Deliverable 1: Preprocessing the Data for PCA
Read the csv file as a DataFrame and preprocess the data so it is ready for Principal Component Analysis (PCA).

- Deliverable 2: Reducing Data Dimensions Using PCA
Apply PCA algorithm to reduce dimensions of the preprocessed DataFrame to three principal components. 

- Deliverable 3: Clustering Cryptocurrencies Using K-means
Use the K-means algorithm to create an elbow curve and identify the best value for K.  Run the K-means algorithm to predict the K clusters for the cryptocurrencies’ data.

- Deliverable 4: Visualizing Cryptocurrencies Results
Create scatter plots with Plotly Express and hvplot to visualize the grouping of cryptocurrencies.

## Results
- After reducing the data dimension by employing PC and using the elbow curve to find the best value for K, it is revealed that there are 4 groups of cryptocurrencies in the market.
    ![4Clusters]()

- However, in order to offer a new investment portfolio, it is also important to check if the currency is available in the market.  Therefore, a scatter plot is used to reveal the availability of individual currency.  Most of the Class 2 and 3 cryptocurrencies are still available for mining and these could be the potential cryptocurrencies to be included in the new investment portfolio. 
    ![Cryptocurrencies]()