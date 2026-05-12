# 🧠 ML-Powered Fact-Checking System

🌐 **Live Demo:** [Fact-Checking System](https://fact-check-ml-ankit-mourya-pipeline.onrender.com/)

An advanced **Machine Learning + NLP-based web application** that automatically classifies political statements and online claims as **True** or **False** using real-time fact-checking data, linguistic analysis, and robust model evaluation techniques.

---

# 🚀 Overview

This project implements a **production-style NLP pipeline** for automated misinformation detection and claim verification. It combines:

- Historical fact-check datasets
- Real-time claim validation
- Advanced linguistic feature extraction
- Multiple ML classification models
- Interactive performance benchmarking

Unlike basic text classifiers, this system focuses on **linguistic intelligence + real-world validation**, making it closer to practical misinformation detection systems used in modern AI applications.

---

# ⚙️ Key Features

## 🔍 End-to-End Data Pipeline

- Scrapes historical fact-check data from **PolitiFact**
- Integrates the **Google Fact Check Tools API** for live claim verification
- Supports real-time benchmarking and prediction analysis

---

## 🧾 Advanced NLP Feature Engineering

The system extracts multi-level linguistic features for improved prediction accuracy:

### 1. Lexical & Morphological Features
- Vocabulary usage patterns
- Word frequency analysis
- Token-level characteristics

### 2. Syntactic Features
- POS (Part-of-Speech) tagging
- Sentence structure analysis
- Grammar-based feature extraction

### 3. Semantic Features
- Sentiment analysis using **TextBlob**
- Subjectivity detection
- Context-aware textual understanding

### 4. Discourse Features
- Argument structure analysis
- Statement coherence evaluation

### 5. Pragmatic Features
- Intent-based keyword detection
- Persuasive and misleading language patterns

---

# 🤖 Machine Learning Models

The application trains and evaluates multiple classification algorithms, including:

- Logistic Regression
- Support Vector Machine (SVM)
- Decision Trees
- Naive Bayes

Each model is benchmarked for performance, accuracy, and inference efficiency.

---

# 📊 Robust Training Strategy

To ensure reliable and unbiased model performance, the pipeline includes:

- Stratified K-Fold Cross Validation
- SMOTE (Synthetic Minority Oversampling Technique) for class imbalance handling
- Multi-metric evaluation and optimization

---

# 📈 Interactive Evaluation Dashboard

The Streamlit dashboard provides:

- Accuracy, Precision, Recall, and F1-Score visualization
- Model inference latency comparison
- Real-time prediction benchmarking
- Interactive claim testing
- AI-generated model critique explaining predictions

---

# 🧱 Tech Stack

## Languages & Frameworks
- Python
- Streamlit

## Machine Learning & NLP
- Scikit-learn
- SpaCy
- TextBlob

## Data Processing
- Pandas
- NumPy

## Imbalance Handling
- Imbalanced-learn (SMOTE)

## Data Collection
- BeautifulSoup
- Google Fact Check Tools API

---

# 🧠 ML Pipeline Architecture

```text
Data Sources (PolitiFact + Google Fact Check API)
                    ↓
              Data Cleaning
                    ↓
       NLP Feature Engineering
                    ↓
         Feature Vectorization
                    ↓
      Model Training (SVM, LR, NB, DT)
                    ↓
      Cross Validation + SMOTE
                    ↓
           Model Evaluation
                    ↓
        Real-Time Fact Checking
```

---

# 🎯 Objective

The objective of this project is to demonstrate how **Machine Learning and Natural Language Processing** can be used to build intelligent systems capable of identifying misinformation and evaluating the credibility of online claims in real time.

---

# 📌 Future Improvements

- Deep Learning integration using Transformers (BERT, RoBERTa)
- Fake news source credibility scoring
- Explainable AI (XAI) visualizations
- Multi-language fact-checking support
- Real-time social media misinformation analysis

---

# 👨‍💻 Author

**Ankit Mourya**
