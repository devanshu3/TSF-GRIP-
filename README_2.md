## K-Means Clustering on Iris Dataset

## Overview

This repository contains Python code for performing K-Means clustering on the Iris dataset. K-Means clustering is an unsupervised machine learning technique used to group data points into clusters based on their similarities. The Iris dataset is a classic dataset often used for educational and testing purposes in the field of machine learning.

## Objective

The main objective of this project is to apply K-Means clustering to the Iris dataset to discover inherent patterns and group the iris flowers into distinct clusters based on their features. This is a fundamental example of unsupervised machine learning and can be used to gain insights into the natural structure of the dataset.

## Prerequisites

Before using this code, ensure you have the following Python libraries installed:

- `pandas`: For data manipulation and analysis.
- `numpy`: For numerical operations.
- `matplotlib`: For data visualization.
- `scikit-learn`: For the implementation of K-Means clustering.

You can install these libraries using pip: 
pip install pandas numpy matplotlib scikit-learn

## Explanation

Data Loading: The Iris dataset is loaded and organized into a Pandas DataFrame.
Optimal Number of Clusters: The Elbow Method is used to determine the optimal number of clusters for the K-Means algorithm.
K-Means Clustering: The K-Means algorithm is applied to cluster the data.
Visualization: The clustered data points and cluster centroids are visualized.
