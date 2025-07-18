# 📍 Location Prediction on Twitter Using Machine Learning Techniques

This project explores how machine learning and natural language processing (NLP) can be used to predict a user's location based on tweet content and metadata. The goal is to build a system that infers user regions without relying on GPS, which can be valuable for trend analysis, crisis response, and social listening.

---

## 📌 Objective

To predict the geographic location of Twitter users (city/region level) by analyzing tweet text, hashtags, and account metadata using NLP and classification models.

---

## 📁 Dataset

- Source: Public Twitter dataset (manually collected or preprocessed)
- Features: tweet content, hashtags, username, language, time of post, location field (when available)
- Target: User’s general location (city, state, or region)

---

## 🔍 Key Tasks

### 🧹 Data Preprocessing
- Cleaned tweet text (removed URLs, emojis, mentions)
- Tokenized and vectorized text using TF-IDF
- Extracted metadata-based features (e.g., time, hashtag usage)

### 🧠 Modeling
- Implemented Naive Bayes and Logistic Regression classifiers
- Used Bag of Words and TF-IDF for feature representation
- Split data into train/test sets and evaluated predictions

### 🧪 Evaluation
- Metrics used: Accuracy, F1-score, Precision, Recall
- Performed error analysis and tuned models based on misclassification patterns

---

## ✅ Results & Insights

- Naive Bayes performed best with TF-IDF features on sparse tweet text  
- Achieved good prediction accuracy for general region-based classification  
- Highlighted the potential for inferring user location without GPS using only language patterns and metadata

---

## 🧰 Tools & Technologies

- **Programming Language:** Python  
- **Libraries:** scikit-learn, pandas, NumPy, NLTK, matplotlib, seaborn  
- **Techniques:** Natural Language Processing (NLP), Text Classification, Feature Engineering, Model Evaluation  

---
---

## 🧠 Future Improvements

- Explore deep learning models like LSTM or BERT for improved context handling  
- Expand language support for multilingual prediction  
- Integrate with a real-time Twitter streaming API for live predictions

