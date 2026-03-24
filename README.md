# 📊 Tweet Sentiment Analysis

## 📌 Project Overview

This project focuses on performing **Sentiment Analysis on Twitter data** to classify tweets as **Positive, Negative, or Neutral**. The dataset contains tweets related to different companies such as Amazon, Microsoft, Google, etc.

---

## 📂 Dataset Description

The dataset consists of the following columns:

* **Id**: Unique identifier for each tweet
* **Location**: Encoded location/user identifier
* **Target**: Company or topic (Amazon, Microsoft, etc.)
* **Text**: Tweet content
* **Sentiment**: Label (Positive / Negative / Neutral)

---

## 🎯 Objective

* Perform **text preprocessing**
* Convert text into numerical features
* Train machine learning models for sentiment classification
* Evaluate model performance

---

## ⚙️ Technologies Used

* Python
* Pandas, NumPy
* Matplotlib / Seaborn
* NLTK / Scikit-learn

---

## 🔄 Workflow

1. Data Loading
2. Data Cleaning (remove stopwords, punctuation, etc.)
3. Text Preprocessing (tokenization, lemmatization)
4. Feature Extraction (TF-IDF)
5. Model Training (Logistic Regression, etc.)
6. Model Evaluation

---

## 📊 Sample Data

| Id | Target    | Sentiment | Text                                         |
| -- | --------- | --------- | -------------------------------------------- |
| 1  | Amazon    | Neutral   | BBC News - Amazon boss Jeff Bezos rejects... |
| 2  | Microsoft | Negative  | @Microsoft Why do I pay for WORD...          |
| 3  | CS-GO     | Negative  | CSGO matchmaking is full of hacking...       |

---

## 📈 Models Used

* Logistic Regression
* Naive Bayes
* Random Forest (optional)

---

## 📌 Results

* Accuracy achieved: 55%
* Best model: SVM

---



## 📎 Future Improvements

* Deep Learning (LSTM / BERT)
* Hyperparameter tuning
* Deployment using Streamlit

---
