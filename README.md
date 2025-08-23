# 📝 Sentiment Analysis with BERT

[![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python&logoColor=white)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.13-orange?logo=tensorflow&logoColor=white)](https://www.tensorflow.org/)
[![Transformers](https://img.shields.io/badge/Transformers-HuggingFace-purple?logo=huggingface&logoColor=white)](https://huggingface.co/transformers/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

---

## 🎯 Project Overview

This project implements **Sentiment Analysis** using **BERT (Bidirectional Encoder Representations from Transformers)**. BERT is a pre-trained language model developed by Google that leverages a **bidirectional transformer architecture** to understand the context of words in a sentence.  

Unlike previous models, BERT captures **complex semantic relationships** and **nuances in human language**, making it ideal for sentiment analysis tasks, such as detecting positive and negative sentiments in social media text.

---

## 📊 Dataset

- **Source:** Tweets extracted using the Twitter API  
- **Size:** 1.6 million tweets  
- **Labels:**  
  - `0` → Negative sentiment  
  - `4` → Positive sentiment  

This dataset allows BERT to classify sentiments accurately at scale.

---

## ⚡ Key Features

- Leverages **BERT’s deep contextual understanding** for high-quality sentiment classification.  
- Handles **nuances and subtleties** of human language.  
- Scalable to millions of text samples for real-world applications.  
- Evaluates performance using standard NLP metrics: **Accuracy, Precision, Recall, F1-Score**.  

---

## 🏗️ Technical Approach

1. **Data Preprocessing:** Clean tweets, tokenize, and encode using the **BERT tokenizer**.  
2. **Model:** Fine-tune a pre-trained **BERT base model** for binary sentiment classification.  
3. **Training:** Use GPU acceleration to optimize model training on the large dataset.  
4. **Evaluation:** Assess model performance with **accuracy, precision, recall, F1-score**, and **confusion matrix**.

---

## 📊 Model Evaluation

The performance of the BERT sentiment analysis model is evaluated using standard NLP metrics:

- **Accuracy:** Overall correctness of predictions.  
- **Precision:** Proportion of positive predictions that are actually positive.  
- **Recall:** Proportion of actual positive samples correctly predicted.  
- **F1-Score:** Harmonic mean of precision and recall.
<img width="628" height="206" alt="image" src="https://github.com/user-attachments/assets/1e8eca91-1a2a-43ac-8eb5-b92e21e70fe2" />

### Confusion Matrix

The confusion matrix visualizes the model’s predictions versus the true labels:

<img width="679" height="546" alt="image" src="https://github.com/user-attachments/assets/262e3776-ae42-456e-80bf-d8268a5894cb" />
