# 🚢 Titanic Survival Prediction using Logistic Regression

## 📌 Project Overview

This project is an end-to-end machine learning classification project that predicts whether a passenger survived the Titanic disaster using **Logistic Regression**.

The project covers the complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and evaluation using Scikit-learn.

---

## 📂 Dataset

The project uses the famous **Titanic Dataset**, which contains passenger information such as:

* Passenger Class
* Gender
* Age
* Fare
* Number of Siblings/Spouses
* Number of Parents/Children
* Port of Embarkation
* Survival Status

Target Variable:

* **Survived**

  * 0 → Did Not Survive
  * 1 → Survived

---

## 🚀 Project Workflow

### 1. Data Exploration

* Loaded the dataset using Pandas
* Explored dataset shape and structure
* Checked missing values
* Analyzed target variable distribution

### 2. Data Preprocessing

* Filled missing values in the **Age** column using the median
* Filled missing values in the **Embarked** column using the mode
* Removed unnecessary columns:

  * PassengerId
  * Name
  * Ticket
  * Cabin
* Encoded categorical variables:

  * Sex
  * Embarked

### 3. Exploratory Data Analysis (EDA)

Visualized important relationships including:

* Survival Count
* Survival by Gender
* Survival by Passenger Class

### 4. Data Preparation

* Separated features and target variable
* Performed Train-Test Split
* Applied Feature Scaling using **StandardScaler**

### 5. Model Building

* Implemented **Logistic Regression** using Scikit-learn
* Trained the model on the training dataset

### 6. Model Evaluation

Evaluated the model using:

* Accuracy Score
* Confusion Matrix
* Classification Report

---

## 📊 Results

**Model:** Logistic Regression

**Test Accuracy:** **80%**

Classification Metrics:

* Precision: **0.77**
* Recall: **0.73**
* F1-Score: **0.75**

The model achieved good performance for a baseline Logistic Regression classifier on the Titanic dataset.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📚 Key Concepts Applied

* Data Cleaning
* Missing Value Handling
* Feature Encoding
* Exploratory Data Analysis (EDA)
* Train-Test Split
* Feature Scaling
* Logistic Regression
* Model Evaluation
* Binary Classification

---

## 📈 Future Improvements

Potential improvements for this project include:

* Hyperparameter tuning
* Feature engineering
* Cross-validation
* Comparing Logistic Regression with:

  * Decision Tree
  * Random Forest
  * Gradient Boosting
* ROC Curve and AUC evaluation

---

## 🎯 Learning Outcome

This project helped strengthen my understanding of the complete supervised machine learning workflow using Scikit-learn—from preprocessing and feature engineering to model training and evaluation.

---

### ⭐ If you found this project interesting, feel free to explore the code and share your feedback!
