# CRYPTO CLUSTERING CHALLENGE

## OVERVIEW

### One of my most important clients, Accountability Accounting, is interested in offering a new cryptocurrency investment portfolio so they have given me the task of creating a report to show what cryptocurrencies are available on the market. Unsupervised machine learning will be used to prepare this report.  Grouping of the crypto currencies will be accomplished using a clustering algorithm.  Lastly data will be visualized and provided to the board so they can use it to make decisions.

### Deliverables are as follows:

### 1) Preprocessing the data for PCA (Principal Component Analysis).

### 2) Reducing data dimensions using PCA.

### 3) Clustering cryptocurrencies using K-means.

### 4) Visualizing cryptocurrency results.



## Resources:

### Data File: crypto_data.csv

### hvplot

### pandas

### plotly

### sklearn.preprocessing. (Standard Scaler, MinMax Scaler)

### sklearn.decomposition.  PCA

### sklearn.cluster.  K-means



## Results

### Preprocessed Crypto Data

![__](https://github.com/Johnnytoobadman/Cryptocurrencies/blob/main/Images/01.png)

### Unamed column Renamed

![__](https://github.com/Johnnytoobadman/Cryptocurrencies/blob/main/Images/02.png)

### Just Crypto Currencies that are being traded

![__](https://github.com/Johnnytoobadman/Cryptocurrencies/blob/main/Images/03.png)

### Just Crypto Currencies with working algorithms

![__](https://github.com/Johnnytoobadman/Cryptocurrencies/blob/main/Images/04.png)

### Is Trading column removed

![__](https://github.com/Johnnytoobadman/Cryptocurrencies/blob/main/Images/05.png)

### Rows Removed if they contain null values

![__](https://github.com/Johnnytoobadman/Cryptocurrencies/blob/main/Images/06.png)

### Rows where coins are mined (only)

![__](https://github.com/Johnnytoobadman/Cryptocurrencies/blob/main/Images/07.png)

### Without the Coinname Column

![__](https://github.com/Johnnytoobadman/Cryptocurrencies/blob/main/Images/08.png)

### Variables Created for Text Features

![__](https://github.com/Johnnytoobadman/Cryptocurrencies/blob/main/Images/09.png)

### DataFrame with Principal Components

![__](https://github.com/Johnnytoobadman/Cryptocurrencies/blob/main/Images/10.png)

### Clustered DataFrame

![__](https://github.com/Johnnytoobadman/Cryptocurrencies/blob/main/Images/11.png)

### 3D ScatterPlot with Clusters

![__](https://github.com/Johnnytoobadman/Cryptocurrencies/blob/main/Images/12.png)

### New DataFrame with scaled Data

![__](https://github.com/Johnnytoobadman/Cryptocurrencies/blob/main/Images/13.png)


## SUMMARY

### The data was preprocessed and transformed to create a DataFrame with the Principal Components.  The ScatterPlot was  generated and works perfectly.  Unfortunately due to an unresolvable issue with hvplot on my laptop I was unable to generate the elbow curve or the Tradeable CryptoCurrencies ScatterPlot.  It is my understanding that I am not the only person to experience this issue.
