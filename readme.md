# Crypto Clustering Challenge

## Introduction

For this challenge we scaled down our data to prepare it, then used Kmeans to obtain a prediction of clustering according to 7 features for each datapoint. After that, to compare, we used PCA (Principal component analysis) and repeated the process to group the same data points.  

## Results

### Original 
![Elbow curve for original](Images/elbow_og.png)  
_Elbow curve for original data: The optimal value for k is 4._  
![Plot clustering original](Images/cluster_original.png)  
_Clustering for original data: The data has some overlap, like category 2 (yellow) and 3 (green)._
___


### Principal component analysis
![Elbow curve for PCA](Images/elbow_PCA.png)  
_Elbow curve for original data: The optimal value for k is still 4._
![Plot clustering PCA](Images/cluster_PCA.png)  
_Clustering for PCA: The data has less overlap, numbers are closer to each other and further from the other categories._  
