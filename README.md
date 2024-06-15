## Project Overview
The primary objective of this project is to understand the factors influencing a traveler's decision to switch their mode of transportation and predict the likelihood of this switch using various machine learning models. This can help in planning and improving transportation services.

## Data Description
The dataset includes the following fields:
- `age`: Age of the traveler
- `purpose_of_transportation`: Purpose of the travel (e.g., work, leisure)
- `time`: Time of travel
- `expense`: Expense incurred during travel
- `distance`: Distance covered in the travel
- `mode`: Current mode of transportation (e.g., bus, car, bike)
- `reason_for_choosing_mode`: Reason for choosing the current mode of transportation

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
