# Titanic Survival Prediction Challenge

## Overview

Goal is to predict the survival outcomes of passengers aboard the Titanic based on given datasets. The competition provides two datasets:

- `train.csv`: Contains details of a subset of passengers (891) along with their survival status (ground truth).
- `test.csv`: Contains similar passenger information but lacks survival information.

Your task is to train a predictive model using the information provided in `train.csv` and apply it to predict the survival outcomes for the passengers in `test.csv`.

## Dataset Description

- `train.csv`: This dataset includes the following columns:
  - PassengerId: Unique identifier for each passenger
  - Survived: Binary indicator (0 or 1) for survival (1 = survived, 0 = not survived)
  - Pclass: Ticket class (1, 2, or 3)
  - Name: Passenger's name
  - Sex: Gender of the passenger (male or female)
  - Age: Age of the passenger
  - SibSp: Number of siblings/spouses aboard
  - Parch: Number of parents/children aboard
  - Ticket: Ticket number
  - Fare: Fare paid for the ticket
  - Cabin: Cabin number
  - Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

- `test.csv`: Similar to `train.csv` but without the 'Survived' column.

## Challenge Steps

1. **Exploratory Data Analysis (EDA):** Understand the structure of the dataset, identify missing values, and explore relationships between features.

2. **Data Preprocessing:** Handle missing values, encode categorical variables, and prepare the data for modeling.

3. **Feature Engineering:** Create new features or transform existing ones to enhance predictive power.

4. **Model Training:** Use machine learning algorithms to train a model on the `train.csv` dataset.

5. **Prediction:** Apply the trained model to predict survival outcomes for passengers in the `test.csv` dataset.

6. **Evaluation:** Assess the performance of your model using appropriate evaluation metrics.

##Instructions

1. Develop and train your model using the provided datasets.

2. Generate predictions for the passengers in the `test.csv` dataset.

3. Format your predictions as a CSV file with columns 'PassengerId' and 'Survived'.


## Good luck, and may the best model win!
