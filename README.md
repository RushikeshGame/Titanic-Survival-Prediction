
# Titanic Survival Prediction

## Project Overview
This project predicts whether a Titanic passenger survived or not using Machine Learning.

## Objective
To build a classification model using passenger attributes and perform:
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Model training
- Model evaluation
- Feature importance
- Inference using a saved model

## Dataset
Titanic dataset containing passenger information such as:
- Passenger class
- Sex
- Age
- SibSp
- Parch
- Fare
- Cabin
- Embarked

## Feature Engineering
The following features were created:
- Title
- FamilySize
- CabinPresence

## Models Used
1. Logistic Regression
2. Decision Tree
3. Random Forest

## Model Evaluation
Accuracy on the test split:

| Model | Accuracy |
|---|---:|
| Logistic Regression | 1.00 |
| Decision Tree | 1.00 |
| Random Forest | 1.00 |

## Feature Importance
Random Forest feature importance was used for model explainability.

Important features included:
- Sex_male
- Title_Mr
- Title_Miss
- Title_Mrs
- Age
- Fare

## Inference Example
A sample passenger was given to the trained Random Forest model.

Prediction:
Not Survived

## Saved Model
The trained model is saved as:

`titanic_survival_model.pkl`

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Joblib
- Google Colab

## Project Files
- `Titanic_Survival_Prediction.ipynb` — Machine Learning notebook
- `titanic_survival_model.pkl` — Saved Random Forest model
- `requirements.txt` — Required Python packages
- `README.md` — Project documentation
