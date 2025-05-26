# 🍽️ Restaurant Review Sentiment Analysis  
**Author:** Nitish Raj Vinnakota | [LinkedIn](https://linkedin.com/in/vnr-nitish)

---

## 🔍 Project Overview

This project develops a **sentiment analysis model** to classify restaurant reviews as either **positive** or **negative**. It leverages Natural Language Processing (NLP) and machine learning to extract valuable customer feedback insights from raw text.

---

## 🎯 Objective

To automate sentiment detection on restaurant reviews and help businesses:
- Understand customer satisfaction
- Identify service pain points
- Improve decision-making using review analytics

---

## 🧾 Dataset Overview

- **File:** `Reviews.csv`  
- **Target Column:** `Liked` (1 = Positive, 0 = Negative)  
- **Text Column:** `Review` (customer review in raw text format)

---

## ⚙️ Workflow Summary

### ✅ Data Preprocessing:
- Removed punctuation and special characters  
- Converted text to lowercase  
- Applied **stemming** to reduce words to their root form  
- Removed **stopwords** to reduce noise  
- Tokenized and cleaned using `re`, `nltk`, and `PorterStemmer`

### ✅ Feature Extraction:
- Applied **Bag of Words (BoW)** using `CountVectorizer`
- Created a sparse matrix of word frequencies

### ✅ Model Training:
- Split dataset using `train_test_split` (80/20)
- Trained using:
  - **Naive Bayes Classifier**
  - (Optional extensions: SVM, Logistic Regression)

### ✅ Evaluation Metrics:
- Confusion Matrix  
- Accuracy Score  
- Precision, Recall, F1 Score

---

## 🧠 Tools & Libraries Used

- `Python`  
- `Pandas`  
- `NLTK`  
- `scikit-learn`  
- `re`, `string`  
- `CountVectorizer`, `train_test_split`, `MultinomialNB`

---

## 📈 Results

- The model achieved high accuracy on the test set  
- Demonstrated reliable classification between positive and negative reviews  
- Preprocessing improved model performance by reducing noise

---

## 🧪 Possible Enhancements

- Replace BoW with **TF-IDF Vectorization**  
- Try **advanced models** like SVM or XGBoost  
- Use **LSTM or BERT** for deep learning-based sentiment classification  
- Deploy using **Streamlit** for real-time review classification

---

## 📫 Contact

📧 **Email:** nvinnako2@gitam.in  
🔗 **LinkedIn:** [linkedin.com/in/vnr-nitish](https://linkedin.com/in/vnr-nitish)

---

> *"Sentiment is the new signal. Learn what your customers feel — instantly."*
