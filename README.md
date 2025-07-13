# 🫀 Heart Disease Prediction and Lifestyle guidance

## 🔍 About the Project

This project is an interactive web-based application designed to **predict the risk of heart disease** using clinical data provided by users. It combines **machine learning** with **data visualization** and an **interactive chatbot** to promote preventive care and healthy lifestyle practices.

The core of the project is a **Logistic Regression** classifier trained on heart disease datasets. The model achieves an impressive **accuracy of 92%**, allowing it to make reliable predictions on whether an individual is at risk of heart disease.

To improve usability, the application includes **EDA-based insights** and a custom-built chatbot named **LubDub**, which delivers **dietary** and **exercise recommendations** based on clinical inputs or model predictions.

---

## 🎯 Use Cases

- ✅ **Early detection** of cardiovascular disease
- ✅ Tool for **doctors and healthcare professionals** to assist diagnosis
- ✅ Provides **personalized health recommendations**
- ✅ Educational tool to understand clinical risk factors

---

## 🧪 Model Accuracy

- **Algorithm Used:** Logistic Regression
- **Accuracy Achieved:** 92%
- **Evaluation Metrics:** Confusion Matrix, Accuracy Score
- **Data Used:** Clinical features including age, sex, cholesterol, BP, etc.

---

## 🩺 Clinical Input Fields

The prediction model takes the following inputs:

| Feature            | Description                                   |
|--------------------|-----------------------------------------------|
| Age                | Age of the individual                         |
| Sex                | 1 = Male, 0 = Female                          |
| ChestPainType      | Type of chest pain (0–3 encoded)              |
| RestingBP          | Resting blood pressure                        |
| Cholesterol        | Serum cholesterol (mg/dl)                     |
| FastingBS          | Fasting blood sugar > 120 mg/dl (1 = true)    |
| RestingECG         | Resting electrocardiographic results          |
| MaxHR              | Maximum heart rate achieved                   |
| ExerciseAngina     | Exercise-induced angina (1 = Yes, 0 = No)     |
| Oldpeak            | ST depression induced by exercise             |
| ST_Slope           | Slope of the peak exercise ST segment         |

---

## 🤖 LubDub Chatbot Features

**LubDub** is a rule-based chatbot integrated into the app. It provides:
- 🥗 **Diet suggestions** based on parameters like cholesterol, BP, BMI
- 🏃‍♂️ **Exercise tips** customized to fitness or clinical conditions
- ⚠️ General and personalized lifestyle advice
- ✅ Option to import form data or answer step-by-step questions

---

## 🛠️ Technologies Used

| Layer        | Technologies                                 |
|--------------|----------------------------------------------|
| Language     | Python, HTML, CSS, JavaScript                |
| Framework    | Flask                                        |
| ML Libraries | Scikit-learn, Pandas, NumPy                  |
| Visualization| Matplotlib, Seaborn                          |
| Chatbot      | JavaScript (Rule-Based)                      |
| Model Format | Joblib                                       |
| Server       | Gunicorn                                     |
| Deployment   | Render.com                                   |

---

## 🌐 Live Deployment

> 🔗 Visit the app here:  
**[https://heart-disease-prediction-elm1.onrender.com](https://heart-disease-prediction-elm1.onrender.com)**

