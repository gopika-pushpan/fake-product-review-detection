# 🛒 Fake Product Review Detection using Machine Learning & Deep Learning  

![Python](https://img.shields.io/badge/Python-3.12-blue?logo=python)
![Flask](https://img.shields.io/badge/Flask-2.0-green?logo=flask)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.15-orange?logo=tensorflow)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.6-yellow?logo=scikitlearn)
![Status](https://img.shields.io/badge/Status-Active-success)

---

## 📌 Overview
Fake product reviews are a major problem in **e-commerce platforms**.  
They mislead customers and influence their buying decisions.  

This project uses **Opinion Mining & Sentiment Analysis** to detect whether a review is **Fake (CG)** or **Genuine (OR)**.  
We built and compared **Traditional ML models** and **Deep Learning models**:

- ✅ **Logistic Regression**  
- ✅ **Support Vector Machine (SVM)**  
- ✅ **LSTM** (Deep Learning)  
- 🔜 **BERT** (Future Integration)  

👉 Final system allows a user to **paste a review or product URL**, and get percentage of **Fake vs Genuine reviews**.

---

## ⚙️ Tech Stack
- **Programming Language**: Python  
- **Framework**: Flask  
- **ML/DL Libraries**: TensorFlow, Keras, Scikit-learn  
- **NLP Tools**: TF-IDF, Tokenizer, VADER Sentiment  
- **Data Handling**: Pandas, NumPy  
- **Visualization**: Matplotlib, Seaborn  
- **Scraping**: BeautifulSoup  

---

## 📂 Project Structure

fake-product-review-detection/
│── app.py                 # Flask backend
│── requirements.txt       # Dependencies
│── README.md              # Documentation
│── models/                # Trained models
│   ├── lstm_fake_review_model.h5
│   ├── tokenizer.pkl
│   ├── logistic_model.pkl
│   ├── svm_model.pkl
│   └── tfidf.pkl
│── templates/             # Frontend
│   ├── index.html
│   └── result.html
│── output_charts/         # Graphs & reports

