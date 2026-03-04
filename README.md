# 🚢 Titanic Survival Prediction using Random Forest

Predicting passenger survival from the **Sinking of the RMS Titanic** using Machine Learning and Hyperparameter Tuning.

---

## 📌 Project Overview

This project uses the **Titanic Dataset** to build a classification model that predicts whether a passenger survived or not.

The focus of this project is:

* Data Cleaning & Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Random Forest Model
* ✅ Hyperparameter Tuning for performance optimization

---

## 🎯 Problem Statement

Given passenger details such as:

* Age
* Gender
* Passenger Class (Pclass)
* Fare
* Embarked Port
* Family Size

Predict:

> **Survival (0 = No, 1 = Yes)**

---

## 🛠️ Tech Stack

* 🐍 Python
* 📊 Pandas & NumPy
* 📉 Matplotlib & Seaborn
* 🤖 Scikit-learn

---

## 🔎 Exploratory Data Analysis

* Handled missing values (Age, Cabin, Embarked)
* Analyzed survival rate by gender and class
* Created new feature: **Family Size**
* Visualized correlations and distributions

Key Insights:

* Female passengers had higher survival rates
* 1st class passengers were more likely to survive
* Fare showed positive correlation with survival

---

## 🤖 Model Building

### 🌲 Random Forest Classifier

Random Forest was chosen because:

* Handles non-linear patterns
* Reduces overfitting through ensemble learning
* Performs well on structured datasets

---

## ⚙️ Hyperparameter Tuning

Used **GridSearchCV** to optimize model performance.

### Parameters Tuned:

* `n_estimators`
* `max_depth`
* `min_samples_split`
* `min_samples_leaf`
* `max_features`

### Process:

1. Defined parameter grid
2. Applied cross-validation
3. Selected best model based on validation score

This improved generalization and reduced overfitting.

---

## 📊 Model Performance

* Accuracy: (Add your final accuracy here)
* Cross-validation score: (Add score)
* Confusion Matrix
* Precision, Recall, F1-score

---

## 📈 Feature Importance

Analyzed feature importance to understand which variables influenced survival most:

* Sex
* Pclass
* Fare
* Age

This improved interpretability of the model.

---

## 📁 Project Structure

```
├── data/
├── notebooks/
├── model_training.py
├── requirements.txt
└── README.md
```

---

## 🚀 Future Improvements

* Compare with Logistic Regression & XGBoost
* Deploy using Flask/Streamlit
* Perform advanced feature engineering

---

## 📚 What I Learned

* Importance of feature engineering
* Hyperparameter tuning improves model performance
* Cross-validation prevents overfitting
* Ensemble learning concepts in depth

---

⭐ *This project strengthened my understanding of ensemble methods and model optimization in Machine Learning.*
