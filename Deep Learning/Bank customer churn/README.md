# Bank-Customer-Churn
The story: A bank is investigating a very high rate of customer leaving the bank. Here is a 10.000 records dataset to investigate and predict which of the customers are more likely to leave the bank soon.  The story of the story: I'd like to compare several techniques (better if not alone, and with the experience of several people) to improve my basic knowledge on Machine Learning.
Dataset was gotten from www.kaggle.com.

## Business Problem

The aim is to predict whether a bank's customers leave the bank or not.
The event that defines customer cancellation is the customer closing his bank account.

## Data Set Information:

It consists of 10000 observations and 12 variables.
Independent variables contain information about customers.
Dependent variable expresses customer churn status.

## Attribute Information:

Surname : Customers' surname

CreditScore : Credit score achieved

Geography : Germany, France, Spain

Gender : Female, Male

Age : Customers' age

Tenure : Numer of years

Balance : Money

NumOfProducts : Number of bank products used

HasCrCard : The state of having credit card or not

IsActiveMember : The state of active membership

EstimatedSalary : Customer's estimated salary

Exited : Churn or not

-----------------------------------------------------------------------------------------------------------------------------------------------------------------

## EDA and Preprocessing

### Null values
<img src="Figures/Fig1.png">

## Analyze Categorical columns

<img src="Figures/Fig2.png">
<img src="Figures/Fig3.png">
<img src="Figures/Fig4.png">
<img src="Figures/Fig5.png">

## Analyze Numerical columns

<img src="Figures/Fig6.png">
<img src="Figures/Fig7.png">
<img src="Figures/Fig8.png">
<img src="Figures/Fig9.png">
<img src="Figures/Fig10.png">
<img src="Figures/Fig11.png">

<p>There is negative skewnwss in Creditscore & balance columns, will handel by applying square.</p>
## Bivariate Analysis against the traget

<img src="Figures/Fig12.png">
<img src="Figures/Fig13.png">
<img src="Figures/Fig14.png">
<img src="Figures/Fig15.png">
<img src="Figures/Fig16.png">
<img src="Figures/Fig17.png">

## Target column

<img src="Figures/Fig18.png">
<p> Since the target column is  imbalanced, used <b>RandomUnderSampler</b> & <b>RandomOverSampler</b> </p>

## Neural Network

<p> Standardization using <b>StandardScaler</b> </p>
<img src="Figures/Fig19.png">

## RandomUnderSampler

<img src="Figures/Fig20.png">

## RandomOverSampler

<img src="Figures/Fig21.png"> 
