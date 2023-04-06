# ML_Titanic_Survival_Prediction

## README

This repository contains a Python script for performing logistic regression on the Titanic dataset. The script uses the pandas and numpy libraries for data manipulation, and the scikit-learn library for building and evaluating a logistic regression model.

Files

- train.csv: Training data for the Titanic dataset
- test.csv: Testing data for the Titanic dataset
- gender_submission.csv: A sample submission file in the correct format for the competition

Python script for performing logistic regression on the Titanic dataset

Usage

To run the script, you will need to have Python 3 and the following libraries installed:

- pandas
- numpy
- scikit-learn
You can install these libraries using pip by running:


pip install pandas numpy scikit-learn

To execute the script, simply run the following command in your terminal:



The script will read in the training and testing data from the train.csv and test.csv files, respectively, and drop unnecessary columns such as Name, Ticket, Fare, and Cabin. It then fills in missing values for the Age and Embarked columns with the mean and mode, respectively. The script then replaces string values with numerical values for the Sex and Embarked columns, and drops any duplicated rows in the data.

The script then builds a logistic regression model on the training data, and evaluates its performance using the testing data. The predicted survival outcomes are then written to a submission file in the correct format for the Kaggle competition.

### Acknowledgments

This script was written for the Titanic Kaggle competition, which can be found at the following link: https://www.kaggle.com/c/titanic. The dataset used in this script was obtained from the competition website.
