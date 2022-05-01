# Cryptocurrencies
Using unsupervised machine learning techniques to analyze cryptocurrency data.
# Analysis Overview
The purpose of this analysis was to analyze various cryptocurrencies on the market and create a report based on their features for an investment company to propose an investment portfolio for their clients. The following methods were used for the analysis:

* `Preprocessing the database`
* `Reducing the data dimension using Principal Component Analysis (PCA)`
* `Clustering cryptocurrencies using K-Means`
* `Visualizing classification results with 2D and 3D scatter plots`

# Resources
* Data Source: crypto_data.csv
* Python 3.7.11, Jupyter Notebook 6.4.5 [using mlenv environment].

# Results
**There were a total of 577 tradable cryptocurrencies** after `preprocessing the database`, `reduce the data dimensions using PCA`, and then `cluster the cryptocurrencies using K-Means`.

#### Finding the best value for k using an elbow curve:
![elbow_curve](https://github.com/jwhberrios/Cryptocurrencies/blob/main/Resources/elbow_curve.png)

As presented in the elbow curve above, the k value is 4. This k value in inputted into a k-means model to predict cryptocurrencies into 4 clusters.

#### 3-D scatter plot with clusters

![3d_graph](https://github.com/jwhberrios/Cryptocurrencies/blob/main/Resources/3d_chart.png)

As presented in the 3-D graph above, using the PCA algorithm, the crytocurrencies dimensions were reduced to three principal components (PC1, PC2, PC3).


#### 2-D plot with clusters

![2d_plot](https://github.com/jwhberrios/Cryptocurrencies/blob/main/Resources/2D_plot.png)

As presented in the 2-D scatter plot above, using the PCA algorithm, the crytocurrencies dimensions was reduced to two principal components.

