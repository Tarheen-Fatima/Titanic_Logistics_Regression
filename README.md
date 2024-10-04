# Titanic Survival Prediction

This project predicts the survival of passengers on the Titanic using logistic regression. The dataset used in this project is the Titanic dataset, which contains information about the passengers such as their class, age, gender, and more.

## Project Overview
The goal of this project is to predict whether a passenger survived the Titanic disaster using logistic regression. The project uses the `Pandas` library for data preprocessing and `scikit-learn` for model building and evaluation.

## Technologies Used
- Python
- Pandas
- Matplotlib
- scikit-learn

## Dataset
The dataset used for this project is the famous [Titanic dataset](https://www.kaggle.com/c/titanic/data), which contains the following key features:
- **Pclass**: Ticket class (1st, 2nd, 3rd)
- **Sex**: Gender of the passenger
- **Age**: Age of the passenger
- **SibSp**: Number of siblings/spouses aboard
- **Parch**: Number of parents/children aboard
- **Fare**: Passenger fare
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)
- **Survived**: Survival status (0 = No, 1 = Yes)

## Model Training
The following steps are performed in the script:
1. Data preprocessing: Filling missing values, encoding categorical variables, and scaling the features.
2. Train-test split: The dataset is split into training (80%) and testing (20%) sets.
3. Model training: A logistic regression model is trained using the training data.
4. Predictions: The model predicts survival for the test set.

## Evaluation
After training the model, the following metrics are computed:
- **Accuracy Score**: Overall accuracy of the model.
- **Confusion Matrix**: Shows true positives, true negatives, false positives, and false negatives.
- **Classification Report**: Provides precision, recall, F1-score, and support for each class.
