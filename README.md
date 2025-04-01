## Titanic Survival Prediction

This repository contains a machine learning model that predicts whether a passenger survived the Titanic disaster based on various features such as age, gender, ticket class, fare, and cabin information.

# Dataset

The dataset includes the following features:

Pclass (Ticket Class: 1st, 2nd, 3rd)

Sex (Male/Female)

Age

SibSp (Number of siblings/spouses aboard)

Parch (Number of parents/children aboard)

Fare (Passenger fare)

Cabin (Cabin number, if available)

Embarked (Port of embarkation: C, Q, S)

# Preprocessing Steps

Handling Missing Values:

Fill missing Age values using the median.

Fill missing Embarked values with the mode.

Drop the Cabin column due to excessive missing values.

Encoding Categorical Variables:

Convert Sex and Embarked into numerical values using Label Encoding.

Feature Scaling:

Normalize numerical features (Age, Fare) using StandardScaler.

Splitting Data:

Split the dataset into training (80%) and testing (20%) sets.

#Model Selection

We implemented Logistic Regression model and evaluated model performance:

#Model Evaluation

The model is evaluated based on:

Accuracy

Precision

Recall

F1-score

Confusion Matrix

#Expected Outcome

The best-performing model is selected based on the evaluation metrics to ensure strong survival prediction accuracy.

# How to Run

Clone this repository:

git clone https://github.com/Yashw2121/titanic_survival_prediction.git
cd titanic_survival_prediction

Install dependencies:

pip install -r requirements.txt

Run the notebook or Python script to train and evaluate the model.

# Contributors

Yash Waghmare

