# 🩺 Diabetes Prediction App

This project is a **Machine Learning Web Application** built using **Streamlit** that predicts whether a person is **Diabetic or Non-Diabetic** based on medical details.

The model is trained using the **Support Vector Machine (SVM)** algorithm.

---

## 📌 Features

- User-friendly Web Interface
- Diabetes Prediction
- Machine Learning Model (SVM)
- Accuracy Score Display
- Real-time Prediction

---

## 📊 Dataset

The dataset used is **Indians Diabetes Dataset**.

Features:

- Pregnancies
- Glucose Level
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

Target:

- 0 → Non-Diabetic
- 1 → Diabetic

---

## 🛠 Technologies Used

- Python
- Streamlit
- Pandas
- NumPy
- Scikit-learn

---

## 📂 Project Structure

---

## ▶️ Installation

Install required libraries:
pip install streamlit pandas numpy scikit-learn

---

## ▶️ Run the App

Run this command:
streamlit run diabeticapp.py

Then open browser:
http://localhost:8501

---

## 📈 Model Used

**Support Vector Machine (SVM)** with linear kernel.
model = SVC(kernel='linear')

---

## 🎯 Output Example

Input patient details and click **Predict Diabetes**

Result:

- Non-Diabetic ✅
- Diabetic ⚠️

---


## ⭐ Future Improvements

- Add more ML algorithms
- Improve accuracy
- Deploy online
- Add graphs and charts
