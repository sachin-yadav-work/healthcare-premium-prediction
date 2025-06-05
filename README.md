
# 🏥 Healthcare Insurance Premium Prediction

Try app here - https://insurance-premium-prediction-sachin.streamlit.app/

## 📌 Overview

This project aims to predict healthcare insurance premiums using machine learning techniques. By analyzing various factors such as age, BMI, smoking status, region etc. The model provides insights into how these variables affect insurance costs.

---

## 🎯 Motivation

Accurate prediction of health insurance premiums is crucial for both insurers and policyholders. It enables better financial planning and risk assessment. This project leverages machine learning to model and predict insurance charges based on individual attributes.

---

## 📂 Dataset

The dataset contains the following features:

- **Age**: Age of the individual  
- **Number of Dependants**: Dependants of the individual
- **Income in Lakhs**: Income of the individual 
- **Genetical Risk**: Genetical risk of the individual
- **Insurance Plan**: Insurance Plan that the individual is looking for
- **Employment Status**: Employment status of the individual
- **Gender**: Gender of the individual  
- **Marital Status**: Marital status of the individual
- **BMI Category**: Body Mass Index category
- **Smoking Status**: Smoking status  
- **Region**: Residential area  
- **Medical History**: Any current illness  

## 🧱 Project Structure

```
healthcare-premium-prediction/
├── artifacts/                # Contains saved models and other artifacts
├── notebooks/                # Jupyter notebooks for EDA and model training
├── main.py                   # Streamlit application
├── prediction_helper.py      # Helper functions for prediction
├── requirements.txt          # Project dependencies
└── README.md                 # Documentation
```

---

## ⚙️ Installation

1. **Clone the repository:**

```bash
git clone https://github.com/sachin-yadav-work/healthcare-premium-prediction.git
cd healthcare-premium-prediction
```

2. **(Optional) Create a virtual environment:**

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install required packages:**

```bash
pip install -r requirements.txt
```

---

## 🚀 Usage

To launch the Streamlit web application:

```bash
streamlit run main.py
```

This will open a browser-based UI where you can input personal attributes and get a predicted insurance premium.

---

## ✨ Features

- ✅ Interactive Streamlit web app  
- ✅ Exploratory Data Analysis (EDA) with visual insights  
- ✅ Regression model trained for accurate prediction  
- ✅ Clean, modular, and maintainable codebase

---

## 📊 Results

- **R² Score**: e.g., `0.9877`  
- **MAE (Mean Absolute Error)**: e.g., `254.21`
