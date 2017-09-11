# Master-Project
Artist Identification of Van-Gogh paintings and their forgeries 

# Team Members

Nagarjun Gururaj, Stanislav Smirnov, Hridkamol Biswas, Muhammed Hassan

# Overview
This project was conducted at University of Paderborn in the SST group under the supervision of Prof. Dr. Peter Schreier. 

Two approaches, feature engineering and feature learning were used to complete the task of identifying the painting image as Van-Gogh or forgery. Additionally, we apply two dimensionality reduction techniques Principal Component Analysis (PCA) and Linear Dimensionality Reduction (LDA) on the data obtained after applying feature engineering and feature learning techniques. Finally, we use a fully-connected network and Support Vector Machine (SVM) as classifiers which are trained and tested separately.

# Feature Engineering 
Feature engineering refers to the classical feature extraction of images. Feature extraction consists of designing a filter which is convolved with the images to obtain the resulting output images. 

1) We have designed a 2D Gabor filter function which is convolved with the images of our dataset.
2) Also we have extracted the color features ike Hue and Saturation of the images by tranforming the image in RBG space to HSV space
3) Also we have split the images into several patches and applied Gabor feature extraction and color feature extraction respectively.

# Dimensionality Reduction 

From the convolved feature, we apply two dimensionality reduction techniques PCA and LDA as mentioned before.

