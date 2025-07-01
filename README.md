# 🩺 Breast Care Analyzer – Early Cancer Detection Tool

## Overview
Breast Care Analyzer is a machine-learning-based diagnostic system that uses logistic regression to identify breast cancer indicators from patient data. With 92% accuracy, it supports early diagnosis and enhances medical decision-making.

## 💻 Features
- Predicts cancer presence based on 30 input features.
- Clean and interactive web interface via Flask.
- Visualizes input data and prediction probabilities.

## 📊 Dataset
- Breast Cancer Wisconsin Diagnostic Dataset (569 patients).
- Features: Radius, Texture, Perimeter, Area, Smoothness, etc.

## 🧪 Model
- Logistic Regression (Scikit-learn)
- Accuracy: **92%**
- Preprocessing: StandardScaler, LabelEncoder

## 🔧 Tech Stack
- Python, Pandas, NumPy
- Scikit-learn, Matplotlib
- Flask (web interface)
- Google Colab (experimentation)

## ⚙️ How to Run
1. Clone the repo.
2. Install dependencies: `pip install -r requirements.txt`
3. Run app: `python app.py`
4. Access via `http://localhost:5000`

## 👥 Team
- Led a 4-member team.
- Supervised data cleaning, model development, and deployment.
