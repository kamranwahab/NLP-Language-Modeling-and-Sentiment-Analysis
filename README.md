# 🧠 NLP Language Modeling & Sentiment Analysis

### *Statistical NLP Fundamentals using NLTK*

---

<p align="center">
  <img src="https://img.shields.io/badge/NLP-N--gram%20Language%20Model-blue" />
  <img src="https://img.shields.io/badge/Model-Naive%20Bayes-orange" />
  <img src="https://img.shields.io/badge/Dataset-Reuters%20%7C%20Movie%20Reviews-green" />
  <img src="https://img.shields.io/badge/Status-Completed-success" />
  <img src="https://img.shields.io/badge/Level-Academic%20Assignment-lightgrey" />
</p>



---

## 🧠 Introduction / Summary

Natural Language Processing (NLP) enables machines to analyze and understand human language.

This assignment explores **two essential NLP questions**:

* **How likely is a sentence?**
  → Learned using a **Bigram Language Model**

* **What sentiment does a sentence express?**
  → Learned using **Naïve Bayes sentiment classification**

### 🔑 Key Idea

> Simple statistical models, when implemented correctly, can perform **surprisingly well** without complex linguistic rules.


---

## 🎯 Objectives

The main objectives of this assignment are to:

* ✅ Understand **N-gram language modeling**
* ✅ Learn **Add-1 (Laplace) smoothing**
* ✅ Compute **sentence probabilities**
* ✅ Measure **perplexity on unseen text**
* ✅ Implement **Naïve Bayes classifier from scratch**
* ✅ Perform **binary sentiment analysis**
* ✅ Experiment with different linguistic features
* ✅ Compare **statistical vs rule-based approaches**

---


## 📂 Datasets Used


### 1️⃣ Reuters Corpus (NLTK)

**Category:** `acq` (Acquisitions)

**Purpose:** Language modeling (syntax)

**Used for:**

* Tokenization
* Unigram & Bigram construction
* Bigram probability estimation
* Perplexity calculation on unseen sentences

---

### 2️⃣ Movie Reviews Corpus (NLTK)

**Type:** Binary sentiment dataset (Positive / Negative)

**Purpose:** Sentiment analysis (semantics)

**Used for:**

* Training Naïve Bayes classifier
* Evaluating sentiment classification accuracy

---


## ⚙️ Tools & Technologies

* **Python**
* **NLTK (Natural Language Toolkit)**
* **NumPy**
* **Scikit-learn** *(only for train/test split)*
* **Google Colab**
* **Jupyter Notebook (.ipynb)**

---


### 🔹 Language Modeling Experiments

* Unigram and Bigram construction
* Add-1 (Laplace) smoothing
* Sentence probability comparison
* Perplexity evaluation on unseen text

---

### 🔹 Sentiment Classification Experiments

* Baseline Naïve Bayes (Unigram features)
* Stopword removal
* Negation handling using `NOT_` prefix
* Lexicon-based features (`LEX_POS`, `LEX_NEG`)
* Bigram-based Naïve Bayes classifier

---

---

## 📊 Results Summary

| Model / Experiment                 | Accuracy  |
| ---------------------------------- | --------- |
| **Baseline Naïve Bayes (Unigram)** | **87.0%** |
| Stopword Removal                   | 85.5%     |
| Negation Handling                  | 85.5%     |
| Lexicon Features                   | 87.0%     |
| Bigram Features                    | 86.5%     |

**Language Model Perplexity:**
➡️ `982.98` on unseen sentences

---

---

## 🧠 Main Findings

* ✔ Bigram Language Models effectively learn **word order and grammar (syntax)**
* ✔ Naïve Bayes effectively learns **sentiment and meaning (semantics)**
* ✔ Pure **statistical models outperformed rule-based tweaks**
* ✔ Stopwords and simple negation rules sometimes remove useful information
* ✔ Lexicon features were **redundant** for this dataset


---

## 🧾 How to Run the Project

1. Open **Google Colab**
2. Upload `NLP_Assignment1_Colab.ipynb`
3. Run all cells sequentially
4. Ensure **internet access** for NLTK dataset downloads

---


## ⭐ Why This Repository Matters

* 📌 Demonstrates **strong NLP fundamentals**
* 📌 Shows ability to **implement models from scratch**
* 📌 Includes **experiments, analysis, and reflection**
