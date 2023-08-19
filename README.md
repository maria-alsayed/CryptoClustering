# CryptoClustering

Clustering cryptocurrencies with Machine Learning (Challenge 19)
This repository contains a mini-project in which a K-means model was used to cluster different cryptocurrencies.

Author
Maria Alsayed

Overview of the Analysis
In this repository you will find how an unsupervised learning Machine Learning model was applied to cluster cryptocurrencies. The purpose of the analysis was to find the best way to cluster such currencies and to evaluate how inertia and the number of features affect the analysis.

The data were prepared for the analysis, and the following method was run twice:

Creating a Pandas DataFrame with the data to be analysed, finding the best value for 'k', clustering the cryptocurrencies with the K-means component of Sci-kit Learn, and plotting the results with hvPlot.
It was run twice because two different datasets were used: first, the original dataset, and second, the same dataset, but optimised with a principal compenent analysis (PCA).

Q&As
As you will see in the Jupyter Notebook within this repository, the following 5 questions were answered as the analysis was conducted:

Question: What is the best value for k? Answer: It seems to be 4.

Question: What is the total explained variance of the three principal components? Answer: About 89.50%. 

Question: What is the best value for k when using the PCA data? Answer: It's still 4. 

Question: Does it differ from the best k value found using the original data? Answer: No, it doesn't. 

Question: After visually analyzing the cluster analysis results, what is the impact of using fewer features to cluster the data using K-Means? Answer: The inertia decreased and the data points seem to be less dispersed.

Contents of the repository
The Resources folder:
It contains the CSV file
ReadMe File
The Crypto_Clustering.ipynb Jupyter Notebook:





