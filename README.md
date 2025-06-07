# 🏥 Disease Risk Prediction using Random Forest

A machine learning project that predicts the likelihood of a patient having a chronic disease (like diabetes) using the Random Forest classification algorithm. This model analyzes health metrics like glucose level, blood pressure, BMI, and more.

---

## 🎯 Objective

To assist healthcare professionals in early detection and pre-screening of patients by identifying high-risk individuals based on measurable health indicators.

---

## 📊 Dataset Overview

A synthetic dataset containing health parameters of individuals:

| Feature                 | Description                              |
|-------------------------|------------------------------------------|
| `Age`                  | Age of the patient                       |
| `BloodPressure`        | Diastolic blood pressure (mm Hg)         |
| `Glucose`              | Plasma glucose concentration             |
| `BMI`                  | Body Mass Index                          |
| `Insulin`              | 2-Hour serum insulin                     |
| `SkinThickness`        | Triceps skin fold thickness (mm)         |
| `DiabetesPedigreeFunc` | Genetic predisposition indicator         |
| `Pregnancies`          | Number of pregnancies                    |
| `Outcome`              | Target variable (1 = At risk, 0 = Not)   |

---

## 🧠 Algorithms Used

- ✅ **Random Forest Classifier**
- 🎛️ Ensemble of Decision Trees
- 🧮 Criterion: Gini (default) / Entropy
- 🌳 `n_estimators=100`, `max_depth=5`

---

## ⚙️ Technologies & Libraries

- Python 🐍
- `pandas` for data handling
- `scikit-learn` for modeling
- `matplotlib`, `seaborn` for visualization

---

## 🚀 How to Run

1. Clone the repository or download the code.
2. Install dependencies:
pip install pandas scikit-learn matplotlib seaborn
Run the script:
python disease_prediction_rf.py

📈 Model Evaluation
✅ Accuracy and classification metrics:

Accuracy: 100%

Classification Report:
              precision    recall  f1-score   support

           0       1.00      1.00      1.00         1
           1       1.00      1.00      1.00         1
📊 Feature Importance Visualization is generated to understand which factors contribute most to predictions.

💡 Real-World Use Cases
👩‍⚕️ AI-Assisted Pre-screening Tools

🏥 Hospital Triage & Referral Automation

🩺 Personal Health Risk Monitoring Systems

🧬 Integration with Smart Health Devices

📌 Future Scope
🔍 Use real-world datasets (e.g., PIMA, Heart Disease)

🌐 Deploy via Flask / Streamlit for interactive prediction

📱 Mobile-compatible dashboard integration

📄 License
This project is licensed under the MIT License. Feel free to use and modify.
