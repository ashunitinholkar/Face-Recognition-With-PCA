# Face Recognition With PCA


#This face recognition task implements Principal Component Analysis (PCA)
##################################################################################################################################################################
#Principal Component Analysis(PCA)

#PCA is nothing but a dimensionality reduction of given data.
#It simply project given data in some direction in order to get maximum variance.
pca1.png
##################################################################################################################################################################
#Dataset and its Preparation

#Given a csv dataset file containig pixel data and labels for images. These images are 64 X 64 pixel white images.
#There are 40 people in this dataset and each one have 10 images with different expressions or wearing glasses, etc.
#After loading data PCA will be applied on the dataset which will initially convert white images into eigen images and then find out region where maximum variation is.
pca2.png

#Sample of dataset  
h1.png
h2.png

Sample plot of training data 
plt.png

###################################################################################################################################################################


