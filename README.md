# KMeans_Clustering
 Simple market segmentation using Sklearn KMeans Clustering to compare original feature and standarized feature
 
 ## Dataset
 *3.12. Example.csv* is market data that contain 2 column :
 - *Satisfaction* :
 discrete variable with range (1 to 10)
 - *Loyalty* :
 continous variable with range (-2.5 to 2.5)
 
 ## Result
 with the original data, the cluster just divided by cutoff line in satisfaction value of 6 because the model only consider satisfaction as a feature an it caused by satisfaction value that too high compared to loyalty value while satisfaction and loyalty value is equally important feature. So after standarized the features, the cluster is not rigid as before. 
 
  
