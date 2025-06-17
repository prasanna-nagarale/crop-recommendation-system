# 🌾 Crop Recommendation System 🚜

A machine learning-powered web application that recommends the most suitable crops based on soil, weather, and environmental parameters. Designed to help farmers and agricultural experts optimize yield, profit, and sustainability.

---

## 🧠 Introduction

Farmers often struggle with selecting the right crop due to complex factors such as soil type, climate, rainfall, temperature, humidity, and pH level. This Crop Recommendation System analyzes these inputs using predictive models to suggest optimal crops tailored to specific conditions — improving agricultural decisions, productivity, and income.

---

## ❓ Problem Statement

Choosing the wrong crop for a region or soil type can lead to poor yields and financial losses. Traditional methods rely heavily on intuition or outdated data. This system provides:
- Data-driven crop recommendations.
- Region-aware and soil-aware predictions.
- Improved resource planning and land use efficiency.

---

## 🛠️ Technologies Used

| Category        | Tools / Libraries                                                                 |
|-----------------|-----------------------------------------------------------------------------------|
| 📊 Data Handling | pandas, numpy                                                                   |
| 📚 ML Models     | scikit-learn (Logistic Regression, SVM, Naive Bayes, Decision Tree, Random Forest, Bagging, AdaBoost, Gradient Boosting) |
| 📏 Preprocessing | LabelEncoder, MinMaxScaler, StandardScaler                                       |
| ✅ Evaluation    | accuracy_score                                                                   |
| 🌐 Web Framework | Flask                                                                            |
| 🎨 Frontend      | HTML, CSS, JavaScript                                                            |

---

## 📷 Web Interface

> Screenshot of the interface:
![App Interface](https://github.com/user-attachments/assets/d167bef7-7dab-4424-bc4e-a251bd49d4f5)

---

## ⚙️ Features

- User input for environmental factors (N, P, K, pH, temperature, humidity, rainfall).
- Real-time crop recommendation based on model prediction.
- Multiple ML models with high accuracy.
- Simple and clean web interface using Flask + HTML/CSS.
- Responsive layout for desktop and mobile devices.

---

## 🧪 Models Implemented

- ✅ Logistic Regression
- ✅ Gaussian Naive Bayes
- ✅ Support Vector Machine (SVM)
- ✅ Decision Tree
- ✅ Random Forest
- ✅ Bagging Classifier
- ✅ Gradient Boosting
- ✅ AdaBoost

> Accuracy evaluated using `accuracy_score` across multiple test scenarios.

---

## 🌱 Inputs Required

- 🧪 Nitrogen (N), Phosphorous (P), Potassium (K)
- 🌡️ Temperature (°C)
- 💧 Humidity (%)
- 🌧️ Rainfall (mm)
- ⚗️ pH Value

---

## 🛤️ Future Improvements

- Real-time weather API integration.
- Geolocation-based crop suggestions.
- Dynamic yield forecasting and fertilizer suggestion.
- Multi-language support for farmers in rural areas.
