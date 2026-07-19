# ❤️ Heart Disease Prediction Web App

## 📌 Overview

This project is a **Machine Learning-based web application** built using **Streamlit** that predicts the risk of heart disease based on user input features such as age, cholesterol, blood pressure, etc.

---

## 🚀 Features

* Interactive and user-friendly UI
* Real-time prediction using trained ML model
* Data preprocessing with scaling
* Fast and lightweight deployment using Streamlit

---

## 🧠 Machine Learning Model

* Algorithm: SVM (Support Vector Machine)
* Preprocessing: StandardScaler
* Input Features:

  * age, sex, cp, trestbps, chol, fbs
  * restecg, thalach, exang, oldpeak
  * slope, ca, thal

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* Streamlit

---

## 📂 Project Structure

```
├── app.py
├── heart.csv
├── SVM_model.pkl
├── scaler.pkl
├── columns.pkl
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation & Run

1. Clone the repository:

```
git clone https://github.com/tanishka121/Heart-Disease-Prediction.git
```

2. Install dependencies:

```
pip install -r requirements.txt
```

3. Run the app:

```
streamlit run app.py
```

---

## 📊 How It Works

1. User enters medical details
2. Data is scaled using trained scaler
3. Model predicts heart disease risk
4. Output shown as:

   * ✅ Low Risk
   * ⚠️ High Risk

---

## 🎯 Future Improvements

* Add more advanced ML models (XGBoost, Random Forest)
* Deploy on cloud (Streamlit Cloud / AWS)
* Add visualization dashboard

---

## 🚀 Live Demo
👉 [Click here to use the app](https://tanishka121-heart-disease-prediction-app-3hko6x.streamlit.app/)

## 👩‍💻 Author

**Tanishka Chauhan**
BTech CSE | Data Science Enthusiast

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
# Heart-Disease-Prediction
# Heart-Disease-Prediction
