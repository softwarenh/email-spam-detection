# Spam Email Classification using NLP & Logistic Regression

A robust machine learning pipeline built to automatically classify emails as **Spam** or **Normal (Ham)** using Natural Language Processing (NLP) and a Logistic Regression classifier. 

---

## 📌 Project Overview
Email spam detection is a classic classification problem with significant real-world utility. This project processes raw email text, extracts features using Term Frequency-Inverse Document Frequency (TF-IDF), trains a Logistic Regression model, and performs a thorough evaluation using metrics tailored for imbalanced classification tasks.

---

## 🚀 Key Features & Pipeline
1. **Exploratory Data Analysis (EDA):** Visualized class distributions and generated **WordClouds** to discover distinct linguistic patterns between spam and normal emails.
2. **Text Preprocessing & Feature Engineering:** Cleaned raw text data (handling prefixes, missing values) and converted text into numerical feature vectors using `TfidfVectorizer` with English stop-word removal.
3. **Model Training:** Trained a supervised **Logistic Regression** classifier on the training split.
4. **Comprehensive Evaluation:** Evaluated model performance beyond simple accuracy by analyzing **Precision, Recall, Precision-Recall Curves (PR-AUC)**, and **Confusion Matrices**.

---

## 📊 Results & Performance
* **Test Accuracy:** $\approx 98.95\%$
* **Precision:** $\approx 98.18\%$ (Ensuring a very low false-positive rate so legitimate emails don't get trapped in the spam folder)
* **Recall:** $\approx 97.46\%$ (Successfully capturing the vast majority of actual spam emails)

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python 3.x
* **Data Manipulation & Analysis:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn (`LogisticRegression`, `TfidfVectorizer`, metrics)
* **Data Visualization:** Matplotlib, Seaborn, WordCloud

---

## ⚙️ Getting Started & Installation

### 1. Clone the Repository
```bash
git clone [https://github.com/your-username/spam-email-classification.git](https://github.com/your-username/spam-email-classification.git)
cd spam-email-classification
