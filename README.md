# SuperPixels,SLIC and SLIC Based Segmentation 

This is a Python-based project that provides implementations of two popular image segmentation techniques: Superpixels using KMeans Clustering and SLIC (Superpixel Likelihood Convolution).It also has a simple neural network for segmentation of 
of images using superpixels.
This repository contains code for generating superpixels and SLIC segments from images, 
as well as utilities for visualizing and evaluating the results.

## Table of Contents
- [Introduction](#introduction)
- [Requirements](#requirements)
- 
## Introduction
### Superpixels
Superpixels are compact, contiguous regions in an image that are perceptually similar. 
They serve as a preprocessing step for various computer vision tasks, such as object recognition, image segmentation, and more. 
Superpixels can help reduce the computational complexity of these tasks and improve their performance.

### SLIC (Superpixel Likelihood Convolution)
SLIC is a superpixel segmentation algorithm that combines k-means clustering with a spatial regularization term. 
It is known for its efficiency and effectiveness in generating superpixels that adhere well to object boundaries. 
SLIC is particularly useful when accurate boundaries are crucial for downstream tasks.

## Packages Used
The notebook using the following packages. You can run the notebook in collab or on a host having cuda support.
- NumPy
- OpenCV (cv2)
- scikit-learn
- Matplotlib
- pandas

The packages are automatically installed when the notebook runs.
  
