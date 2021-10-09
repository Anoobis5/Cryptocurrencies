# Cryptocurrencies

## Project Overview

Our task is to provide a report that includes which cryptocurrencies are on the trading market and how they could be grouped to create a classification system for our client's new cryptocurrency investment portfolio it will be providing to their customers. The data we will be using will need to be processed to fit an unsupervised machine learning model. To group the currencies, we will use a clustering algorithm and visualize our data findings. 


## Results of Analysis

After processing and cleaning our data, we came up with a total of 532 tradable cryptocurrencies:

![Tradable_Crypto](https://user-images.githubusercontent.com/84881187/136662316-3e25fbfb-c174-426e-b66a-b185660e12b6.PNG)


Since we do not know what our output will be, we used unsupervised machine learning models to identify clusters of our cryptocurrency data. Using the K-Mean method to iterate on k-values 1-10, we visualized an elbow curve plot:

![elbow-curve](https://user-images.githubusercontent.com/84881187/136662654-029b7ef2-35ce-47ed-979b-cc07c0a37158.PNG)

Looking at our Elbow Curve, our best k-value to categorize our cyrptocurrency clusters would be 4.


We then used the PCA algorithm to reduce the cryptocurrency dimensions to three princocal components, and created a 3D Scatter Plot visual. Looking at our scatter splot visualization, we can observe the distribution, the 4 clusters of cryptocurrencies, and identify any outlier cryptocurrencies.
![#D_Scatterplot](https://user-images.githubusercontent.com/84881187/136662760-b4dfad94-dccd-4c02-a93b-506f5b59bc75.PNG)


We then created a scatter plot with our X-Axis as the "TotalCoinsMined", our Y-Axis as the "TotalCoinSupply", and have it sort by="Class". We also made it to show the CoinName when you hover over the the data point.
![scatterplot](https://user-images.githubusercontent.com/84881187/136663042-7108ec35-ea4f-460e-82b9-0cdb65729eef.PNG)




## Project Summary

Using our Unsupervised Machine Learning model, we can identify the classifications of 532 cryptocurrencies based on similarities in their features. Lookingat our data, we can see that Bitcoin outclasses all other cryptocurrencies, and could be used as a good exemplar of growth. However, we feel that it would be beneficial to re-run this analysis without Bitcoin to see if we can discover any other, more optimal clsuters. We will need to further analyze each group without Bitcoin to determine their potentiala and their growth performance to best suit the needs of our client and their customers in the cryptocurrency market.
