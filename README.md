# 📬 Spam Email Classifier

A machine learning-based spam detection system that uses natural language processing (NLP) and the Naive Bayes algorithm to classify messages as spam or not spam.

---

## 🚀 Features

- Preprocessing of SMS text data (lowercasing, removing punctuation, stopwords, stemming)
- Feature extraction using TF-IDF vectorization
- Classification using Multinomial Naive Bayes
- Evaluation using accuracy, precision, recall, F1-score
- Confusion matrix and graphical result visualization

---

## 🛠️ Technologies Used

- Python
- Scikit-learn
- Pandas
- NumPy
- NLTK
- Matplotlib
- Jupyter Notebook

---

## 📂 Folder Structure

spam-email-classifier/
├── dataset/ # (Optional) Folder containing the SMS spam dataset
├── model.pkl # Saved trained model
├── vectorizer.pkl # Saved TF-IDF vectorizer
├── sms-spam-detection.ipynb # Main Jupyter notebook
├── README.md # Project documentation
├── requirements.txt # Python dependencies
└── app.py # Script for model prediction (if using a web app)

---

## 📊 Dataset

The dataset used is the **SMS Spam Collection Dataset**, available on [Kaggle](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset).

---
