# 📧 Email Spam Classifier

## Intern Details
| Field | Details |
|---|---|
| **Intern ID** | CITS4715 |
| **Full Name** | Sanskruti Vijay Gulghane |
| **Organization** | Codtech IT Solutions Pvt. Ltd. |
| **Domain** | Artificial Intelligence |
| **No. of Weeks** | 4 Weeks |
| **Internship Period** | 14 June 2026 – 12 July 2026 |

---

## 📌 Project Name
**Email Spam Classifier**

## 📋 Project Scope
Build an NLP-based classifier that automatically detects whether an email is **Spam** or **Ham (Not Spam)** using TF-IDF vectorization and a **Naive Bayes** algorithm. Includes label distribution analysis and custom email prediction.

---

## 🛠️ Technologies Used
- Python 3.x
- NumPy & Pandas
- Matplotlib & Seaborn
- Scikit-learn (TF-IDF + MultinomialNB)

---

## 📂 Project Structure
```
spam/
├── email_spam_classifier.py     # Main Python script
├── spam_label_distribution.png  # EDA output
├── spam_confusion_matrix.png    # Evaluation output
└── README.md
```

---

## ▶️ How to Run
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
python email_spam_classifier.py
```

---

## 📊 Output
- Label distribution chart (Spam vs Ham)
- Model accuracy and classification report
- Confusion matrix
- Predictions on 4 custom test emails

---

## 🔍 Algorithm
**Multinomial Naive Bayes** with **TF-IDF Vectorizer** (max 500 features, English stop words removed). Best suited for text classification tasks like spam detection.
