# Cryptocurrencies

## Summary
Accountability Accounting, a prominent hypothetical investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. The company has enlisted my services to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for the tentative new investment portfolio. 

Since there is no known outcome, I employ an unsupervised machine learning python libraries and methods to explore, condense and structure, and present the findings to Accountability Accounting's team. First, I clean the data by removing null values, deleting or replacing text strings that cannot be consumed by our model, removing coins that are not active on the market, and getting that data into a useable dataframe. This stage is called "Preprocessing the Data [for PCA]". Second, I initialize a principal component analysis (PCA) tool that allows me to condense the available data into the desired number of features. In our case, that number is three. This stage is called "Reducing Data Dimensions Using PCA". Third, I use KMeans to predict which coins have similar features, and put those predictions and the three features from step 2 all into one dataframe. And, finally, I prep the data for visualization.


## Example Client Deliverables
The full list of actively trading crypto currencies can be located ![here](Resources/Actively_Trading_Cryptos.csv).

![](/images/Actively_Trading_Cryptos.png)
