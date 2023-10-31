# CryptoClustering_reja
Module 19 Challenge


In this challenge, you’ll use your knowledge of Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

## Files ##

Downloaded the following files to get started:

[Module 19 Challenge files](https://bootcampspot.instructure.com/courses/3819/assignments/56654?module_item_id=1000905)

## Instructions ##

1. Renamed the Crypto_Clustering_starter_code.ipynb file as Crypto_Clustering.ipynb.

2. Loaded the crypto_market_data.csv into a DataFrame.

3. Get the summary statistics and plot the data to see what the data looks like before proceeding.


## Data Preparation ##

- Used the **StandardScaler()** module from **scikit-learn** to normalize the data from the CSV file.

- Created a DataFrame with the scaled data and set the "coin_id" index from the original DataFrame as the index for the new DataFrame.

   - The first five rows of the scaled DataFrame appeared as follows:
 
## Find the Best K-value  ##

- Discovering the optimal K value for clustering cryptocurrencies was accomplished by analyzing the original scaled data frame, and the result indicated that K=4 is the most suitable choice.
- Following this determination, the K-means algorithm was utilized to group cryptocurrencies into distinct clusters.

 
## PCA (Principal Component Analysis) and K-value ##

- Conduct a Principal Component Analysis (PCA) to reduce the features to three principal components and determine the total explained variance, which is calculated to be 0.8950316570309841. 
- Subsequently, establish the optimal K value for clustering after PCA, with the best K value identified as 4.
- Finally, employ the K-means algorithm to cluster cryptocurrencies following the PCA dimensionality reduction.

## Findings  ##

