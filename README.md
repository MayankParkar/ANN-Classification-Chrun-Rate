# 📉 ANN Customer Churn Prediction

A binary classification project that uses an Artificial Neural Network (ANN) to predict whether a bank customer is likely to churn, with an interactive Streamlit app for live predictions.

## About

This project trains a feed-forward neural network on the classic `Churn_Modelling.csv` bank dataset to predict customer churn probability from features like credit score, geography, age, balance, and account activity. It covers the full pipeline — data preprocessing and encoding, model training and experimentation in notebooks, and a deployed Streamlit interface where you can enter a customer's details and get a real-time churn prediction.

## Features

- ANN built and trained with TensorFlow/Keras (`model.h5`)
- Preprocessing pipeline with `LabelEncoder`, `OneHotEncoder`, and `StandardScaler`, all persisted as `.pkl` files for reuse at inference time
- Separate notebooks for experimentation (`experiments.ipynb`) and prediction (`prediction.ipynb`)
- Interactive Streamlit app (`app.py`) for entering customer details and viewing churn probability live

## Built With

- Python
- TensorFlow / Keras
- scikit-learn
- Pandas / NumPy
- Streamlit
- Jupyter Notebook

## Getting Started

```bash
git clone https://github.com/<your-username>/ANN-Classification-Chrun-Rate.git
cd ANN-Classification-Chrun-Rate
pip install -r requirements.txt
streamlit run app.py
```

Open the local URL Streamlit prints (usually `http://localhost:8501`), fill in the customer details, and view the predicted churn probability.
