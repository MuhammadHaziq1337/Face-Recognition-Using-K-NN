# Face Recognition Using K-NN

## Abstract

This project aims to implement a face recognition system using the k-Nearest Neighbors (k-NN) classifier. The dataset used is a simplified version of the CMU Pose, Illumination, and Expression (PIE) Dataset, containing 10 subjects with 170 images each. We perform preprocessing, implement the k-NN classifier from scratch, and compare its performance with SVM and GaussianNB classifiers. Additionally, we visualize the dataset using Principal Component Analysis (PCA).

## Introduction

The dataset comprises 1700 images resized to 32x32 pixels, with each row representing an image and each column a feature. The first 170 instances belong to the first subject, the next 170 to the second, and so on.

## Tasks

1. **Pre-process the dataset:**
   - Normalize each face image vector to unit length.
   - Split the dataset into training (150 images) and testing (20 images) sets for each subject.

2. **Implement k-NN classifier from scratch:**
   - Implement Euclidean and cosine similarity distance measures.
   - Evaluate performance for different k-values (2, 5, 7, 11).
   - Present results with fewer training images (100 training, 70 testing).

3. **Use Sklearn to apply SVM and GaussianNB:**
   - Compare their accuracy with k-NN.

4. **Dimensionality reduction and visualization:**
   - Perform PCA and visualize the dataset in 3-D space using matplotlib.

## PCA-Analysis 

![image](https://github.com/MuhammadHaziq1337/Face-Recognition-Using-K-NN/assets/148570176/ee711d7f-d946-4d4f-9f88-e696f92d5f6a)

## Accuracy 
![image](https://github.com/MuhammadHaziq1337/Face-Recognition-Using-K-NN/assets/148570176/429c23a5-4367-4027-b930-9dd52a3aa456)

