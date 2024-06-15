## Project Overview
The primary objective of this project is to understand the factors influencing a traveler's decision to switch their mode of transportation and predict the likelihood of this switch using various machine learning models. This can help in planning and improving transportation services.

## Dataset Description

- **Age_Group** : Age of the traveller

- **P_Use** : Primary use of transportation by the traveller

**Type** : By which type of transportation the traveller prefer to travel (public/private/both)

**Frequency** : How many times the traveller travels in a week

**Expense** : Amount spent on travelling per month

**Mode** : Which mode of transportation do they prefer

**c_Time** : Time spent during travelling

**Distance** : How much distance do the ttraveller travels

**switch_p** : How likely the traveller wants to change their type of transportation (public to private) out of 5

**Reasons** : Why the traveller prefer the particular type of transportation chosen by them

***New Column***-

**Switch** : Likely to change mode from private to public and vice-versa
              (0 = not likely to change, 1= likely to change)

## Exploratory Data Analysis (EDA)
Comprehensive EDA was performed, including:
- Numerical and categorical data analysis
- Visualizations to understand distributions, correlations, and trends

## Data Preparation
Data preparation steps include:
- Handling missing values
- Encoding categorical variables
- Normalizing/standardizing numerical variables

## Feature Engineering
New features were engineered to enhance model performance, such as:
- Time of travel categorized into different periods (e.g., morning, afternoon, evening)
- Expense per distance unit

## Modeling
Several machine learning models were employed and cross-validated:
- Decision Tree
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Random Forest Classifier (RFC)
- Naive Bayes

## Evaluation
Models were evaluated using cross-validation techniques. Metrics considered include:
- Accuracy
- Precision
- Recall
- F1 Score

## Results
The performance of each model was compared, and the best-performing model(s) were identified based on the evaluation metrics.
