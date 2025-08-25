# 📧 SMS Spam Classifier

This is a beginner-friendly NLP project where we build a **machine learning model** to classify SMS messages as **Spam** or **Not Spam**.  
It uses the famous Kaggle **SMS Spam Collection Dataset**.

---

## 🚀 Project Overview
- Preprocessed SMS text (removing punctuation, lowercasing, stopword removal).
- Converted text into numerical features using **TF-IDF**.
- Trained a **Logistic Regression** model for classification.
- Achieved good accuracy in detecting spam messages.

---

## 📂 Project Structure
spam-sms-classifier/
│
├── spam_classifier.ipynb # Jupyter Notebook code
├── requirements.txt # Dependencies
├── README.md # Project details
└── data/
└── spam.csv # Dataset (from Kaggle)

---

## 🛠️ Installation & Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/spam-sms-classifier.git
   cd spam-sms-classifier
Install dependencies:
pip install -r requirements.txt
Run the notebook:
jupyter notebook spam_classifier.ipynb
📊 Results
Model: Logistic Regression
Accuracy: ~95% on test data
Example:
Input: "Congratulations! You won a free iPhone. Click the link now!"
Output: Spam
Input: "Hey, are we still meeting at 5 pm?"
Output: Not Spam
📌 Future Improvements
Try other models (Naive Bayes, Random Forest, LSTM).
Deploy as a web app using Flask/Streamlit.
🙌 Credits
Dataset: Kaggle - SMS Spam Collection Dataset
Libraries: pandas, scikit-learn, nltk
