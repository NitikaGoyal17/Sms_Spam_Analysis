# # SMS Spam Analysis

## 📌 Overview
This project classifies SMS messages as **Spam** or **Ham** using **Machine Learning (ML) and Natural Language Processing (NLP)**.

## 🔥 Features
- Text preprocessing (stopword removal, tokenization)
- Feature extraction (TF-IDF, Count Vectorization)
- ML models like **Naïve Bayes, Logistic Regression**
- Performance evaluation (accuracy, precision, recall, F1-score)

## 📂 Dataset
Uses a labeled dataset from **Kaggle SMS Spam Collection**.

## 🛠 Installation
```bash
git clone https://github.com/NitikaGoyal17/Sms_Spam_Analysis.git
cd Sms_Spam_Analysis
pip install -r requirements.txt
```

## 🚀 Usage
```bash
python sms_spam_analysis.py
```
Example Input:
```
"Congratulations! You have won a free gift. Click here to claim."
```
Output:
```
Spam
```

## 📊 Evaluation
- **Confusion Matrix**
- **Precision, Recall, F1-Score**
- **ROC-AUC Curve**

## 💡 Future Work
- Web app deployment
- SMS API integration
- Deep learning implementation
