# Skin Lesion Clustering using Deep Learning

## Project Overview
This project implements unsupervised clustering on skin lesion images from the HAM10000 dataset using deep learning feature extraction and various clustering algorithms.

## Features
- Deep feature extraction using ResNet50
- Multiple clustering algorithms (K-Means, Agglomerative, DBSCAN)
- Cluster evaluation using Silhouette Score, Calinski-Harabasz, Davies-Bouldin
- Dimensionality reduction with UMAP for visualization

## Dataset
- HAM10000 ("Human Against Machine with 10000 training images") dataset
- Contains dermatoscopic images of common pigmented skin lesions

## Installation
```bash
pip install torch torchvision scikit-learn umap-learn opencv-python matplotlib
