# titanic-survival-prediction
titanic survival prediction using machine learning (tool- Sklearn)
🚢 Titanic Machine Learning Project – Summary
This project involves predicting passenger survival on the Titanic using machine learning techniques. The goal is to build models that can classify whether a passenger survived or not based on features such as age, gender, ticket class, etc.

🔍 Key Steps:
1. Data Loading & Exploration

Loaded the Titanic dataset (train and test sets).

Explored key features like Sex, Age, Pclass, Fare, Embarked, etc.

2. Data Cleaning & Preprocessing

Dropped irrelevant columns: Cabin, Ticket, Name.

Handled missing values:

Filled Age and Fare with median.

Filled Embarked with the mode.

Converted categorical data:

Used Label Encoding or One-Hot Encoding for Sex and Embarked.

3. Feature Engineering

Created new features (optional, if done): e.g., family size, title extraction from names (if you implemented).

Normalized/standardized data (if needed by some models).

4. Model Building

Trained multiple machine learning models:

Logistic Regression

Decision Tree

Random Forest

K-Nearest Neighbors

Support Vector Machine (SVM)

5. Model Evaluation

Evaluated model performance using:

Accuracy score

Confusion matrix

Cross-validation (if applied)

6. Prediction

Made predictions on the test set.

Saved results in the required format for submission.

