# Spam Classification

## Overview

This project focuses on classifying emails as spam or not spam using a Naïve Bayes classifier. The model has been trained on a labeled dataset sourced from Kaggle and utilizes Natural Language Processing (NLP) techniques for text preprocessing.

## Model Performance

The Naïve Bayes model achieves the following performance metrics:

Accuracy: 95%

Precision: 94% (macro average)

Recall: 96% (macro average)

F1-Score: 95% (macro average)

## NLP Preprocessing Techniques

The dataset undergoes several preprocessing steps before classification:

Tokenization: Splitting text into individual words.

Lowercasing: Converting all text to lowercase.

Stopword Removal: Removing common words like 'the', 'is', etc.

Lemmatization: Reducing words to their base forms.

TF-IDF Vectorization: Converting text data into numerical representations for the classifier.

## Usage

Run the Naïve Bayes model to classify emails as spam or not spam. For setup and usage instructions, refer to the project files.

