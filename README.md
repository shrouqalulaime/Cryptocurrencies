# Cryptocurrencies

## Project Overview:

This project aims to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment. Four main steps were performed during the technical analysis:
1. Preprocessing the Data for principal component analysis (PCA)
2. Reducing Data Dimensions Using PCA
3. Clustering Cryptocurrencies Using K-means
4. Visualizing Cryptocurrencies Results

## Analysis Summary:

The raw dataset has six features: coin name, algorithm, trading, proof type, total coins mined, and total coin supply, with 1144 records. After cleaning the data, the size was reduced to 685 rows. To simplify the clustering results, PCA is used to reduce data dimensionality to three features. K-means clustering is used to group cryptocurrencies' reduced dimensionality data. Based on the elbow method, the optimal cluster number is four clusters.

<img width="779" alt="Screenshot 2023-02-04 at 5 10 06 PM" src="https://user-images.githubusercontent.com/48078471/216796447-7b3514ce-0e68-422f-ae98-37fc895ad248.png">

The clustering results of k-means clustering are shown below:

<img width="833" alt="Screenshot 2023-02-04 at 5 11 36 PM" src="https://user-images.githubusercontent.com/48078471/216796472-a3d464ad-dd9a-4dfa-be12-bc0f721928c8.png">

<img width="717" alt="Screenshot 2023-02-04 at 5 13 21 PM" src="https://user-images.githubusercontent.com/48078471/216796518-6c044926-d60f-40ad-bd98-4b22c8064dec.png">

