# Cryptocurrencies
Unsupervised learning with the K-means algorithm, principal component analysis (PCA) and heirarchical clustering

## Overview of Project
Our task for this project was to use unsupervised machine learning algorithms to analyze a cryptocurrency dataset in order to create a report that included what cryptocurrencies are on the trading market. The analyzed data was then grouped to create a classification system for a new investment opportunity presentation. Our analysis included the following:

- Reading in the dataset from a CSV file and completing various Preprocessing steps on the data to prepare it for performing Principal Componen Analysis (PCA).
- Reducing the data dimensions by performing PCA to prepare the data for the K-Means algorithm and visualization.
- Clustering the cryptocurrencies by using the K-Means algorithm.
- Visualizing the principal components and clustered data through 2D and 3D scatter plots.

## Project Visualizations
Here are the visualizations we generated as part of our analysis:

1) Elbow Curve - used to determine the best K value to use for the K-Means algorithm.<br>
![Elbow Curve](https://github.com/jmueller187/Cryptocurrencies/blob/main/Resources/ElbowCurve.png)

2) 3D Scatter Plot - visualization of the three principal components generated from PCA in the four classes obtained from K-Means.<br>
![3D Scatter Plot](https://github.com/jmueller187/Cryptocurrencies/blob/main/Resources/3DScatterPlot.png)

3) 2D Scatter Plot - visualization of the Total Coins Mined vs. Total Coin Supply in the four classes obtained from K-Means.<br>
![2D Scatter Plot](https://github.com/jmueller187/Cryptocurrencies/blob/main/Resources/2DScatterPlot.png)
