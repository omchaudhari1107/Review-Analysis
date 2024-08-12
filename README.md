# 🎬 Movie Classification Using NLP

This project focuses on classifying movie reviews using Natural Language Processing (NLP) techniques. We explore two approaches:
1. **Clustering** using unsupervised learning.
2. **Classification** using supervised learning algorithms like KNN, SVM, and Naive Bayes.

## 🗂️ Table of Contents
- [Introduction](#introduction)
- [Clustering](#clustering)
  - [K-Means Clustering](#k-means-clustering)
- [Classification](#classification)
  - [K-Nearest Neighbors (KNN)](#k-nearest-neighbors-knn)
  - [Support Vector Machine (SVM)](#support-vector-machine-svm)
  - [Naive Bayes](#naive-bayes)
- [Conclusion](#conclusion)

## 📝 Introduction
Movie reviews can be analyzed to predict the sentiment or classify them into genres. This project leverages NLP techniques to preprocess the text data and then applies clustering and classification methods to categorize the reviews.

## 🔍 Clustering
Clustering is an unsupervised learning technique that groups data points based on their similarities.

### 🔹 K-Means Clustering
We applied K-Means Clustering to group similar movie reviews together. The elbow method was used to determine the optimal number of clusters.

![Clustering Visualization](path/to/clustering-image.png)

The above image shows the clusters formed using K-Means on the preprocessed movie review data.

## 🧠 Classification
After clustering, we move to classification using different machine learning algorithms to categorize the movie reviews.

### 🔸 K-Nearest Neighbors (KNN)
KNN is a simple, instance-based learning algorithm. It classifies a data point based on how its neighbors are classified.

### 🔹 Support Vector Machine (SVM)
SVM is a powerful classification algorithm that finds the hyperplane which best separates the data into different classes.

### 🔸 Naive Bayes
Naive Bayes is a probabilistic classifier based on Bayes' theorem, making strong independence assumptions between features.

## ✅ Conclusion
This project demonstrates how NLP can be combined with clustering and various machine learning algorithms to classify movie reviews effectively. The complete code and implementation details are available on [GitHub](https://github.com/omchaudhari1107/Review-Analysis.git) 📂.

```
git clone https://github.com/omchaudhari1107/Review-Analysis.git
```
