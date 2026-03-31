# Final Project — End-to-End Data Preparation Pipeline:
Pick a raw dataset from Kaggle (e.g. House Prices, Titanic, or Customer Churn). Build a complete pipeline from raw file to model-ready feature matrix: load and inspect → EDA with key plots → clean all issues → preprocess all features → split into train/test → save the clean dataset and all plots to an organised output folder. Write a short README.txt summarising the dataset, key findings from EDA, and every preprocessing decision made.

# Project Overview:
I am using the titanic dataset from kaggle. It has 12 columns and 891 rows.

The Numerical Columns include: 
- Age
- Fare

The Categorical columns include:
- Survived
- Pclass
- Sex
- SibSp
- Parch
- Embarked

The target column of this dataset and project is "Survived".

# Key Findings
## Duplicated Data
There are no duplicates in the dataset

## Missing Values
Two columns; Age and Cabin have missing values.

The missing values in the cabin column are completely random (MCAR).

The missing values in the age column are missing due to the factor Pclass. Especially 3rd Pclass.

## Plots
All the important visualized plots have been stored in the plots sub-folder

## EDA
The target column was mostly related to Pclass and Fare. 
- Positive correlation with Fare.
- Negative correlation with Pclass

The median age in Pclass 1 is higher than other classes.

More females survived as compared to males.

Majority passengers of Pclass 3 did not survive.

## Column Seletion:
For features, all columns expect `Survived`, `Name`, `Ticket`, `Cabin`

For target, `Survived`

## Preprocessor Steps
For numerical columns, I used `SimpleImputer` and `StandardScaler`.

For categorical columns, I only used `OneHotEncoding`. Imputer was not needed.


