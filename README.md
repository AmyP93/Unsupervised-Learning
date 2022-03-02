# Cryptocurrency Clusters

###Background

* You are on the Advisory Services Team of a financial consultancy. One of your clients, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies. They’ve asked you to create a report that includes what cryptocurrencies are on the trading market and determine whether they can be grouped to create a classification system for this new investment.


### Data Preparation

* Discard all cryptocurrencies that are not being traded. 

* Remove all rows that have at least one null value.

* Filter for cryptocurrencies that have been mined. 

* Delete the `CoinName` from the original dataframe.

* Use Pandas to create dummy variables for `Algorithm` and `ProofType`.

* Standardize your dataset so that columns that contain larger values do not unduly influence the outcome.

### Dimensionality Reduction

* Perform dimensionality reduction with PCA.Using `PCA(n_components=0.99)`and `PCA(n_components=0.90)` 

* Further reduce the dataset dimensions with t-SNE, (only one distinct cluster)

### Cluster Analysis with k-Means

* Create an elbow plot 

### Recommendation

* Did PCA reduction with both .99 and .90; negligble difference between the two.


