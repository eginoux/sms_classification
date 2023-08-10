# Text Classification with NLP: SMS Text Classification

This repository contains a Jupyter Notebook that demonstrates text classification using Natural Language Processing (NLP) techniques. The notebook focuses on classifying SMS messages into different categories using TensorFlow.

Text classification is a fundamental task in NLP, with applications ranging from sentiment analysis and spam detection to topic categorization. This project provides a practical example of building and evaluating a text classification model. 

This project is a part of the FreeCodeCamp challenges from the Machine Learning with Python course: https://www.freecodecamp.org/learn/machine-learning-with-python

## Introduction
Text classification involves assigning predefined categories or labels to text documents based on their content. In this notebook, we explore the process of building a text classification model for SMS messages. 
We start by performing exploratory data analysis (EDA) to understand the dataset, followed by data preprocessing, model selection, and evaluation.

## Dataset
The dataset used in this project consists of SMS messages labeled as either "ham" (legitimate) or "spam." The data is split into a training set and a testing set. You can find the dataset in the data directory of this repository.

## Model 
The model starts with a layer to convert text data into numerical vectors, followed by an embedding layer to capture word relationships. 
The bidirectional LSTM layer processes sequences, followed by a dropout layer for regularization. 
The subsequent dense layers further process the features, leading to a final output layer for binary classification ("ham" 0 or "spam" 1). 

## Results
The notebook covers the entire process of text classification, from data loading to model evaluation with a 98% accuracy on validation data. 

Feel free to reach out if you have any questions or suggestions regarding this project.
