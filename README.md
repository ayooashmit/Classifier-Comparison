# FASTag Fraud Detection

This project analyzes FASTag transaction data to detect fraud using machine learning.

## Dataset

* Source: FASTag transaction logs.
* Columns include: `Vehicle_Type`, `TollBoothID`, `Lane_Type`, `Payment_Status`, etc.
* Initial processing included missing value checks, duplicate removal, and summary statistics.

## Models Used

* **Logistic Regression**
* **Decision Tree**
* **Support Vector Machine**
* **K-Nearest Neighbors**
* **Random Forest**

Each model was evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

## Goal

Compare classification models to detect FASTag fraud effectively.
