# Face Recognition With PCA


This face recognition task implements Principal Component Analysis (PCA)
##################################################################################################################################################################
Principal Component Analysis(PCA)

PCA is nothing but a dimensionality reduction of given data.
It simply project given data in some direction in order to get maximum variance.
![PCA](https://github.com/ashunitinholkar/Face-Recognition-With-PCA/blob/master/Face%20Recognition%20with%20PCA/images/pca1.png)
##################################################################################################################################################################
Dataset and its Preparation

Given a csv dataset file containig pixel data and labels for images. These images are 64 X 64 pixel white images.
There are 40 people in this dataset and each one have 10 images with different expressions or wearing glasses, etc.
After loading data PCA will be applied on the dataset which will initially convert white images into eigen images and then find out region where maximum variation is.
![PCA](https://github.com/ashunitinholkar/Face-Recognition-With-PCA/blob/master/Face%20Recognition%20with%20PCA/images/pca2.png)


Sample of dataset 
![Dataset](https://github.com/ashunitinholkar/Face-Recognition-With-PCA/blob/master/Face%20Recognition%20with%20PCA/images/h1.png)
![Dataset](https://github.com/ashunitinholkar/Face-Recognition-With-PCA/blob/master/Face%20Recognition%20with%20PCA/images/h2.png)


Sample plot of training data 
![Plot](https://github.com/ashunitinholkar/Face-Recognition-With-PCA/blob/master/Face%20Recognition%20with%20PCA/images/plt.png)


Accuracy for this face recognition system is 94% in total
![Classification Report](https://github.com/ashunitinholkar/Face-Recognition-With-PCA/blob/master/Face%20Recognition%20with%20PCA/images/cf1.png)
![Classification Report](https://github.com/ashunitinholkar/Face-Recognition-With-PCA/blob/master/Face%20Recognition%20with%20PCA/images/cf2.png)
###################################################################################################################################################################


