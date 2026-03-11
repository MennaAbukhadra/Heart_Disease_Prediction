# Heart Disease Prediction Dashboard

## Overview
This project is an interactive **Machine Learning dashboard** built using **Streamlit** to predict the risk of heart disease.

Users can input patient clinical data and receive a prediction of heart disease risk.  
The system also provides clustering analysis and explainable AI using **SHAP** to understand model predictions.

---

## Features

- Predict heart disease risk for a single patient
- Batch prediction for multiple patients
- Interactive patient form
- Model explainability using **SHAP**
- Patient clustering using **KMeans** and **DBSCAN**
- Interactive visualizations using **Plotly**

---

## Dataset

The project uses the **Cardiovascular Disease Dataset**.

Main features include:

- Age
- Gender
- Height
- Weight
- Systolic Blood Pressure (ap_hi)
- Diastolic Blood Pressure (ap_lo)
- Cholesterol
- Glucose
- Smoking
- Alcohol consumption
- Physical activity

Dataset file:
```
cardio_train.csv
```

---

## Machine Learning Models

The project uses several models:

### Classification Models
- XGBoost
- Logistic Regression

### Clustering Models
- KMeans
- DBSCAN

### Explainability
- SHAP (SHapley Additive Explanations)

---

## Technologies Used

- Python
- Streamlit
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Plotly
- SHAP
- Joblib

---

## Project Structure

```
Heart_Disease_Prediction
│
├── app.py
├── cardio_train.csv
├── requirements.txt
├── README.md
│
└── models
    ├── xgb_model.pkl
    ├── lg_model.pkl
    ├── dbscan_model.pkl
    ├── kmeans_model.pkl
    └── scaler.pkl
```

---

## How to Run the Project

### 1 Install dependencies

```
pip install -r requirements.txt
```

### 2 Run the Streamlit app

```
streamlit run app.py
```

The dashboard will open in your browser.

---

## Dashboard Capabilities

The application provides three main modes:

### Single Patient Prediction
Enter clinical patient data and get heart disease risk prediction.

### Cluster Exploration
Explore which cluster the patient belongs to using clustering models.

### Batch Upload
Upload a CSV file with multiple patients to generate predictions for all records.

---

## Authors

- Hager
- Mai
- Menna
- Shahd
