# Cardiovascular-Risk-Prediction
**Project Type**: Classification

**Project Goal:** The project goal is to predict whether the patient has a 10-year risk of future coronary heart disease (CHD) considering the other features.

**Problem Statement**

The dataset is from an ongoing cardiovascular study on residents of the town of Framingham,Massachusetts.The dataset provides the patient's information. It include over 4,000 records and 15 attributes.
The classification goal is to predict whether the patient has a 10-year risk of future coronary heart disease (CHD) considering the other features.

**Dataset Pipeline**

**Analyze Data:** The first step is to observe data and looked into features line shape, statistical summary, and size of data.

**EDA:** In this step, we explore the data and find some patterns through visualization techniques. It will help us to find the mistakes and unusuality in data.

**Data Cleaning:** It is a process of removing or modifying the inconsistency and inaccuracy in the dataset.

**Feature Selection:** At this step, we encode the categorical features. We identified the most important features using the correlation coefficient, chi-square test, information gain, and an extra tree classifier. Also, we tried to balance the dataset using SMOTE.

**Model Training:** We tried some machine learning algorithms to train the dataset. We also hypertune the data using GridSearchCV and RandomSearchCV.

**Performance Evaluation:** We use some evaluation metrics like accuracy, precision, and recall to compare the algorithm. The evaluation metrics help in finding the best algorithm.

**Conclusion**

- There are a total of 3390 records with 17 attributes.

- In feature engineering, we tried to balance data using SMOTE.

- Since the data is concerned with the healthcare industry, we closely observe the features that directly effects the target variable.

- Also, in the healthcare industry recall is the most important evaluation metric as it is more valid to predict true positive results.

- KNN and XGBoost are performing well. KNN with an accuracy of 88.4% and a recall percentage of 93.5%.

- XGboost has higher accuracy of around 90.9% but the recall percentage is lower than KNN.

- Decision trees are also doing moderately well but decision trees are more prone to overfitting. So, we can't rely on it. That's why we have chosen KNN as our final machine-learning model.
