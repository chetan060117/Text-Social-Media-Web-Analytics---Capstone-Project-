# FinSight AI — Conversational Financial Market Intelligence Engine

⚡ **A Social Media & Financial Text Analytics Capstone Project**
📌 **Author:** Koyalkar Chetan


---

## 📘 Project Summary

FinSight AI is an advanced NLP-powered analytics engine designed to extract insights from financial and social-media text. It integrates **Sentiment Analysis**, **Emotion Detection**, **Topic Modeling**, **Named Entity Recognition (NER)**, and a **Retrieval‑Based Chatbot** into one cohesive system.

This project helps users (investors, analysts, businesses) understand:

* Market mood & public opinion
* Trending topics in financial news
* Key entities influencing markets
* Dominant emotions behind discussions
* Answers to common finance-related questions

---

## 🚀 Features Implemented

### ✔ 1. Sentiment Analysis (TF‑IDF + Logistic Regression)

* Classifies text into **Positive / Negative / Neutral**
* Applied TF‑IDF vectorization
* Evaluated using precision, recall, and F1-score

### ✔ 2. Topic Modeling (NMF)

* Extracts latent topics in financial text
* Outputs top keywords per topic
* Helps identify market themes & discussion clusters

### ✔ 3. Named Entity Recognition (NER)

* Using **spaCy** to extract:

  * ORGANIZATION
  * PERSON
  * MONEY
  * DATE
  * LOCATIONS
* Custom rules added for better financial text extraction

### ✔ 4. Emotion Detection

* Detects **Joy, Fear, Anger, Sadness, Trust, Surprise**
* Uses lexicon-based + machine learning approach

### ✔ 5. Retrieval-Based Chatbot

* Uses semantic similarity to retrieve best matching answer from knowledge base
* Includes fallback logic (keyword → semantic → default)
* Helps explain finance concepts

---

## 📂 Project Structure

```
/ (root)
│── README.md
│
│── data/(5 datasets)
│── project demo
│── ppt
│ 
│── notebooks/
│   ├── sentiment analysis.ipynb
│   ├── Topic Modeling.ipynb
│   ├── NER.ipynb
│   ├── Emotion detection.ipynb
│   └── Support Chatbot (Retrieval-based).ipynb
│
```

---

## 🔧 Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/chetan060117/Text-Social-Media-Web-Analytics---Capstone-Project-
cd Text-Social-Media-Web-Analytics---Capstone-Project-
```

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
source venv/bin/activate          # Windows → venv\Scripts\activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🧠 Modules & How to Use Them

### 🔹 **1. Sentiment Analysis**

Notebook:

```
notebooks/sentiment analysis.ipynb
```

Includes:

* Data preprocessing
* TF‑IDF vectorization
* Logistic Regression model
* Classification report
* Model saving

### 🔹 **2. Topic Modeling**

Notebook:

```
notebooks/Topic Modeling.ipynb
```

* TF‑IDF vectorization
* NMF model training
* Topic visualization

### 🔹 **3. NER**

Notebook:

```
notebooks/NER.ipynb
```

* spaCy pipeline
* Entity extraction

### 🔹 **4. Emotion Detection**

Notebook:

```
notebooks/Emotion detection.ipynb
```

* Emotion lexicon generation
* Multi‑class classification

### 🔹 **5. Retrieval Chatbot**

Notebook:

```
notebooks/Support Chatbot (Retrieval-based).ipynb
```

* TF‑IDF / embedding similarity
* Query → best match logic

---

## 📊 Results & Insights

### ⭐ Sentiment Analysis

* Good accuracy after preventing model overfitting
* Balanced performance across classes

### ⭐ Topic Modeling

Identified themes such as:

* Cryptocurrency markets
* Stock volatility
* Company earnings
* Inflation & macro‑economic factors

### ⭐ Emotion Detection

* Fear and anger increase during market crashes
* Joy rises around positive earnings and bullish trends

### ⭐ NER

* Extracted organizations, dates, monetary values effectively

### ⭐ Chatbot

* Answers retrieved correctly using similarity search
* Helps users understand financial terminology

---

## 📌 Future Enhancements

* Integrate transformer models (FinBERT, RoBERTa)
* Deploy as FastAPI/Streamlit web app
* Add real‑time Twitter/News streaming


---

## 🤝 Contributing

1. Fork repository
2. Create a feature branch
3. Commit changes
4. Open a pull request

---

## 📞 Contact

**Koyalkar Chetan**
Email: **[chetankoyalkar06@gmail.com](mailto:chetankoyalkar06@gmail.com)**

---

✔ *This README follows GitHub‑standard formatting and is ready to upload directly as your project's README.md.*
