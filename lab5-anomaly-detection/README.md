> [!NOTE]
> Download the `creditcard.csv` dataset there: https://drive.google.com/file/d/1HAvXZNik1XaYZsY9znhVvuBQMIJ-Butm/view?usp=drive_link

# Lab 5: Anomaly detection

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Sarmatae685/Intelligent-Data-Analysis/blob/main/lab5-anomaly-detection/credit_fraud_detection.ipynb?flush_cache=true)

## Overview

Detecting fraudulent credit card transactions using unsupervised anomaly detection algorithms. Handling highly imbalanced datasets with multiple outlier detection techniques.

## Algorithms

- **DBSCAN** - Density-based spatial clustering for noise detection
- **Isolation Forest** - Tree-based anomaly detection
- **IQR Method** - Interquartile range outlier detection
- **Z-Score** - Standard deviation-based outlier identification
- **Modified Z-Score** - Median absolute deviation method
- **Standard Deviation Method** - Statistical threshold approach

## Evaluation Metrics

- **Detection Rate** - Percentage of anomalies identified
- **False Positive Rate** - Incorrectly flagged normal transactions
- **Confusion Matrix** - Detailed classification results
- **Visual Analysis** - Outlier distribution plots

## Technologies

- **Python 3.x**
- **scikit-learn** - Anomaly detection algorithms
- **pandas** - Data manipulation
- **numpy** - Numerical operations
- **scipy** - Statistical functions
- **gdown** - Google Drive dataset download
