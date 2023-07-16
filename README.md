# CryptoClustering Challenge 19- Use Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

# Starter code was provided, which created df_market_data and a chart indicating price changes over the different intervals for each currency. The data was scaled, then a new column of "Coin_id" was added and indexed creating df_scaled_df.

# Using cluster=4, a KMeans prediciton model was used to create 'k_predicitons' array. 

# A 'predictions_df' was then created from the 'df_market_data' and a new column for 'clusters' was added. The resulting prediction clusters can be seen in 'Predictions - KMeans Original Data.'

# Clusters were then optimized using Principal Component Analysis. A PCA instance was created with n-clusters=3 then acted upon by fit_transform to create an array. Total Explained Variance = 0.895.

# 'df_crypto_pca' dataframe was created and a column of 'coin_id' was adedd and indexed.THe values of k were calculated and visualized in'PCA Elbow Curve - KMeans.' A prediction array was created and groupings are seen in 'Predictions - PCA Data.'



