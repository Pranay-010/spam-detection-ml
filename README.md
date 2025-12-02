**BADGES**
<p align="center">
  <img src="https://img.shields.io/badge/Python-3.13.5-blue">
  <img src="https://img.shields.io/badge/TensorFlow-2.x-FF6F00">
  <img src="https://img.shields.io/badge/NLTK-Ready-green">
  <img src="https://img.shields.io/badge/Scikit--Learn-TF--IDF-orange">
  <img src="https://img.shields.io/github/license/Pranay-010/spam-detection-ml">
  <img src="https://img.shields.io/github/repo-size/Pranay-010/spam-detection-ml">
  <img src="https://img.shields.io/github/last-commit/Pranay-010/spam-detection-ml">
</p>

<h1 align="center">📧 SMS Spam Detection using Machine Learning</h1>

<p align="center">
A complete SMS Spam Classification project built using <b>Python 3.13.5</b>, TF-IDF, NLP preprocessing, and a Neural Network model (Keras).
</p>

---

##  Overview

This project focuses on classifying SMS messages into:

- **HAM** → Genuine, normal messages  
- **SPAM** → Fraud, scam, promotional, or phishing messages  

**The workflow includes:**

- Text preprocessing with NLTK  
- TF-IDF feature extraction  
- Label encoding (one-hot)  
- Neural Network model  
- Predictions on real-world messages  
- Clean dataset + notebook for reproducibility  

---

##  Features

-  Custom tokenizer  
-  Stopwords removal  
-  Lemmatization  
-  TF-IDF Vectorizer  
-  Keras Sequential Model  
-  Accurate spam classification  
-  Working prediction pipeline  
-  User input prediction  

---

##  Model Architecture

**The neural network consists of:**

- Dense Layer (128 units, ReLU)
- Dropout (0.3)
- Dense Layer (64 units, ReLU)
- Dropout (0.3)
- Output Layer (2 units, Softmax)


---
**Example 1 — Spam Message**
- URGENT: Your bank account will be blocked today. Verify at http://fake-sbi.com

**Result Summary**

TF-IDF Matrix Shape: (1500, 4568)
One-Hot Labels: (1500, 2)
Neural Network model trained successfully
Predictions working correctly on both real ham and real spam messages
