# Principal Component Analysis (PCA) for Face Image Analysis

This repository contains Python code snippets for implementing Principal Component Analysis (PCA) to analyze face images. 

## Loading and Displaying Images

We start by loading the face data and displaying the 200th image from the dataset.

## Mean Centering and Displaying Images

We calculate the mean and subtract it from the data to obtain the mean-centered data matrix. Then, we display the 100th image from the mean-centered dataset.

## Calculating Covariance Matrix and Eigenvalues

We calculate the covariance matrix on the mean-centered data matrix and extract eigenvalues and eigenvectors. Then, we sort them in descending order and plot the sorted eigenvalues.

## Performing PCA and Displaying Eigenfaces

We perform PCA using sklearn with 400 components and display the eigenfaces for the first 30 components.

## Cumulative Explained Variance

We plot the cumulative explained variance to determine the optimal number of principal components.

## Reconstructing Images with Reduced Dimensionality

We perform PCA for 150 components and reconstruct images using these components. Then, we compare the input images with the reconstructed images.

## Displaying Top Eigenvectors

We display the top-5 leading eigenvectors corresponding to the top-5 largest eigenvalues.

## Reconstructing Images with Different Numbers of Principal Components

We reconstruct the 100th image using 10, 100, 200, and 399 principal components and visualize the results.

## Conclusion

This repository provides an overview of implementing Principal Component Analysis (PCA) for face image analysis. The code snippets cover various steps, including loading data, mean centering, calculating covariance matrix, performing PCA, and reconstructing images with reduced dimensionality.
