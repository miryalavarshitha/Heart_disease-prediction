# 🫀 Heart Disease Prediction and Lifestyle Guidance

## 🔍 About the Project

This project is an interactive web-based application designed to **predict the risk of heart disease** using clinical data provided by users. It combines **machine learning**, **data visualization**, and a **rule-based chatbot (LubDub)** to encourage preventive care and healthier lifestyle practices.

Four different machine learning models were evaluated, and **Logistic Regression**, achieving the **highest accuracy of 93.4%**, was selected for deployment.

---

## 🎯 Key Features and Use Cases

- ✅ **Early detection** of heart disease risk  
- ✅ **Decision support** tool for medical professionals  
- ✅ **Customized health tips** based on clinical inputs  
- ✅ **Educational insights** using visual data analytics  

---

## 🧪 Model Evaluation and Selection

| Model                   | Accuracy  |
|-------------------------|-----------|
| ✅ Logistic Regression   | **93.4%** |
| 🌲 Random Forest         | 79%       |
| 📍 K-Nearest Neighbors   | 62%       |
| 📈 Support Vector Machine| 59%       |

> ✅ **Logistic Regression** was chosen as the final model for deployment due to its superior performance.

---

## 🩺 Clinical Input Fields

| Feature         | Description                                         |
|------------------|-----------------------------------------------------|
| Age              | Age of the individual                               |
| Sex              | 1 = Male, 0 = Female                                |
| ChestPainType    | Encoded chest pain type (0–3)                       |
| RestingBP        | Resting blood pressure                              |
| Cholesterol      | Serum cholesterol (mg/dl)                           |
| FastingBS        | Fasting blood sugar > 120 mg/dl (1 = true)          |
| RestingECG       | Resting electrocardiographic results                |
| MaxHR            | Maximum heart rate achieved                         |
| ExerciseAngina   | Exercise-induced angina (1 = Yes, 0 = No)           |
| Oldpeak          | ST depression induced by exercise                   |
| ST_Slope         | Slope of the ST segment during exercise             |

---

## 📊 Visual Analysis of Risk Factors

The app includes interactive EDA dashboards and graphs that visualize:
- 🔸 Feature distributions and outliers  
- 🔸 Correlation heatmaps  
- 🔸 Risk factor comparisons by class  
- 🔸 Histogram, boxplot, and countplot summaries  

---

## 🤖 LubDub Chatbot

**LubDub** is a built-in, rule-based chatbot that helps users:
- 🥗 Get **diet recommendations** based on cholesterol, BP, and sugar levels  
- 🏃 Receive **exercise suggestions** tailored to fitness and age  
- ⚠️ Learn **lifestyle precautions** to minimize heart risk  
- 🧾 Import form values or walk through interactive Q&A  

---

## 🛠️ Technology Stack

| Layer         | Technologies                            |
|---------------|------------------------------------------|
| Language      | Python, HTML, CSS, JavaScript            |
| Framework     | Flask                                    |
| ML Libraries  | Scikit-learn, Pandas, NumPy              |
| Visualization | Matplotlib, Seaborn                      |
| Chatbot       | JavaScript (Rule-Based)                  |
| Model Format  | Joblib                                   |
| Deployment    | Flask + Gunicorn on Render.com           |

---

## 🌐 Live Deployment

🔗 Access the app here:  
**[https://heart-disease-prediction-elm1.onrender.com](https://heart-disease-prediction-elm1.onrender.com)**

---

## ⚙️ Project Pipeline

1. 📥 Load clinical dataset (CSV)  
2. 🧼 Perform preprocessing and EDA  
3. 🤖 Train four models: LR, RF, KNN, SVM  
4. 🏆 Select best-performing model (Logistic Regression: 93.4%)  
5. 📊 Evaluate via accuracy and confusion matrix  
6. 🔧 Develop backend using Flask  
7. 💻 Build frontend UI with HTML/CSS  
8. 🤖 Integrate LubDub chatbot  
9. 🌐 Deploy full-stack app on Render.com  

---

