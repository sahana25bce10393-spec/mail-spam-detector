# 📩 SMS Spam Detection using Machine Learning

## 📌 Project Overview

This project is a Machine Learning-based system that classifies SMS messages as **Spam** or **Ham (Not Spam)**.

Spam messages are unwanted, promotional, or fraudulent messages that can mislead users. This project demonstrates how **Natural Language Processing (NLP)** and **Machine Learning algorithms** can be used to automatically detect such messages.

The model is trained on a real-world dataset and achieves high accuracy (~98%) in classifying messages.

---

## 🎯 Problem Statement

In today's digital world, users frequently receive spam messages such as advertisements, lottery scams, and phishing attempts. Manually filtering these messages is inefficient.

👉 **Solution:**
Build an intelligent system that automatically detects whether a message is spam or not using Machine Learning.

---

## 🎯 Objectives

* Automatically classify SMS messages into spam or ham
* Apply multiple machine learning algorithms
* Compare performance of different models
* Demonstrate a real-world AI application

---

## 📂 Dataset

* Dataset Name: **SMSSpamCollection**
* Total Messages: **5574**

### Labels:

* `ham` → Normal message
* `spam` → Unwanted / spam message

---

## ⚙️ Technologies Used

* Python 🐍
* NLTK (Natural Language Processing)
* Scikit-learn (Machine Learning)

---

## 🧠 Machine Learning Models Used

The following models are trained and evaluated:

* Naive Bayes
* Multinomial Naive Bayes
* Bernoulli Naive Bayes
* Logistic Regression
* SGD Classifier

---

## 🔍 Methodology

### 1. Data Preprocessing

* Converted all text to lowercase
* Removed punctuation
* Removed stopwords using NLTK

---

### 2. Feature Extraction

* Used **Bag of Words (BoW)** approach
* Selected top **2000 most frequent words**
* Converted text messages into feature vectors

---

### 3. Model Training

* Dataset split:

  * **75% Training Data**
  * **25% Testing Data**
* Models trained using labeled data

---

### 4. Evaluation

* Accuracy used as evaluation metric
* Models achieve approximately **97% – 98% accuracy**

---

## 📊 Results

| Model               | Accuracy |
| ------------------- | -------- |
| Naive Bayes         | ~98%     |
| MultinomialNB       | ~97–98%  |
| BernoulliNB         | ~97–98%  |
| Logistic Regression | ~98%     |
| SGD Classifier      | ~98%     |

👉 All models perform well, with accuracy around **98%**.

---

## 🧪 Sample Predictions

| Message                       | Prediction |
| ----------------------------- | ---------- |
| FREE money win cash now!!!    | Spam ✅     |
| Let's meet tomorrow for lunch | Ham ✅      |
| Nature is beautiful           | Ham ✅      |
| Ankur is husband of Sahana    | Ham ✅      |

---

## 🚀 How to Run the Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/sahana25bce10393-spec/mail-spam-detector.git
cd sms-spam-detection-ml
```

### Step 2: Install Dependencies

```bash
pip install nltk scikit-learn
```

### Step 3: Run the Notebook

Open the notebook and run all cells:

```bash
jupyter notebook sms_spam_detection.ipynb
```

---

## 📁 Project Structure

```
sms-spam-detection-ml/
│
├── SMSSpamCollection.txt
├── sms_spam_detection.ipynb
└── README.md
```

---

## 💡 Key Insights

* Machine Learning can effectively classify spam messages
* Naive Bayes performs well for text classification tasks
* Simple NLP techniques can achieve high accuracy (~98%)
* Different models may give slightly different predictions

---

## 🔮 Future Improvements

* Use **TF-IDF vectorization** for better feature extraction
* Apply **Deep Learning models (LSTM, RNN)**
* Build a **web application** using Flask or Streamlit
* Implement **real-time spam detection system**

---

## 👩‍💻 Author

**Sahana Saxena**

---

## 📜 License

This project is for educational purposes only.
