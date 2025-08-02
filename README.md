# 🌧️ Precipitation Prediction using Machine Learning

This project applies **supervised machine learning** to predict daily precipitation in Los Angeles using historical weather data. The entire workflow is implemented in a single Jupyter Notebook.

## 📌 Overview

- **Objective:** Predict whether it will rain based on weather features like temperature, humidity, and wind speed.
- **Dataset:** 1000+ historical weather records for Los Angeles.
- **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`
- **Accuracy:** Achieved up to **93%** using classification models.

## 🧪 Machine Learning Pipeline

The notebook performs:

1. **Exploratory Data Analysis (EDA)**  
   Identify correlations, missing values, and distribution of features.

2. **Data Preprocessing**  
   - Feature selection  
   - Handling nulls and encoding categorical variables  
   - Train-test split  

3. **Model Training**  
   Algorithms used:
   - Logistic Regression  
   - Random Forest  
   - Decision Tree  

4. **Evaluation Metrics**  
   - Accuracy  
   - Confusion Matrix  
   - Cross-validation  

## 📁 File Structure

```bash
📦 Precipitation-Prediction
 └── precipitation_prediction.ipynb   # Main notebook


---

## 📊 Results

- **Best Performing Model:** ✅ Random Forest Classifier
- **Test Accuracy:** ~93%  
- **Key Insights:**
  - Temperature and humidity are strong indicators of rainfall.
  - Model generalizes well across unseen data.
  - Decision boundaries were validated using confusion matrices and cross-validation scores.

---

## 💡 Future Enhancements

- Extend to **multi-city** or **regional-scale** weather prediction  
- Experiment with **time-series forecasting models** like LSTM, Prophet, or ARIMA  
- Build a **real-time rainfall prediction web app** using Flask or Streamlit  
- Incorporate additional meteorological parameters (e.g., pressure, wind gust, cloud cover)

---
