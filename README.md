# CryptoClustering

The goal of this exercise is to use Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

## Plotting the Data Frame
![image](https://github.com/AADHIP09/CryptoClustering/assets/135389893/b9dbc98b-55c3-4d3e-b4f4-5190df361bbd)



## Elbow Curves:

### 1. Elbow Curve Based on Original Data: 
![image](https://github.com/AADHIP09/CryptoClustering/assets/135389893/a058c24a-db12-491d-903a-cfd342a53101)

#### 2.Elbow Curve Based on PCA Data: 
![image](https://github.com/AADHIP09/CryptoClustering/assets/135389893/2e74a74f-272d-4610-b9da-a4564d0e461c)

### CONCLUSIONS: 
The Elbow curve based on the PCA data shows a lower inertia value(49) in comparison with the elbow curve based on the original data(79). This indicates that the Data points are tightly clustered. It also means we have less 'noise' in our data which makes it easier to identify clusters. This makes it easier to see the patterns, and thus improve our predictability.

## Scatter Plots: 

### 1. Scatter Plot Based on Original Data: 
![image](https://github.com/AADHIP09/CryptoClustering/assets/135389893/64e06276-4d0f-42e4-9200-e02eee7b8556)

### 2. Scatter Plot Based on PCA Data:
![image](https://github.com/AADHIP09/CryptoClustering/assets/135389893/fcc8e1f2-354f-4f5e-88e3-70845d3b5bad)

### CONCLUSIONS: 
The Scatter plot based on the original data shows overlapping clusters, which suggests that the original data, using more features, may not have effectively captured the underlying patterns or structure of the data for clustering purposes. Conversely, the Scatter Plot based on the PCA data has more distinct and well-defined clusters, which indicates that this method has helped reveal more distinct patterns in the data.

### QUESTION: What is the impact of using fewer features to cluster the data using K-Means?
### ANSWER: Based on the observations, it would appear that using fewer features (PCA data) to cluster the cryptocurrency data using K-Means has had a positive impact. It has resulted in better-defined and separable clusters compared to using the original data. Thus, it can be concluded that the reduction in the number of features through PCA has likely helped highlight the essential patterns and reduce the impact of noise, leading to more accurate and meaningful clustering results.
