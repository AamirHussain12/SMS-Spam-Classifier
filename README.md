# 📩 SMS Spam Classifier

This project is a simple yet powerful introduction to **Natural Language Processing (NLP)**.  
It focuses on classifying SMS messages as **Spam** or **Ham (Not Spam)** using machine learning techniques.

---

## 🚀 Project Overview

The goal of this project is to build a model that can automatically detect whether a message is spam or not.  
It demonstrates the complete NLP pipeline — from raw text to predictions.

---

## 🧠 Key Concepts Used

- Text preprocessing (cleaning, stopwords removal, etc.)
- Feature extraction using **TF-IDF**
- Machine Learning model for classification
- Model evaluation and performance analysis

---

## ⚙️ Tech Stack

- Python
- Scikit-learn
- Pandas
- NumPy
- NLP techniques (TF-IDF)

---

## 📂 Project Workflow

1. **Data Collection**
   - SMS dataset containing labeled messages (spam/ham)

2. **Data Preprocessing**
   - Lowercasing text
   - Removing punctuation and special characters
   - Removing stopwords

3. **Feature Engineering**
   - Converting text into numerical form using TF-IDF

4. **Model Training**
   - Training a classification model on processed data

5. **Evaluation**
   - Measuring performance using accuracy and other metrics

---

## 📊 Key Insight

Accuracy alone is not enough in spam detection.

- **False Positives (important messages marked as spam)** are more harmful than missing spam.
- This project highlights the importance of evaluating models beyond just accuracy.

---

## ▶️ How to Run

```bash
# Clone the repository
git clone https://github.com/AamirHussain12/SMS-Spam-Classifier

# Navigate to project folder
cd SMS-Spam-Classifier



# Run the notebook or script
