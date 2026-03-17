# 🚀 Uber Sentiment & Topic Analyzer  

An end-to-end NLP system that analyzes Uber user reviews to extract sentiment, identify key topics, and generate actionable insights using Machine Learning and Deep Learning.

---

## 🔥 Overview  

This project converts raw Uber reviews into meaningful insights using:

- Sentiment Analysis (Negative / Neutral / Positive)  
- Topic Modeling (what users are talking about)  
- Machine Learning + Deep Learning models  

The goal is not just prediction — but *understanding customer experience at scale*.

---

## 📸 Output Preview  

### 🔹 Model Outputs  

![Output1](uber%201.jpeg)  
![Output2](uber%202.jpeg)  
![Output3](uber%203.jpeg)  
![Output4](uber%204.jpeg)  

---

## 🎥 Project Demo  

[![Watch Demo](uber%201.jpeg)](uber%20vid.mp4)

> If the video does not play on GitHub, download uber vid.mp4 to view it.

---

## ⚙️ Pipeline  

Raw Uber Reviews  
↓  
Text Cleaning & Preprocessing  
↓  
TF-IDF Vectorization  
↓  
Machine Learning Models  
↓  
Deep Learning (DistilBERT)  
↓  
Topic Modeling  
↓  
Insights  

---

## 🧠 Models Used  

### 🔹 Machine Learning  
- Logistic Regression  
- K-Nearest Neighbors (KNN)  

### 🔹 Deep Learning  
- DistilBERT  

---

## 📊 Performance  

- Logistic Regression: ~83% accuracy  
- KNN: moderate performance  
- DistilBERT: ~88% accuracy  

> Note: Dataset is highly imbalanced, especially for the neutral class.

---

## ⚠️ Key Challenge: Neutral Class  

- Very few samples  
- Ambiguous language  

### ✔ Approach Taken  
- Class weighting  
- Stratified split  
- Transformer-based modeling  

---

## 📌 Key Insights  

### 🚨 Negative Feedback  
- Driver behavior issues  
- Ride cancellations  
- Delays  

### 😊 Positive Feedback  
- Comfortable rides  
- Smooth experience  

---

## 🌐 Deployment  

This project can be deployed using:

- Streamlit  
- Gradio  
- Flask  

---

## 💡 Future Improvements  

- Improve neutral sentiment prediction  
- Fine-tune DistilBERT  
- Real-time dashboard  
- Cloud deployment  

---

## 👩‍💻 Author  

Mallika Bhardwaj  
MSc Mathematics  
Data Science & Decision Science, IIT Delhi  

---

## 🚀 Final Note  

This project demonstrates how NLP can transform unstructured text into actionable insights using machine learning and deep learning.

---

⭐ If you found this useful, consider starring the repository.
