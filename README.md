# 📧 Spam Email Detection using Machine Learning

A simple and effective machine learning project that detects spam emails using **Python**, **scikit-learn**, and **Natural Language Processing (NLP)**.  
This mini-project is great for beginners looking to understand text classification and showcase their ML skills on GitHub.

---

## 🚀 Project Overview

This project demonstrates how to build a model that classifies an email message as **Spam** or **Not Spam** using a dataset of email texts.

**Tech Stack:**
- Python 🐍  
- Scikit-learn  
- Pandas  
- CountVectorizer (Bag of Words)  
- Multinomial Naive Bayes  

---

## 🧾 Dataset

The dataset used (`spam_dataset.xlsx`) contains two columns:
| label | message |
|--------|----------|
| ham | Hi John, are we still meeting tomorrow? |
| spam | Congratulations! You've won a $1000 Walmart gift card. Click here to claim now. |
| ham | Can you send me the report by tonight? |
| spam | Earn money from home! Limited offer, apply now. |

You can expand this dataset or replace it with a larger public spam dataset for better accuracy.

---

## 🧠 Model Workflow

1. **Load and preprocess data**
2. **Convert text to numeric features** using `CountVectorizer`
3. **Train the model** using `MultinomialNB`
4. **Evaluate performance** (accuracy, precision, recall, F1-score)
5. **Predict new unseen messages**

---

## 💻 Run the Project

### Run in Google Colab
1. Open [Google Colab](https://colab.research.google.com/).
2. Upload the file **`spam_email_detection.ipynb`**.
3. Upload the **`spam_dataset.xlsx`** file to the Colab workspace.
4. Run each cell sequentially.
