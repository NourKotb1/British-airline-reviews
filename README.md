# ✈️ NLP Pipeline for British Airline Reviews

## 📌 Project Overview

This project presents an end-to-end **Natural Language Processing (NLP)** pipeline designed to analyze customer reviews of British Airways. The goal is to predict whether customers would recommend the airline based on their feedback — helping the company identify improvement areas and enhance customer satisfaction.

## 🔍 Problem Statement

Customer feedback plays a vital role in airline reputation and business growth. By automating the prediction of whether a customer would recommend British Airways or not, the airline can proactively improve its services.

## 📊 Dataset Information

- Source: [Kaggle - British Airline Reviews](https://www.kaggle.com/datasets/dharun4772/british-airline-review-dataset)
- Total entries: 3,616 reviews
- Key features include:
  - `content`: Review text
  - `recommended`: Target label (Yes/No)
  - Other fields: rating, author, seat type, route, date, entertainment, service scores, etc.

## 🧹 Data Preprocessing

- Removed duplicates and missing values
- Selected relevant features (`content`, `recommended`)
- Renamed columns: `content` → `text`, `recommended` → `label`
- Encoded labels: Yes = 1, No = 0
- Text cleaning:
  - Lowercasing
  - Punctuation removal
  - Stopwords removal
  - Lemmatization

## 🤖 Models & Libraries Used

- **Traditional ML Models**: (e.g., Logistic Regression, Random Forest)
- **NLP Libraries**:
  - `nltk`, `spacy`, `textacy`
  - `TfidfVectorizer`
- **Other Tools**:
  - `pandas`, `numpy`, `matplotlib`, `seaborn`
  - `sklearn` (for ML and evaluation)
  - `transformers` (for potential BERT-based modeling)

## 🔍 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
