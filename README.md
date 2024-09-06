# Titanic Survival Prediction

This project focuses on predicting the survival of passengers aboard the Titanic using machine learning techniques. The dataset includes features like `PassengerId`, `Survived`, `Pclass`, `Name`, `Sex`, `Age`, `SibSp`, `Parch`, `Ticket`, `Fare`, `Cabin`, and `Embarked`. The goal is to classify passengers as survivors or non-survivors based on these features.

## Project Overview
The Titanic classification project demonstrates the end-to-end workflow of a data science project. The workflow includes data preprocessing, exploratory data analysis (EDA), feature engineering, model selection, and model evaluation.

### Key Components:
1. **Importing Necessary Libraries**  
   Libraries like `pandas`, `numpy`, `matplotlib`, `seaborn`, and `scikit-learn` are used for data manipulation, visualization, and machine learning model implementation.

2. **Data Preprocessing and Cleaning**  
   Handle missing values, clean incorrect or inconsistent data, and prepare the dataset for analysis by converting categorical variables into numerical representations.

3. **Exploratory Data Analysis (EDA)**  
   Visualize data and derive insights from features such as `Age`, `Sex`, `Pclass`, and `Fare`. Understand the distribution of features and how they correlate with survival rates.

4. **Feature Engineering**  
   Create new features from the existing ones to improve model performance, such as extracting titles from the `Name` feature, categorizing `Age`, and encoding categorical variables like `Sex` and `Embarked`.

5. **Model Selection and Training**  
   Train multiple machine learning models, including Decision Trees to predict passenger survival. Perform hyperparameter tuning for each model.

6. **Model Evaluation and Performance Metrics**  
   Evaluate the performance of each model using metrics like accuracy, precision, recall, F1-score, and confusion matrix. Select the best model based on the evaluation metrics.

## Dataset
The dataset used in this project contains the following columns:
- **PassengerId**: Unique identifier for each passenger.
- **Survived**: Survival status (0 = No, 1 = Yes).
- **Pclass**: Ticket class (1 = 1st class, 2 = 2nd class, 3 = 3rd class).
- **Name**: Passenger's name.
- **Sex**: Gender of the passenger.
- **Age**: Age of the passenger.
- **SibSp**: Number of siblings/spouses aboard the Titanic.
- **Parch**: Number of parents/children aboard the Titanic.
- **Ticket**: Ticket number.
- **Fare**: Passenger fare.
- **Cabin**: Cabin number.
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).
