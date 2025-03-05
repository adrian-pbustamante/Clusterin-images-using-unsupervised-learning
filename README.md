# Clustering Images using unsupervised learning

##  Objective

We consider a dataset consisting of images of shoes, sandals, and boots. The objective of this small project is to apply a couple of unsupervised clustering models, together with dimensionality reduction of the dataset, to classify the images.

Due to the simplicity of the approach, it is not expected that the models reach high accuracy, precision and/or recall. To analyze the outcomes of the models considered, the data has been labeled in the preprocessing part of the notebook. However only unsupervised models have been used in this work.

##  About the dataset

This Shoe vs Sandal vs Boot Image Dataset contains 15,000 images of shoes, sandals and boots. 5000 images for each category. The images have a resolution of 136x102 pixels in RGB color model. There are three classes here. Shoe, Sandal, Boot

This dataset is a modified version of a large image dataset provided by M.Stephenson.

The data can be found at the following link: https://www.kaggle.com/datasets/hasibalmuzdadid/shoe-vs-sandal-vs-boot-dataset-15k-images

## Conclusion

We consider a dataset that includes images of boots, sandals, and shoes. We train and test different clustering models, after doing some dimensionality reduction using PCA, with the aim to classify the images into their respective categories. Among the clustering models considered ( K means, Gaussian mixture, and Non negative Matrix factorization), Gaussian Mixture has the better performance, giving an average accuracy of 0.612 and fscore of 0.616. All models considered seem to have problems to distinguish between shoes and sandals.

To be able to train the models seamlessly in a laptop with 16gb of ram memory, we have only used a sample of the dataset and we have reduced the number of pixels of the images used. With more computational resources a thorough exploration of different clustering models (like DBSCAN, Mean shift, etc) could be carried out.

A jupyter notebook with all the computation can be found in this repository.
