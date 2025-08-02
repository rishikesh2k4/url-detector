# 🔒 Malicious URL Detection using Machine Learning

This project was developed by a Team Mind Melders during a **Hackathon hosted by Dayananda Sagar**. The goal was to create a robust URL classification tool that detects whether a given URL is **benign or malicious** using multiple machine learning models.

Dataset not uploaded as the dataset file is very huge, the dataset is available online!
https://www.kaggle.com/datasets/sid321axn/malicious-urls-dataset?resource=download



## 👥 Team & Hackathon Context

- **Hackathon**: Conducted at Dayananda Sagar Institutions
- **Team Size**: 5 Members  
- **Goal**: Build a URL classification engine using NLP and ML



## 📦 Project Overview

- **Objective**: Detect if a given URL is **malicious** or **benign**.
- **Input**: Raw URLs from a CSV dataset
- **Output**: Label (`malicious`, `benign`, `phishing`, or `defacement`)



## ⚙️ Techniques Used

- **Custom Tokenizer** to extract meaningful tokens from URLs
- **Vectorization Methods**:
  - Count Vectorizer
  - TF-IDF Vectorizer
- **Machine Learning Models**:
  - Multinomial Naive Bayes (Count & TF-IDF)
  - Logistic Regression (Count & TF-IDF)



## 📁 Dataset

- **File**: `malicious_phish 2.csv`
- **Columns**: `url`, `type`
- **Target Variable**: `type` (label indicating nature of the URL)



## 📊 Model Performance

- Confusion matrix and classification report for each of the 4 models
- Visualization of training/testing class distribution
- User input interface to test any URL against all models


## 👨🏻‍💻 Result


![CLI Output](https://github.com/rishikesh2k4/url-detector/blob/main/assets/urlop1.png)

![CLI Output](https://github.com/rishikesh2k4/url-detector/blob/main/assets/urlop2.png)


- **Multinomial Naive Bayesian with TF-IDF**

![CLI Output](https://github.com/rishikesh2k4/url-detector/blob/main/assets/urlop3.png)


- **Multinomial Naive Bayesian with Count Vectorizer**

![CLI Output](https://github.com/rishikesh2k4/url-detector/blob/main/assets/urlop4.png)


- **Logistic Regression with TF-IDF**

![CLI Output](https://github.com/rishikesh2k4/url-detector/blob/main/assets/urlop5.png)


- **Logistic Regression with Count Vectorizer**

![CLI Output](https://github.com/rishikesh2k4/url-detector/blob/main/assets/urlop6.png)


- **Final Result**

![CLI Output](https://github.com/rishikesh2k4/url-detector/blob/main/assets/urlop7.png)
