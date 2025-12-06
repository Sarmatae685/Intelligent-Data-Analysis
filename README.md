# Intelligent Data Analysis - Laboratory Works

A collection of machine learning projects completed during the Master's program at **Lviv Polytechnic National University**, demonstrating practical skills in data preprocessing, supervised learning, unsupervised learning, and anomaly detection.

## 📚 Course Information

**Course**: Intelligent Data Analysis  
**Program**: Master's Degree in Data Analysis  
**Institution**: Lviv Polytechnic National University  
**Semester**: 1st Semester  

## 🎯 Overview

This repository contains 5 laboratory works covering fundamental machine learning techniques:

- **Data Preprocessing** - Feature scaling, normalization, outlier detection
- **Classification** - Supervised learning with SVM and Naive Bayes
- **Regression** - Predictive modeling with regularization
- **Clustering** - Unsupervised pattern discovery
- **Anomaly Detection** - Fraud detection in imbalanced datasets

Each lab demonstrates end-to-end ML workflow: data loading, preprocessing, model training, evaluation, and visualization.

## 📂 Repository Structure
```
Intelligent-Data-Analysis/
├── lab1-data-preprocessing/
│   ├── data_preprocessing.ipynb
│   ├── CloudWatch_Traffic_Web_Attack_.csv
│   └── README.md
├── lab2-classification/
│   ├── mobile_price_classification.ipynb
│   ├── mobile_price.csv
│   └── README.md
├── lab3-regression/
│   ├── movie_revenue_regression.ipynb
│   ├── imdb_movies.csv
│   └── README.md
├── lab4-clustering/
│   ├── clustering_analysis.ipynb
│   ├── clustering_data.csv
│   └── README.md
├── lab5-anomaly-detection/
│   ├── credit_fraud_detection.ipynb
│   ├── README.md
│   └── (dataset auto-downloads from Google Drive)
├── requirements.txt
├── .gitignore
└── README.md
```

## 🚀 Quick Start

### Option 1: Google Colab (Recommended)

Open any lab directly in your browser - no installation required!

| Lab | Topic | Open in Colab |
|-----|-------|---------------|
| 1 | Data Preprocessing | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Sarmatae685/Intelligent-Data-Analysis/blob/main/lab1-data-preprocessing/data_preprocessing.ipynb?flush_cache=true) |
| 2 | Classification | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Sarmatae685/Intelligent-Data-Analysis/blob/main/lab2-classification/mobile_price_classification.ipynb?flush_cache=true) |
| 3 | Regression | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Sarmatae685/Intelligent-Data-Analysis/blob/main/lab3-regression/movie_revenue_regression.ipynb?flush_cache=true) |
| 4 | Clustering | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Sarmatae685/Intelligent-Data-Analysis/blob/main/lab4-clustering/clustering_analysis.ipynb?flush_cache=true) |
| 5 | Anomaly Detection | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Sarmatae685/Intelligent-Data-Analysis/blob/main/lab5-anomaly-detection/credit_fraud_detection.ipynb?flush_cache=true) |

**All datasets load automatically in Colab!**

---

### Option 2: Local Setup

Clone the repository and run notebooks on your machine:
```bash
# Clone repository
git clone https://github.com/Sarmatae685/Intelligent-Data-Analysis.git
cd Intelligent-Data-Analysis

# Create virtual environment (recommended)
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Start Jupyter
jupyter notebook

# Navigate to any lab folder and open the .ipynb file
```


---

## 📊 Laboratory Works Details

### Lab 1: Data Preprocessing
**Focus**: Feature scaling, outlier detection, normalization  
**Key Techniques**: Z-score, statistical methods  

[→ Details](lab1-data-preprocessing/)

---

### Lab 2: Classification
**Focus**: Multi-class classification  
**Algorithms**: LinearSVC, Gaussian Naive Bayes  
**Metrics**: Accuracy, Precision, Recall, F1-Score  

[→ Details](lab2-classification/)

---

### Lab 3: Regression
**Focus**: Revenue prediction  
**Algorithm**: Ridge Regression with L2 regularization  
**Evaluation**: Explained variance, MSE, R²  

[→ Details](lab3-regression/)

---

### Lab 4: Clustering
**Focus**: Unsupervised pattern discovery  
**Algorithms**: K-Means, MiniBatchKMeans, GMM  
**Metrics**: Silhouette score, visual analysis  

[→ Details](lab4-clustering/)

---

### Lab 5: Anomaly Detection
**Focus**: Fraud detection in highly imbalanced data (0.172% fraud)  
**Algorithms**: DBSCAN, Isolation Forest, statistical methods  
**Challenge**: Real-world financial dataset  

[→ Details](lab5-anomaly-detection/)

---

## 🛠️ Technologies & Tools

- **Python 3.x** - Primary programming language
- **pandas** - Data manipulation and analysis
- **numpy** - Numerical computing
- **scikit-learn** - Machine learning algorithms
- **scipy** - Scientific computing and statistics
- **matplotlib** - Data visualization
- **seaborn** - Statistical graphics
- **Jupyter Notebook** - Interactive development
- **Google Colab** - Cloud-based execution


## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
