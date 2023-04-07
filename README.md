# Titanic Survival Prediction

This project aims to build a machine learning model that can predict the survival of passengers aboard the Titanic based on various features such as gender, age, class, and fare.

# Dataset
The dataset used for this project is the Titanic dataset available on Kaggle, which contains information about the passengers aboard the Titanic, including whether they survived or not. The dataset has 891 observations and 12 features, including:

PassengerId: Unique ID for each passenger

Survived: Survival (0 = No, 1 = Yes)

Pclass: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)

Name: Passenger name

Sex: Sex of passenger

Age: Age of passenger

SibSp: Number of siblings/spouses aboard

Parch: Number of parents/children aboard

Ticket: Ticket number

Fare: Passenger fare

Cabin: Cabin number

Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

# Requirements
Python 3.x
Jupyter Notebook
Pandas
Numpy
Scikit-learn
Matplotlib
Seaborn

# Installation
To install the required packages, run the following command:

```pip install -r requirements.txt```

# Usage
To run the project, open titanic_survival_prediction.ipynb in Jupyter Notebook and run the cells in order. The notebook contains the following sections:

Exploratory Data Analysis (EDA)
Data Preprocessing
Model Training and Evaluation
Model Comparison

The EDA section includes visualizations of the dataset to gain insights into the relationships between the various features and the target variable (survival). The Data Preprocessing section includes cleaning and transforming the data to prepare it for model training. The Model Training and Evaluation section includes training several machine learning models on the preprocessed data and evaluating their performance using various metrics. Finally, the Model Comparison section compares the performance of the different models and selects the best one for the task.

# Conclusion

The project concludes that the most accurate and reliable model for predicting the survival of passengers aboard the Titanic is the one that is split based on the Sex column. This model achieved an accuracy score of 0.83, precision score of 0.79, recall score of 0.71, and F1 score of 0.75. It performed significantly better than other models and showed good generalization ability.
