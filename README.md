# Breast-Cancer-Classifier

## What is this?

This is a KNN classifier trained on the [Wisconsin breast cancer data set.](http://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Original%29)

## The data

This repository is built around a dataset curated by the UCI machine learning repository. The dataset consists of medical data derived from a study of suspicious forms found in womens' breasts in Wisconsin collected between the years 1989 and 1992. The dataset consists of the following attributes:

1. Sample code number: id number
2. Clump Thickness: 1 - 10
3. Uniformity of Cell Size: 1 - 10
4. Uniformity of Cell Shape: 1 - 10
5. Marginal Adhesion: 1 - 10
6. Single Epithelial Cell Size: 1 - 10
7. Bare Nuclei: 1 - 10
8. Bland Chromatin: 1 - 10
9. Normal Nucleoli: 1 - 10
10. Mitoses: 1 - 10
11. Class: (2 for benign, 4 for malignant)

## What is a KNN classifier?

K-nearest neighbors (KNN) classifers work by analyzing the nearest K neighbors to determine how an arbitrary point in the vector space of interest should be classed. Many of the same assumptions from Bayesian classifiers carry over to KNN classifiers (low correlation between individual features, class balances et al).
