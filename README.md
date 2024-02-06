# Spam Email Detection Model

This repository contains code for a spam email detection model built using natural language processing (NLP) techniques.

## Overview

The spam email detection model is designed to classify emails as spam or ham (not spam). It utilizes various NLP techniques and machine learning algorithms for preprocessing, feature extraction, and model training.

## Dataset

The model is trained on a dataset of labeled emails, consisting of both spam and ham emails. The dataset is cleaned and preprocessed before training the model.

## Code Structure

The repository structure is organized as follows:

- `Spam_Email_Detection.ipynb`: Jupyter Notebook containing the code for data preprocessing, model training, and evaluation.
- `Email_Data.csv`: Dataset file containing labeled emails.
- `README.md`: Markdown file providing an overview of the project and instructions for running the code.
- 'model.pkl': This file contains the trained model (multinomial Naive Bayes).
- 'Vectorizer.pkl': this file contains the vectorizer used for text.

## Models Used

The following models were used for spam email detection:

- Multinomial Naive Bayes
- Bernoulli Naive Bayes
- Gaussian Naive Bayes

## Model Results

The performance of each model was evaluated using accuracy, precision, confusion matrix, and classification report metrics. Below are the results:

### Multinomial Naive Bayes:
- Accuracy: 0.97
- Precision: 0.99
- preffered and used later for prediction

### Bernoulli Naive Bayes:
- Accuracy: 0.91
- Precision: 0.87

### Gaussian Naive Bayes:
- Accuracy: 0.88
- Precision: 0.85

