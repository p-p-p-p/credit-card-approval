# Project : Predict Credit Card Acceptance <br>
* A small credit card dataset for simple econometric analysis (taken from Kaggle,
originally from William Greene's book Econometric Analysis) [Download link here](https://drive.google.com/file/d/1ZxaThxH4fqtZQxxdgVQcD2dUDULYXLxo/preview)
* Content
  * card: Dummy variable, 1 if application for credit card accepted, 0 if not
  * reports: Number of major derogatory reports
  * age: Age n years plus twelfths of a year
  * income: Yearly income (divided by 10,000)
  * share: Ratio of monthly credit card expenditure to yearly income
  * expenditure: Average monthly credit card expenditure
  * owner: 1 if owns their home, 0 if rent
  * selfempl: 1 if self employed, 0 if not.
  * dependents: 1 + number of dependents
  * months: Months living at current address
  * majorcards: Number of major credit cards held
  * active: Number of active credit accounts
* Goal: Predict whether a credit card application will be accepted based upon various
data about the applicant.
* Split into train and test data and create 4 different types of models from the data -
Decision Trees, Linear Regression, Native Bayes and K-NN
* Do performance evaluation of each model

## Our problem:
Commercial banks receive a lot of applications for credit cards. Many of them get rejected for many reasons, like high loan balances, low income levels, or too many inquiries on an individual's credit report, for example. Manually analysing these applications is mundane, error-prone, and time-consuming and time is money. So, we create a machine learning model for the problem.

## How we are planning to solve the problem.
* First, we will start off by loading and viewing the dataset.
* We will see that the dataset has a mixture of both numerical and non-numerical features, that it contains values from different ranges, plus that it contains a number of missing entries.
* We will have to pre-process the dataset to ensure the machine learning model we choose can make good predictions.
* After our data is in good shape, we will do some exploratory data analysis to build our intuitions.
* Finally, we will build a machine learning model that can predict if an individual's application for a credit card will be accepted.<br>


[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/p-p-p-p/credit-card-approval/blob/main/credit_card_approval.ipynb)

