# Cryptocurrencies
  
## Objective
  
Prepare the data for dimensions reduction with PCA and clustering using K-means.
  
Reduce data dimensions using PCA algorithms from sklearn.
  
Predict clusters using cryptocurrencies data using the K-means algorithm form sklearn.
  
Create some plots and data tables to present your results.
  
## Resources
  
Dataset provided: crypto_data.csv
  
### Data Preprocessing
  
The data from the csv file is read into a crypto_df dataframe and a bunch of proprocessing steps are applied. This data is then scaled using StandardScaler from sklearn.
  
### Reducing Data Dimensions Using PCA
  
The PCA algorithm uses this scaled data and produces 3 components

![alt_text](https://github.com/29bharat/Cryptocurrencies/blob/master/Resources/PCA.PNG)
  
  
### Clustering Cryptocurrencies Using K-means
  
Elbow curve method is applied to get the best fit number of clusters. The best fit is 4
  
![alt_text](https://github.com/29bharat/Cryptocurrencies/blob/master/Resources/Elbow%20Curve.PNG)
  
The dataframe clustered_df is created
  
![alt_text](https://github.com/29bharat/Cryptocurrencies/blob/master/Resources/clustered_df.PNG)
  
### Visualizations
  
Clustered_df 3D scatter plot using plotly express
  
![alt_text](https://github.com/29bharat/Cryptocurrencies/blob/master/Resources/3D%20Scatter.PNG)
  
Data table with all the current tradable cryptocurrencies using hvplot.table
  
![alt_text](https://github.com/29bharat/Cryptocurrencies/blob/master/Resources/hvplot%20table.PNG)
  
Scatter plot using hvplot.scatter to present the clustered data
  
![alt_text](https://github.com/29bharat/Cryptocurrencies/blob/master/Resources/clustered_df%20scatter%20plot.PNG)
  

