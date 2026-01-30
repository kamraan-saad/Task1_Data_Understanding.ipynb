# Dataset Analysis Report – Titanic Dataset

## 1. Dataset Overview
The Titanic dataset contains information about passengers such as age, gender, passenger class, fare, and survival status. Each row represents an individual passenger, and each column represents a specific feature.

## 2. Understanding the Dataset Structure
The dataset was loaded using Pandas. The first and last few records were examined to understand the overall structure, number of columns, and type of data stored in each column.

## 3. Data Types Identification
The dataset contains different types of features:
- Numerical: Age, Fare, SibSp, Parch
- Categorical: Sex, Embarked, Ticket, Cabin
- Ordinal: Pclass (Passenger class with an inherent order)
- Binary: Survived (0 = Did not survive, 1 = Survived)

## 4. Target Variable and Input Features
The target variable in this dataset is **Survived**, which indicates whether a passenger survived the Titanic disaster. The remaining columns act as input features for machine learning models.

## 5. Data Analysis Using Pandas Functions
The `df.info()` function was used to analyze data types and identify missing values. The `df.describe()` function provided statistical summaries such as mean, standard deviation, minimum, maximum, and quartile values for numerical features.

## 6. Data Quality Issues
Some data quality issues were observed:
- Missing values in the Age, Cabin, and Embarked columns
- Cabin has a large number of missing entries
- Slight imbalance in the target variable (Survived)

## 7. Machine Learning Suitability
The dataset has an appropriate size and contains meaningful features for a classification problem. After handling missing values and encoding categorical variables, it is suitable for machine learning models.

## 8. Conclusion
Understanding the dataset before applying machine learning techniques is essential. This task helped in identifying feature types, data quality issues, and assessing the dataset’s readiness for machine learning applications.

Added dataset analysis report
