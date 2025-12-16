# Sentiment_Analysis_on_IMBD_dataset

This repository contains two sentiment analysis projects based on Natural Language Processing (NLP). The goal of both projects is to classify movie reviews as positive or negative using different modeling approaches. The implementations were developed for academic purposes and practical experimentation with machine learning and deep learning methods.

---

## Project 1: TF-IDF and Logistic Regression

This project follows a traditional machine learning pipeline for sentiment classification.

### Methodology

* Text preprocessing (lowercasing, punctuation removal, stopword removal)
* Feature extraction using TF-IDF vectorization
* Classification using Logistic Regression

### Evaluation

The model is evaluated using the following metrics:

* Accuracy
* Precision, Recall, and F1-score
* ROC-AUC
* Confusion Matrix

### Notes

* TF-IDF provides an interpretable representation of text data
* Feature weight analysis is used to examine the most influential words for each sentiment class
* This model serves as a strong and explainable baseline approach

Notebook: `TFIDF_Logistic_Regression.ipynb`

---

## Project 2: Deep Learning with TensorFlow / Keras

This project uses a neural network-based approach to perform sentiment analysis.

### Methodology

* Text preprocessing and tokenization
* Numerical vectorization of text data
* Construction of a Multi-Layer Perceptron (MLP) model using TensorFlow/Keras
* Model training and validation

### Evaluation

The model performance is assessed using:

* Accuracy
* F1-score
* ROC-AUC
* Confusion Matrix

### Notes

* The neural network is able to capture more complex patterns in text data
* This approach demonstrates the application of deep learning techniques to NLP problems
* Results are compared with the traditional machine learning model

Notebook: `Deep_Learning_Sentiment_Analysis.ipynb`

---

## Requirements

* Python 3.x
* scikit-learn
* TensorFlow / Keras
* pandas, numpy, matplotlib

---

## Purpose

These projects aim to demonstrate and compare classical machine learning and deep learning approaches for sentiment analysis on text data.

