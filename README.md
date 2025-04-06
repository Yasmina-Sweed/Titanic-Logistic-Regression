# Titanic-Logistic-Regression
# Titanic Survival Prediction using Logistic Regression 🚢

This project uses the famous Titanic dataset to build a **Logistic Regression model** that predicts whether a passenger survived or not. The project includes **data preprocessing**, **exploratory data analysis (EDA)**, **model training**, and **evaluation**.

## 📌 Project Overview

The Titanic dataset is a classic classification problem in machine learning. The main goal is to predict passenger survival based on features such as age, sex, class, fare, etc. This project demonstrates:

- How to clean and prepare data
- Perform EDA using visualizations
- Train a logistic regression model
- Evaluate the model using metrics such as accuracy and confusion matrix

---

## 📂 Contents

- `Titanic_Logistic_Regression.ipynb`: Jupyter notebook containing all code and analysis.
- `README.md`: Project documentation.

---

## 📊 Dataset Description

The dataset used is the **Titanic dataset** from Kaggle

- `PassengerId`: Unique ID for each passenger
- `Survived`: Target variable (0 = No, 1 = Yes)
- `Pclass`: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- `Name`, `Sex`, `Age`: Personal information
- `SibSp`, `Parch`: Family relationships
- `Ticket`, `Fare`: Ticket details
- `Cabin`, `Embarked`: Boarding details

---

## 🧹 Data Preprocessing

- Handling missing values (`Age`, `Embarked`)
- Encoding categorical variables (`Sex`, `Embarked`)
- Feature selection
- Data scaling

---

## 📈 Exploratory Data Analysis (EDA)

- Distribution of survival based on gender, class, age
- Visualizations using `matplotlib` and `seaborn`
- Correlation matrix to analyze feature relationships

---

## 🤖 Model Training

A **Logistic Regression** model was used to train on the preprocessed data:


