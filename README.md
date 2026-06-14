# 📩 Machine Learning Based SMS Spam & Ham Detection System

An end-to-end Machine Learning and Natural Language Processing (NLP) project that automatically classifies SMS messages as **Spam** or **Ham (Legitimate Message)** using Logistic Regression and TF-IDF Vectorization.

The application is deployed using Streamlit, allowing users to test SMS messages in real time.

---

## 🚀 Live Demo

https://machine-learning-based-spam-ham-detection-yuewtcszp3runl7wssgn.streamlit.app/

---

## 📌 Problem Statement

Mobile users frequently receive unwanted SMS messages, commonly known as spam. These messages may contain advertisements, scams, phishing attempts, or fraudulent content.

The objective of this project is to develop a machine learning model capable of automatically classifying SMS messages as:

- Spam
- Ham (Legitimate Message)

based on the text content of the message.

---

## 🎯 Project Objectives

- Detect spam SMS messages automatically
- Reduce unwanted message exposure
- Apply NLP techniques to text data
- Build and evaluate a machine learning classification model
- Deploy the model for real-time predictions

---

## 📊 Dataset

SMS Spam Collection Dataset

Dataset contains:

- Text → SMS Content
- Target → Spam / Ham Label

---

## 🔍 Exploratory Data Analysis (EDA)

Performed exploratory analysis to understand:

- Message distribution
- Character count
- Word count
- Sentence count
- Spam vs Ham patterns

### Feature Engineering

Created additional features:

- Number of Characters
- Number of Words
- Number of Sentences

---

## ⚙️ Data Preprocessing

### Text Cleaning

- Removed special characters
- Removed numbers
- Removed extra spaces

### Tokenization

- Converted sentences into individual words

### Stopword Removal

- Removed common words with little semantic value

### Lemmatization

- Converted words into their root form

Example:

Running → Run

Playing → Play

---

## 📈 Outlier Detection

Applied:

- Box Plot Analysis
- Interquartile Range (IQR) Method

to identify and handle abnormal message lengths.

---

## 🔤 Text Vectorization

Implemented:

### TF-IDF Vectorization

Converted text data into numerical feature vectors suitable for machine learning algorithms.

---

## ⚖️ Handling Class Imbalance

Applied:

### SMOTE (Synthetic Minority Oversampling Technique)

to balance Spam and Ham classes before model training.

---

## 🤖 Model Building

Algorithm Used:

### Logistic Regression

Steps:

1. Train-Test Split
2. Model Training
3. Prediction
4. Hyperparameter Tuning using GridSearchCV

---

## 📉 Model Evaluation

Evaluation Metrics:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

These metrics were used to assess the effectiveness of spam detection.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-Learn
- TF-IDF Vectorizer
- Logistic Regression
- SMOTE
- Joblib
- Streamlit

---

## 📁 Project Structure

```text
Machine-Learning-Based-Spam-Ham-Detection/
│
├── app.py
├── logistic_regression_sms_spam_model.pkl
├── tfidf_vectorizer.pkl
├── label_encoder.pkl
├── requirements.txt
├── spam.csv
└── README.md
```

---

## 💡 Key Learnings

- Natural Language Processing workflow
- Text preprocessing techniques
- TF-IDF feature extraction
- Handling imbalanced datasets using SMOTE
- Logistic Regression for text classification
- Hyperparameter tuning with GridSearchCV
- Streamlit deployment
- End-to-end machine learning project lifecycle

---

## 👨‍💻 Author

Daniel J

LinkedIn: https://www.linkedin.com/in/daniel-j77

GitHub: https://github.com/daniel-j77

---

## ⭐ Future Improvements

- Deep Learning based spam detection
- LSTM / RNN implementation
- Transformer-based models (BERT)
- Multilingual spam detection
- Real-time SMS filtering API
