# 📰 Fake News Detection Using NLP & Machine Learning

## 🚀 Project Overview
This project was completed as part of the *AI Internship at Digipex Solutions LLC* and addresses the critical issue of *misinformation* on the internet. By combining *Natural Language Processing (NLP)* and *Machine Learning (ML), the system can classify news articles as **real* or *fake* with high accuracy.

---

## 🎯 Objective
To build an end-to-end, interpretable machine learning pipeline for classifying news articles based on their content, with the ability to detect fake news using linguistic patterns and statistical features.

---
## 📰 1. Fake and Real News Dataset by clmentbisaillon
✅ The one you just uploaded (Fake.csv and True.csv)
🔗 https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset
---

## 🔍 What Was Delivered
- ✅ Full text classification pipeline from raw text to prediction
- ✅ Cleaned, tokenized, and lemmatized news content
- ✅ Feature extraction using *TF-IDF Vectorization*
- ✅ Model training using *Logistic Regression* and *Multinomial Naive Bayes*
- ✅ Evaluation using Accuracy, Confusion Matrix, and Classification Report
- ✅ A user-friendly *Streamlit app* for live prediction

---

## 📊 Dataset Used
- *Sources*: fake.csv, true.csv
- *Features*: 
  - title: News headline
  - text: Full article body
  - subject: News category
  - date: Publication date
- *Target*: label (1 = Real, 0 = Fake)

---

## 🧹 Text Preprocessing Steps
- Lowercasing
- Removal of:
  - HTML tags
  - Punctuation
  - URLs
  - Extra spaces
- Tokenization
- Stopword removal
- Lemmatization (WordNetLemmatizer)

---

## 🤖 Machine Learning Models
| Model                    | Accuracy |
|--------------------------|----------|
| Logistic Regression      | ~96%     |
| Multinomial Naive Bayes  | ~95%     |

- Vectorized text using *TF-IDF*
- Trained and tested on 80/20 train-test split
- Interpretable and efficient classifiers

---

## 🔍 Key Insights from Analysis
- 📰 Fake news uses *emotive, sensational language* and inconsistent formatting
- ✍ Real news includes *named sources, citations, and formal language*
- 🔑 Certain *keywords* and *writing patterns* are strong indicators of fake content

---

## 🎯 Recommendations
- ✅ Integrate with *browser extensions* or *news platforms* for real-time detection
- ✅ Use as an educational tool for *media literacy training*
- ✅ Enhance social media filters to combat *disinformation spread*

---

## 💻 Streamlit Web Application

### 🚀 Features:
- Clean user interface
- Paste any article text to classify
- Instant prediction (Real/Fake)
- Built with streamlit, pickle, and scikit-learn

### ▶ To Run the App Locally:
```bash
pip install -r requirements.txt
streamlit run app.py
