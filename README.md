# Spam Detection Using Advanced NLP Techniques

## Introduction

This project focuses on detecting spam in email using advanced Natural Language Processing (NLP) techniques. The dataset used is an augmented version of the Enron public email corpus, specifically curated for spam detection purposes.

## Dataset

- Source: Athens University of Economics and Business (AUEB)
- Composition:
  - 3,672 regular (ham) emails
  - 1,500 spam emails

## Methodology

The project employs various NLP techniques and machine learning models to classify emails as spam or ham:

### Text Processing and Tokenization

- Utilized NLTK for tokenization and text preprocessing
- Implemented frequency distribution analysis

### Feature Engineering

- Bag-of-Words (BOW) / Unigram baseline approach
- Stopwords filtering
- Bigram features
- Part-of-Speech (POS) tagging features

### Machine Learning Models

- Naive Bayes Classifier
- Support Vector Machines (SVM)
  - SVC (Support Vector Classification)
  - LinearSVC
  - NuSVC

### Evaluation Techniques

- Cross-validation
- Precision, Recall, and F1 Score calculation

## Results

- Naive Bayes Classifier with POS features achieved 95% accuracy
- LinearSVC model outperformed others with 96% accuracy

## Key Findings

- POS-tagged features consistently provided higher accuracy across different models
- Bigram features improved performance over unigram features
- LinearSVC proved to be the most effective model for this dataset

## Future Work

- Experiment with more advanced NLP techniques (e.g., word embeddings, deep learning models)
- Explore ensemble methods to potentially improve accuracy further
- Investigate the impact of different preprocessing techniques on model performance
