Machine Learning Classification Project
📌 Project Overview

The Titanic Survival Prediction project aims to build a machine learning model that predicts whether a passenger survived the Titanic disaster based on their personal and travel information. This is a classical binary classification problem widely used to learn data cleaning, feature engineering, and predictive modeling.

🎯 Objective

To predict the survival status (0 = No, 1 = Yes) of Titanic passengers using machine learning by analyzing features such as gender, age, passenger class, family size, and fare.

📊 Dataset Description

The dataset contains demographic and travel details of Titanic passengers. Key features include:

Pclass – Passenger class (1st, 2nd, 3rd)

Sex – Gender of passenger

Age – Age in years

SibSp – Number of siblings/spouses aboard

Parch – Number of parents/children aboard

Fare – Ticket fare

Embarked – Port of embarkation

Survived – (Target variable)

🔧 Methodology
1. Data Preprocessing

Handled missing values (Age, Cabin, Embarked)

Converted categorical features to numerical form

Removed irrelevant columns (Name, Ticket, Cabin)

Created new engineered features such as:

FamilySize

IsAlone

Title Extraction (Mr, Mrs, Miss, etc.)

2. Exploratory Data Analysis (EDA)

Key findings:

Females had a significantly higher survival rate

1st class passengers survived more than 2nd & 3rd classes

Children had higher chances of survival

Higher fare was linked to higher survival probability

3. Model Building

Trained multiple machine learning algorithms:

Logistic Regression

Decision Tree

Random Forest

Support Vector Machine (SVM)

KNN

4. Model Evaluation

Evaluated models using:

Accuracy Score

Confusion Matrix

Cross-Validation

The Random Forest model performed the best with high accuracy and good generalization.

🧠 Result

The final model successfully predicts passenger survival with strong accuracy and captures key patterns such as:

“Women and children first”

Higher survival among first-class passengers

Effect of family size on survival chances

🏁 Conclusion

This project demonstrates:

Complete ML workflow (preprocessing → modelling → evaluation)

Feature engineering importance

Practical application of classification models

How demographic and socioeconomic factors relate to survival in real scenarios

📂 Tools & Technologies

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-Learn

Jupyter Notebook