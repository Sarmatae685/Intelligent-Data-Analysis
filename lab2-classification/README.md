# Lab 2: Classification

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Sarmatae685/Intelligent-Data-Analysis/blob/main/lab2-classification/mobile_price_classification.ipynb?flush_cache=true)

## Overview

Binary and multi-class classification using Support Vector Machines and Naive Bayes algorithms to predict mobile phone price categories.

## Dataset

**Mobile Price Classification** - Mobile device specifications and price ranges
- **Size**: 2,000 records, 21 features
- **Source**: Included in repository
- **Format**: CSV
- **Target**: Price range (0-3, 4 categories)

## Algorithms

- **Support Vector Machine (LinearSVC)** - Linear kernel for multi-class classification
- **Gaussian Naive Bayes** - Probabilistic classifier based on Bayes' theorem
- **StandardScaler** - Feature normalization for improved performance

## Evaluation Metrics

- **Accuracy** - Overall classification correctness
- **Precision** - Positive prediction accuracy
- **Recall** - True positive detection rate
- **F1-Score** - Harmonic mean of precision and recall
- **Confusion Matrix** - Detailed error analysis

## Technologies

- **Python 3.x**
- **scikit-learn** - Machine learning algorithms
- **pandas** - Data manipulation
- **numpy** - Numerical operations
