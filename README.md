# 💳 KredAlert - Credit Card Fraud Detection

A machine learning-based fraud detection system that identifies fraudulent credit card transactions using TensorFlow/Keras and provides predictions through an interactive Streamlit web application.

---

## 📌 Project Overview

Credit card fraud is one of the major challenges faced by financial institutions today. This project aims to detect fraudulent transactions by analyzing transaction patterns and applying machine learning techniques.

Users can upload transaction data and instantly receive fraud predictions through a user-friendly web interface.

---

## 🚀 Features

- Fraud detection using Machine Learning
- Interactive Streamlit web application
- CSV file upload support
- Real-time transaction predictions
- Downloadable prediction results
- Data preprocessing and feature scaling
- User-friendly interface

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- Scikit-Learn
- Pandas
- NumPy
- Streamlit

---

## 📂 Project Structure

```text
KredAlert-credit-card-fraud-detection/
│
├── README.md
├── requirements.txt
├── architecture.md
│
├── app.py
├── main.py
├── ml_model.py
├── make_csv.py
│
├── fraud_detection_model.keras
├── scaler.pkl
├── model_metadata_cnn.json
│
└── sample_transactions.csv
```

---

## 🔍 Workflow

1. Data Collection
2. Data Preprocessing
3. Feature Scaling
4. Model Training using TensorFlow/Keras
5. Fraud Prediction
6. Result Generation through Streamlit

---

## 📈 Results

The model learns transaction patterns from historical credit card data and predicts whether a transaction is legitimate or fraudulent.

### Key Outcomes

- Detects suspicious transactions automatically
- Reduces manual verification efforts
- Provides quick prediction results
- Demonstrates an end-to-end machine learning workflow

---

## ▶️ How to Run

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Train the Model

```bash
python ml_model.py
```

### Launch the Application

```bash
streamlit run app.py
```

---

## 📊 Dataset

The project uses the Credit Card Fraud Detection dataset for model training.

Due to GitHub file size limitations, the training dataset (`creditcard.csv`) is not included in this repository.

Users can download the dataset separately and place it in the project directory before training the model.

---

## 💡 Skills Demonstrated

- Machine Learning
- Data Preprocessing
- Feature Scaling
- Model Training
- Model Evaluation
- Streamlit Deployment
- Python Development
- Data Analysis

---

## 👩‍💻 Author

**Vaishnavi Poojary**

Third-Year Computer Engineering Student  
Aspiring Data Analyst | Machine Learning Enthusiast

---
