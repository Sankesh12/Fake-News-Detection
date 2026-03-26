# 📰 Fake News Detection

- A Machine Learning based web application that detects whether a news article is Fake or Real.

# 🚀 Project Overview

- This project uses Text Processing + Machine Learning to classify news articles.

- The model is trained on real and fake news datasets and deployed using Streamlit for real-time prediction.

# 🛠 Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- TF-IDF Vectorizer
- Logistic Regression
- Streamlit
- Joblib

# 🤖 Machine Learning Model Used

- Logistic Regression

# 📊 Dataset Details
## Dataset: 
- Fake & True News Dataset
## Problem Type: 
- Classification
## Target Variable:
- 0 → Fake News
- 1 → Real News

# 🔍 Methodology
## 1️⃣ Data Preprocessing
- Combined fake and real datasets
- Created class labels
- Removed unnecessary columns
- Cleaned text (lowercase, remove links, punctuation, numbers)

## 2️⃣ Feature Engineering
- Converted text into numerical format using TF-IDF Vectorizer

## 3️⃣ Model Training
- Split data into train and test sets
- Applied Logistic Regression
- Trained model on text data

## 4️⃣ Model Evaluation
- Accuracy Score
- Classification Report

# 📸 Project Screenshots

![image alt](https://github.com/Sankesh12/Fake-News-Detection/blob/main/fake5.png)
![image alt](https://github.com/Sankesh12/Fake-News-Detection/blob/main/fake6.png)

# 📈 Model Performance
- Model achieved good accuracy
- Logistic Regression performed well for text classification

# 🌐 Deployment
- Model and vectorizer saved using Joblib
- Integrated into Streamlit Web App

# Users can:
- Enter any news article
- Click Check News
- Get result (Fake or Real) instantly

# ▶️ How to Run the Project
## ##Install dependencies
- pip install -r requirements.txt
## ##Run Streamlit App
- streamlit run fake_news.py

# 🔮 Future Improvements
- Try advanced models (Naive Bayes, LSTM, BERT)
- Improve UI design
- Add confidence score
