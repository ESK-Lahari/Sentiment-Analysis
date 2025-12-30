# Sentiment Analysis

This project implements binary sentiment classification on movie reviews using classical machine learning techniques. The goal is to determine whether a given movie review expresses a **positive** or **negative** sentiment.  
Two text feature extraction approaches are evaluated: **Bag-of-Words (BoW)** and **Term Frequency–Inverse Document Frequency (TF-IDF)**, both paired with **Logistic Regression**.

---

## 📌 Project Overview

This repository demonstrates an end-to-end text classification workflow, including:

- Text vectorization using BoW and TF-IDF
- Training sentiment classifiers using Logistic Regression
- Performance comparison between the two representations
- Predicting sentiment for new, unseen text inputs

> **Note:** A small subset of user-written movie reviews sourced from the **IMDb review dataset** is provided for demonstration.  
For practical applications, a larger dataset is recommended.

---

## 🧠 Methods Used

| Step | Description |
|-------|------------|
| Dataset | Sample IMDb movie reviews labeled positive/negative |
| Vectorization | `CountVectorizer` (BoW), `TfidfVectorizer` (TF-IDF) |
| Model | `LogisticRegression(max_iter=1000)` |
| Evaluation | `classification_report`, confusion matrix |
| Inference | Prediction on newly provided text reviews |

---

## 🚀 Getting Started

### **1️⃣ Requirements**

This project requires **Python 3.8+**.

Install the dependencies:

```bash
pip install scikit-learn numpy
