# 🫀 Heart Disease Prediction
# Heart Disease Prediction
A supervised machine learning project focused on predicting whether a patient is at risk of heart disease based on clinical features. This project combines **Python for data preprocessing, feature engineering, and model building** and **Power BI for dashboard development** to uncover patterns related to cardiac risk factors and patient outcomes.

---

## Project Overview

Heart disease is one of the leading causes of death worldwide, and early identification of at-risk patients can significantly improve outcomes and reduce healthcare costs.

This project uses clinical data from the UCI Heart Disease dataset to build a classification model capable of predicting the presence of heart disease in a patient. The analysis explores demographic and clinical variables to understand which factors most influence cardiac risk.

---

## Objectives

The main objectives of this project were:

* Build a machine learning model to predict heart disease presence
* Identify the most relevant clinical risk factors
* Evaluate model performance using appropriate metrics
* Build an interactive dashboard for visual exploration of the data
* Practice the full machine learning pipeline, from data cleaning to model evaluation

---

## Tools & Technologies

* **Python**
* **Pandas**
* **Matplotlib**
* **Seaborn**
* **Scikit-learn**
* **Jupyter Notebook**
* **Power BI**
* **Git & GitHub**

---

## Dataset

Dataset used:
**UCI Heart Disease Data**

* **Source:** [Kaggle – UCI Heart Disease Data](https://www.kaggle.com/datasets/ronitf/heart-disease-uci)
* **Size:** 920 patient records
* **Target:** Binary classification — 0 (no disease) / 1 (disease present)

The dataset contains clinical variables such as:

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol
* Fasting Blood Sugar
* Resting ECG Results
* Maximum Heart Rate Achieved
* Exercise-Induced Angina
* ST Depression (Oldpeak)

---

## Questions Explored

This project investigates questions such as:

* Which **clinical features** are most associated with heart disease?
* Does **cholesterol level** significantly influence cardiac risk?
* Does **age** play a major role in disease prediction?
* How well can a **Random Forest model** classify patients by disease presence?
* Is there a risk of **overfitting**, and how does the model generalize to unseen data?

---

## Model Results

| Metric | Training Set | Test Set |
|---|---|---|
| Accuracy | 1.0000 | 0.8478 |
| Recall | 1.0000 | 0.8440 |
| F1-Score | 1.0000 | 0.8679 |

> The perfect training score is expected behavior for Random Forest. The test results indicate the model generalizes well, with only a slight overfitting.

---

## Dashboard Overview

The Power BI dashboard includes:

### Key Performance Indicators (KPIs)

* Total Patients Analyzed
* Overall Disease Rate
* Average Age of Patients
* Average Cholesterol Level

### Visual Analysis

* Disease Rate by Age Group
* Cholesterol vs Heart Disease
* Most Important Features (Random Forest)
* Disease Distribution by Sex

---

## Key Insights

Some important findings from the analysis include:

* **Cholesterol** was the strongest predictor of heart disease in the Random Forest model
* **Maximum heart rate** and **ST depression** were also among the top predictors
* **Age** showed a clear positive correlation with disease presence
* The model achieved **84.78% accuracy** on unseen data, demonstrating good generalization

---

## Project Structure

```text
03_ml_prediction/
│── data/
│   └── heart_disease_uci.csv
│── heart_disease_prediction.ipynb
│── README.md
```

---

## Future Improvements

Possible next steps for this project:

* Test additional algorithms such as **XGBoost** and **Logistic Regression**
* Apply **cross-validation** for more robust evaluation
* Perform **hyperparameter tuning** to improve model performance
* Add a risk segmentation analysis based on model predictions

---

## Author

**Luiza Magnani**
Aspiring Data Scientist | Data Analytics | Python | Power BI