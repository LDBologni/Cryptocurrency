# Cryptocurrencies - Module 18 - Challenge

## Purpose of the Project

The purpose of the challenge is to use cryptocurrencies data, categorize them to build a classification system for the new investors. The potential investors are probably lost in the world of cryptocurrency so they will be presented with a report on what cryptocurrencies are, which market is located, and how to categorize them.

## Overview of the Project

Prepocessing the data: It is crucial that we preprocess our data before feeding it into our model, as the quality of the data and the relevant information that can be gleaned from it directly influences the model's capacity to learn. During the preprocessing we need to deal with:

- Standardization of the data
-  - Null values
-  - Missing values
- Handling Categorical Variables: Categorize variables wether are discrete rather than continuous. 

**Use of PCA (Principal Component Analysis)**. Principal Component Analysis (PCA) is a well-known unsupervised learning technique for reducing data dimensionality. It improves interpretability while reducing information loss at the same time. It aids in the discovery of the most important features in a dataset and facilitates the charting of data in 2D and 3D. PCA aids in the discovery of a series of linear combinations of variables.

**Elbow Curve:** One of the most important parts of any unsupervised algorithm is determining what best number of groups into which the data can be put. 

**K-means** : a method for grouping data that can be used for unseprvised machine learning. It can sort unlabeled data into a certain number of clusters based on how similar they are.

Visualizing the results with **hvplot & Plotly**.

## Results

- **Deliverable 1**: Preprocessing the Data for PCA
![deliverable_1_preprocessing](https://user-images.githubusercontent.com/88510296/146452861-2befb576-e085-40c5-8c03-834bf0980e44.png)

- **Deliverable 2**: Reducing Data Dimensions Using PCA
![deliverable_2_PCA](https://user-images.githubusercontent.com/88510296/146452881-46cec9ad-21fe-4d1f-a50d-8862002ec05c.png)


- **Deliverable 3**: Clustering Cryptocurrencies Using K-means
![image](https://user-images.githubusercontent.com/98929742/175828002-71432e25-7b85-4bbb-8fe9-662b53b17f4a.png)

The graph depicts that the optimal number of clusters is 4, although the computer numbers them starting from zero, so the clusters would be identified in the charts as follows 0, 1, 2, 3, that is indicated in the column Class in the table below.

![deliverable_3_dataframe](https://user-images.githubusercontent.com/88510296/146452900-3760f27c-9187-4fc1-ae96-310a22c12b65.png)

- **Deliverable 4**: Visualizing Cryptocurrencies Results

![deliverable_4_3d_scatter](https://user-images.githubusercontent.com/88510296/146452943-13fc35fb-8964-43dc-8010-ef7a6a26eae5.png)
![deliverable_4_scatter_coinsmined_v_coinsupply](https://user-images.githubusercontent.com/88510296/146452966-3a1b5c0a-10b4-42a8-8232-3d250fff3c00.png)


