# K_Mean_Module

This is a K means clustering algorithm I designed. When the module is initialised it takes 3 parameters:
  no_K                Number of centroids   
  iterations          Number of iterations to run 
  plot                If the results should be plotted or not (True/False)
  
All the above parameters also have default settings if not specified

On top of this there is 1 compulsory input parameter X, this is the data the algorithm will be trained on. This is accepted in the form of a Numpy array 

Run():
  The modules K Means Clustering algorithm can be trained with the Run() function. If plot is set to true, it will graphically show the     centroids in relation to the data

Other functionalities in this module are:

Get_Out():
  This reproduces the data with an allocated centroid aswell (in the form of an integer). This data is represented as a a Numpy array
  
Get_Kmeans():
  This produces the co-ordinates for each centroid
  
Get_Parameters():
  This returns the parameters used in the K Means clustering algorithm
  




