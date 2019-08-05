# Eigendiputados

Given the prior dataset, please provide:

  With the chamber of representatives images (CHAMBERdb):

    - Import the data
    
    - Compute and plot the image of the mean representative  𝜇
    
    - Build a principal component analysis of the dataset. Plot a 2D PCA scoreplot showing political affiliation a 2D PCA scoreplot showing gender.
    
    - Plot the first three eigenvectors as images, interpret the resulting images.
    
    - Build a notebook widget with two parameters  𝑠=[𝑠1 ,  𝑠2]  (being the scores corresponding to the first two principal components) controlled by two sliders. Generate the reconstruction image 𝐼=𝑠1𝑡1+𝑠2𝑡2+𝜇 where,  𝑡1,𝑡2  are the two main eigenvectors with largest eigenvalues. Generate I for different configurations of  𝑠 , interpret the results.
    
    - Apply a  𝑘 -means clustering (with  𝑘=2  and  𝑘=8 ), plot the images clustered for different groups and the mean image per cluster.
    
    - Fit two classifiers ( 𝑘 -nn and RBF-SVM) on this dataset for both targets (political afiliation and gender). Use cross-validation to build a boxplot showing differences in accuracies for both classifiers and for each target. Present overall statistics of your classifiers, discuss your results.


  With your class fellow images (CLASSdb)

    - Import your images.
    
    - Project your CLASSdb images on the 2D PCA scoreplot computed previously with CHAMBERdb. Is the overall distribution far away from the chamber of representatives? Plot the mean images position on the PCA score plot and discuss the results.
    
    - Given the PCA computed with CHAMBERdb, plot the reconstruction of your own images in CLASSdb under different PCA dimesionality orders  𝑓 (e.g.  𝑓∈{1,2,5,10,50,150,250} ). Discuss whether images can be reconstructed and how may PCs are needed to reconstruct gender and other features.
    
    - Estimate the performance of the gender predictors built in with CHAMBERdb, using CLASSdb as validation dataset.
    
    - Discuss your results.
