# Titanic_Survival_Prediction
A mini machine learning project using Titanic dataset
# 🚢 Titanic Survival Prediction - Machine Learning Mini Project

This project uses the **Titanic dataset** from Kaggle to predict whether a passenger survived the disaster using various features like passenger class, age, gender, fare, and more.

## 📊 Project Overview

- **Goal:** Predict survival of Titanic passengers using machine learning
- **Dataset:** [Kaggle - Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic/data)
- **Model Used:** Logistic Regression
- **Accuracy Achieved:** ~81%

---

## 🛠️ Tools & Libraries

- Python
- Jupyter Notebook
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn

---

## 🧠 Steps Performed

1. **Data Loading & Exploration**
   - Loaded `train.csv` from Kaggle
   - Inspected structure using `.head()` and `.info()`

2. **Data Cleaning**
   - Filled missing values in `Age` and `Embarked`
   - Dropped `Cabin`, `Name`, `Ticket`, `PassengerId`

3. **Exploratory Data Analysis (EDA)**
   - Visualized survival patterns using countplots and boxplots

4. **Data Preprocessing**
   - Converted categorical variables (`Sex`, `Embarked`) to numerical
   - Selected key features for the model

5. **Model Building**
   - Trained a Logistic Regression model
   - Used train-test split to validate

6. **Model Evaluation**
   - Evaluated using accuracy, confusion matrix, and classification report

7. **Custom Prediction**
   - Predicted survival for a sample passenger (e.g., 28-year-old female in 2nd class)

---

## 🔍 Sample Output

```text
🎯 Accuracy: 0.81

📊 Classification Report:
              precision    recall  f1-score   support
           0       0.83       0.87      0.85       105
           1       0.78       0.72      0.75        74

🧍 Survival Prediction: Survived 💚
