# 📱 SMS Spam Classifier

A machine learning-based SMS Spam Classifier that uses Natural Language Processing (NLP) techniques to distinguish between spam and ham (non-spam) messages.

## 🚀 Features

- Preprocessing of SMS data including lowercasing, punctuation removal, stopword removal, and stemming.
- Vectorization using TF-IDF for feature extraction.
- Classification using Multinomial Naive Bayes algorithm.
- Model and vectorizer persistence using `pickle` for later reuse.
- Streamlit interface for easy message prediction and interaction.

## 🗂️ Dataset

The dataset used is `spam.csv`, which contains over 5,000 SMS messages labeled as either:
- `ham`: not spam
- `spam`: unwanted/spam messages

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- NLTK
- Pickle
- Jupyter Notebook
- Streamlit

## 📦 How to Use (via Streamlit)

1. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
2. Ensure the following files are in the same directory:

streamlit_app.py
model.pkl
vectorizer.pkl

3. Run the Streamlit app:
   streamlit run streamlit_app.py

4. Use the Web Interface:

Enter an SMS message into the text input box.
Click "Predict" to classify the message as SPAM or NOT SPAM.

## 🗂️ Repo Structure

sms-spam-classifier/
│
├── spam.csv                 # Dataset
├── code.ipynb               # Training notebook
├── model.pkl                # Trained model file
├── vectorizer.pkl           # TF-IDF vectorizer file
├── streamlit_app.py         # Streamlit UI app
├── requirements.txt         # Python dependencies
└── README.md                # Project documentation

## 📜 License

MIT License – You are free to use, modify, and distribute this project with attribution.

