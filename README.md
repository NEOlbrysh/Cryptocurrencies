# Cryptocurrencies


Cryptocurrencies analysis with unsupervised machine learning


The focus of this project was to use unsupervised machine learning to examine cryptocurrency data. The following steps were taken:

- The data was first preprocessed by being cleaned, encoded, and scaled to work with the algorithms more appropriately.
- We then used Principle Component Analysis (PCA) to reduce the dimensions of the dataframe, for further analysis.
- The K-means algorithm was then used to create an elbow curve plot. This allowed us to find the best value for k, and thus the best number of clusters for the available data. 


![Crypto-Elbow](https://user-images.githubusercontent.com/103701561/187462562-dd292860-7775-472c-bd0a-c9862ecdf36a.png)


- Lastly, we visualized the data. First, we created a 3D scatter plot using the PCA data. Then we transformed data for "Total Coin Supply" and "Total Coins Mined", which we then used to create a 2D scatter plot. 


![Crypto-3D](https://user-images.githubusercontent.com/103701561/187462543-21963083-6956-41b7-813f-43e36d368807.png)



![Crypto-Scatter](https://user-images.githubusercontent.com/103701561/187462610-32798f68-cc55-4349-812b-cd2b6de43921.png)
