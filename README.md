# Titanic Survival Prediction

## Overview
This project aims to predict the survival of passengers aboard the Titanic using machine learning techniques. The dataset includes various features such as passenger class, gender, age, and other attributes that may influence survival.

## Dataset
The dataset used in this project is derived from the Titanic machine learning competition on Kaggle. It includes the following key features:

- **PassengerId**: Unique identifier for each passenger.
- **Pclass**: Passenger class (1st, 2nd, or 3rd).
- **Name**: Name of the passenger.
- **Sex**: Gender of the passenger.
- **Age**: Age of the passenger.
- **SibSp**: Number of siblings/spouses aboard.
- **Parch**: Number of parents/children aboard.
- **Ticket**: Ticket number.
- **Fare**: Fare paid for the ticket.
- **Cabin**: Cabin number (if available).
- **Embarked**: Port of embarkation (C = Cherbourg; Q = Queenstown; S = Southampton).

## Methodology
1. **Data Preprocessing**:
   - Handled missing values.
   - Encoded categorical variables.
   - Normalized numerical features.
  
2. **Model Development**:
   - Developed a neural network model to predict survival.
   - Emphasized accuracy and validation through various metrics.

3. **Submission**:
   - The final predictions were saved in a clean CSV format for submission.

## Results
- **Public Score**: 0.77751

## Requirements
- Python 3.x
- Libraries: `pandas`, `numpy`, `scikit-learn`, `tensorflow`, `keras`

## Usage
1. Clone this repository:
   ```bash
   git clone <repository_url>
