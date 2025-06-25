# 📱 SMS Spam Classifier

A machine learning-based SMS Spam Classifier that uses Natural Language Processing (NLP) techniques to distinguish between spam and ham (non-spam) messages.

## 🚀 Features

- Preprocessing of SMS data including lowercasing, punctuation removal, stopword removal, stemming.
- Vectorization using TF-IDF for feature extraction.
- Classification using Multinomial Naive Bayes algorithm.
- Model and vectorizer persistence using `pickle` for later reuse.
- Interactive notebook format for ease of understanding and experimentation.

## 🗂️ Dataset

The dataset used is `spam.csv`, which contains SMS messages labeled as 'ham' (not spam) or 'spam'.

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- NLTK
- Pickle
- Jupyter Notebook

## 💡 Repo Structure

sms-spam-classifier/

│
├── spam.csv                 
# Dataset

├── code.ipynb               # Training notebook

├── model.pkl                # Trained model

├── vectorizer.pkl           # Saved TF-IDF vectorizer

└── README.md                # Project documentation
