# IMDB Review Classification with Logistic Regression

This repository contains a classification project using Logistic Regression to determine whether IMDB movie reviews are positive or negative based on their text content.

---

## 📚 **Project Overview**

The classification of movie reviews is a fundamental natural language processing (NLP) task. This project:
- Analyzes a dataset of 50,000 labeled IMDB reviews.
- Preprocesses text data using TF-IDF Vectorization.
- Trains a Logistic Regression model to classify reviews as positive or negative.
- Evaluates performance using metrics such as accuracy, F1-score, and a confusion matrix.
- Conducts fairness analysis to assess prediction equity across demographic groups.

---

## 🛠️ **Technologies Used**
- Python
- Scikit-learn
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🧪 Model Performance
- Accuracy: 89.58%
- Precision (Weighted): 0.90
- Recall (Weighted): 0.90
- F1-Score (Weighted): 0.90

---

## 📊 Fairness Analysis
The fairness evaluation of predictions across demographic groups revealed:

- Male Reviews Accuracy: 88.54%
- Female Reviews Accuracy: 88.88%
The model performed equitably across groups with no significant bias.

---

## 🔮 Future Enhancements
- Explore advanced classification techniques like deep learning models (e.g., LSTMs, BERT).
- Introduce hyperparameter tuning for improved model performance.
- Add analysis for multi-class sentiment categories if available.
