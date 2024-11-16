
# Census Income Prediction

The Census Income Prediction project aims to predict whether individuals earn more than $50,000 annually based on census data and to uncover patterns related to economic inequality. This project involves the use of various machine learning algorithms to analyze socio-economic factors and identify key predictors of income.

## Problem Setting
Predict Income: Develop a model to classify whether individuals earn more than $50,000 annually.

## Data
The dataset used is the Adult Census Income dataset from the 1994 Census Bureau. It includes the following features:

Age: Age of the individual

Work Class: Employment status

Final Weight (fnlwgt): Estimated number of people the census entry represents

Education: Highest level of education achieved

Education Number: Numerical representation of education level

Marital Status: Marital status of the individual

Occupation: Type of occupation

Relationship: Relative status to others

Race: Race of the individual

Sex: Biological sex

Capital Gain: Capital gains

Capital Loss: Capital losses

Hours Per Week: Hours worked per week

Native Country: Country of origin

Label: Income level (<=50k or >50k)

## Data Visualization
Key visualizations include:

Age Distribution: Most individuals are between 20 and 40 years old.

Education vs. Income: Higher education levels correlate with higher income.

Gender Distribution: Dataset is male-dominated.

Marital Status Distribution: Most individuals are married.

## Model Exploration
We explored the following classification algorithms:

Logistic Regression

KNN Classifier

Support Vector Classifier

Naïve Bayes Classifier

Decision Tree Classifier

Random Forest Classifier

## Model Results
Performance metrics for key models:

Logistic Regression: Accuracy of 80.97%

KNN Classifier: Accuracy of 83.45%

Support Vector Classifier: Accuracy of 81.76%

Naïve Bayes Classifier: Accuracy of 68.19%

Decision Tree Classifier: Accuracy of 91.41%

Random Forest Classifier: Accuracy of 92.23%, improved to 92.37% with hyperparameter tuning

<img width="585" alt="image" src="https://github.com/user-attachments/assets/c080fa99-9dbf-4cef-8b4c-b4c14eb6d0cf">

## Performance Summary
The Decision Tree and Random Forest classifiers demonstrated exceptional performance in predicting income.





