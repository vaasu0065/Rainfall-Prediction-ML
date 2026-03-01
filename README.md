# 🌧️ Rainfall Prediction Using Machine Learning

## 📌 Project Overview
This project focuses on analyzing historical weather data and predicting whether rainfall will occur on a given day using machine learning techniques. The project also includes exploratory data analysis (EDA) to understand seasonal and yearly rainfall patterns.

---

## 🎯 Objective
- Analyze rainfall trends year-wise and month-wise
- Predict rain occurrence (Rain / No Rain)
- Compare multiple machine learning models
- Identify important weather features affecting rainfall

---

## 📂 Dataset
The dataset contains daily weather observations including:

- Maximum Temperature
- Minimum Temperature
- Relative Humidity
- Mean Wind Speed
- Sunshine Duration
- Rainfall (mm)
- Year and Month

A binary target variable `Rain_Occurred` is created:
- `1` → Rainfall > 0 mm
- `0` → No Rainfall

---

## 🔍 Exploratory Data Analysis (EDA)
- Heatmap analysis of rainfall across years and months
- Month-wise and year-wise rainfall trend analysis
- Feature correlation analysis

EDA helps in understanding seasonal rainfall behavior and data distribution.

---

## ⚙️ Data Preprocessing
- Handling missing values using median imputation
- Feature selection based on relevance
- Train-test split for model evaluation

---

## 🤖 Machine Learning Models Used
1. **Logistic Regression**  
   - Baseline classification model  
   - Easy to interpret  

2. **Random Forest Classifier**  
   - Handles non-linear relationships  
   - Reduces overfitting  

3. **XGBoost Classifier**  
   - Gradient boosting approach  
   - Best performing model  

---

## 📊 Model Evaluation
Models were evaluated using:
- Accuracy Score
- ROC-AUC Score

Performance comparison was done across:
- Different years
- Monthly rainfall data

---

## 🏆 Results
- XGBoost achieved the highest accuracy and ROC-AUC score
- Random Forest performed better than Logistic Regression
- Humidity, sunshine, and wind speed were key influencing features

---

## 🧠 Challenges Faced
- Missing values in weather data
- Seasonal imbalance in rainfall
- Year-wise variation in model performance

---

## 🚀 Future Enhancements
- Add recent and real-time weather data
- Use time-series models like LSTM
- Deploy the model using Streamlit or Flask
- Create an API for real-time rainfall prediction

---

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost

---

## 📁 Project Structure
