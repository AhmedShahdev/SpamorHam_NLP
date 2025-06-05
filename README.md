# 📧 Spam vs Ham Classification using Machine Learning

A machine learning project to classify SMS messages as **Spam** or **Ham (Not Spam)** using classical ML algorithms. This project explores an **imbalanced dataset** and focuses on proper evaluation using various metrics.

---

## 📂 Project Overview

This repository contains an end-to-end pipeline for classifying text messages as spam or ham using Machine Learning techniques. The workflow includes:

- Data cleaning and preprocessing
- Text vectorization
- Handling class imbalance
- Training multiple ML models
- Evaluating models using various metrics
- Comparing results

---

## 📊 Dataset

- The dataset consists of labeled SMS messages (`spam` or `ham`)
- Text data is **imbalanced**, with fewer spam messages compared to ham.
- Common in SMS classification problems.

---

## 🛠️ Technologies Used

- Python 🐍
- Pandas, NumPy
- Scikit-learn
- NLTK (for tokenization)
- Matplotlib / Seaborn (optional: for visualizations)
- Jupyter Notebook

---

## 📌 Key Steps

### 🔹 Data Preprocessing
- Removal of punctuation and special characters
- Lowercasing text
- Tokenization using NLTK
- Stop word removal
- Vectorization (CountVectorizer or TF-IDF)

### 🔹 Handling Imbalance
- Analysis of class distribution
- Techniques like Stratified Split or Class Weights

### 🔹 ML Models Applied
- Logistic Regression
- Naive Bayes
- Support Vector Machine (SVM)
- Random Forest
- (Add any other if applicable)

---

## 📈 Evaluation Metrics

| Metric           | Description                                 |
|------------------|---------------------------------------------|
| ✅ Accuracy       | Overall correct predictions                 |
| 📉 Precision      | Correct positive predictions (Spam)         |
| 📊 Recall         | Ability to detect actual spam messages      |
| 🔁 F1-Score       | Harmonic mean of precision & recall         |
| 📉 Confusion Matrix | Visual breakdown of predictions          |

Used `classification_report`, `confusion_matrix`, and `f1_score` from `sklearn.metrics`.

---

## 🚀 How to Run

1. **Clone the repo**  
```bash
git clone https://github.com/yourusername/spam-ham-classification.git
cd spam-ham-classification
