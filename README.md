# 🎬 Movie Classification Using NLP

This project focuses on classifying movie reviews using Natural Language Processing (NLP) techniques. We explore two approaches:
1. **Clustering** using unsupervised learning.
2. **Classification** using supervised learning algorithms like KNN, SVM, and Naive Bayes.

## 🗂️ Table of Contents
- Introduction
- Clustering
  - K-Means Clustering
- Classification
  - K-Nearest Neighbors (KNN)
  - Support Vector Machine (SVM)
  - Naive Bayes
- Conclusion

## 📝 Introduction
Movie reviews can be analyzed to predict the sentiment or classify them into genres. This project leverages NLP techniques to preprocess the text data and then applies clustering and classification methods to categorize the reviews.

## 🔍 Clustering
Clustering is an unsupervised learning technique that groups data points based on their similarities.

### 🔹 K-Means Clustering
We applied K-Means Clustering to group similar movie reviews together. The elbow method was used to determine the optimal number of clusters.

![Clustering Visualization](https://github.com/user-attachments/assets/6d5a0057-0ef9-46bf-9fd4-1054a55a2bed)

The above image shows the clusters formed using K-Means on the preprocessed movie review data.

## 🧠 Classification
After clustering, we move to classification using different machine learning algorithms to categorize the movie reviews.

### 🔸 K-Nearest Neighbors (KNN)
KNN is a simple, instance-based learning algorithm. It classifies a data point based on how its neighbors are classified.

### 🔹 Support Vector Machine (SVM)
SVM is a powerful classification algorithm that finds the hyperplane which best separates the data into different classes.

![SVM Classification Report](https://github.com/user-attachments/assets/723a7718-89dc-4426-ba85-bcbf74e7c100)

*The above image shows the classification report of SVM with an accuracy of 89%.*

### 🔸 Naive Bayes
Naive Bayes is a probabilistic classifier based on Bayes' theorem, making strong independence assumptions between features.

## ✅ Conclusion
This project demonstrates how NLP can be combined with clustering and various machine learning algorithms to classify movie reviews effectively.



```
git clone https://github.com/omchaudhari1107/Review-Analysis.git
```
