# Cryptocurrencies
## Purpose
The purpose of this challenge was to use clustering and unsupervised machine learning
to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for a new investment. Both the K-Means method and the PCA algorithm were used to accomplish this task.
## Results
### Elbow Curve
![elbow_curve](https://user-images.githubusercontent.com/87148177/145319480-e4c0d7f1-1f76-49a3-9be4-a35a28fb072a.png)\
We don't know what the output of the analysis would be so we are using unsupervised machine learning to identify clusters of the cryptocurrencies.
We produced this elbow curve using the K-Means method. The best k value appears to be 4 so we would conclude on an output of 4 clusters to categorize the crytocurrencies.
### 3-D Scatter Plot
![3D_Scatter](https://user-images.githubusercontent.com/87148177/145318536-b9610ccc-ed9f-4a63-b24d-558d258a356c.png)\
This 3-D scatter plot was created using the PCA algorithm to reduce the crytocurrencies dimensions to three principal components.
### Table
![table](https://user-images.githubusercontent.com/87148177/145318668-ffd9e8df-8c54-45e0-aba8-40057c845a42.png)\
This is a screenshot of a table that was created using the hvplot.table() function. The table contains all the currently tradable cryptocurrencies.
### 2D-Scatter plot with TotalCoinMined vs TotalCoinSupply
![deliverable4_scatter](https://user-images.githubusercontent.com/87148177/145319131-e46623da-190a-45e2-b078-aba19336fb59.png)\
Plotting the scatter plot from two cryptocurrency features directly does not efficiently segregate the different classes. Therefore, using the PCA algorithm is the correct choice for visualizing the data.
## Summary
We have identified the classification of 531 cryptocurrencies based on similarities of their features.
The distinct characteristics of each group need to be analyzed to determine their performance and potential interest for investment.
