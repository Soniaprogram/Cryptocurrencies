# Cryptocurrencies

## Purpose


Accountability Accounting, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. Using unsupervised learning and my knowledge of processing data, how to cluster, how to reduce my dimensions, and how to reduce the principal components using PCA, I have created a report including what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment. This report will provide an analysis for clients preparing to get into the cryptocurrency market.

#### Deliverable 1: Preprocessing the Data for PCA
Using my knowledge of Pandas, I preprocessed the dataset in order to perform PCA in Deliverable 2.

#### Deliverable 2: Reducing Data Dimensions Using PCA
Using my knowledge of how to apply the Principal Component Analysis (PCA) algorithm, I reduced the dimensions of the X DataFrame to three principal components and placed these dimensions in a new DataFrame.

#### Deliverable 3: Clustering Cryptocurrencies Using K-means
Using my knowledge of the K-means algorithm, I created an elbow curve using hvPlot to find the best value for K from the pcs_df DataFrame created in Deliverable 2. Then, I ran the K-means algorithm to predict the K clusters for the cryptocurrencies’ data.

#### Deliverable 4: Visualizing Cryptocurrencies Results
Using my knowledge of creating scatter plots with Plotly Express and hvplot, I visualized the distinct groups that corresponded to the three principal components I created in Deliverable 2, then I created a table with all the currently tradable cryptocurrencies using the hvplot.table() function.


#### Reference: See crypto_clustering.ipynb
