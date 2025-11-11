#                                                    Titanic Survival Prediction - Machine Learning Project

## Overview

This project focuses on predicting passenger survival from the Titanic dataset using various machine learning classification algorithms. It follows a structured data science workflow including data preprocessing, feature engineering, model training, and evaluation.

## Dataset

The dataset used is the Kaggle Titanic dataset, which includes features such as:

* Age
* Sex
* Passenger Class (Pclass)
* Number of siblings/spouses aboard (SibSp)
* Number of parents/children aboard (Parch)
* Fare
* Embarkation Port

## Methodology

### 1. Data Preprocessing

* Handled missing values appropriately
* Encoded categorical variables
* Removed irrelevant columns

### 2. Exploratory Data Analysis (EDA)

* Studied survival patterns across gender, age, and ticket class
* Visualized class imbalance and feature relationships

### 3. Feature Engineering

* Created new features to improve predictive power
* Normalized/standardized necessary fields

### 4. Model Training

Applied multiple machine learning models to compare performance:

* K Nearest Neighbors (KNN)
* Naive Bayes
* Support Vector Machine (SVM)
* Decision Tree
* Random Forest

### 5. Model Evaluation

The performance of each model was evaluated using accuracy score on the test set.

#### Model Performance Comparison

| Model                        | Accuracy          |
| ---------------------------- | ----------------- |
| K-Nearest Neighbors (KNN)    | 0.66              |
| Naive Bayes                  | 0.80              |
| Support Vector Machine (SVM) | 0.61              |
| Decision Tree                | 0.79              |
| **Random Forest**            | **0.82** ✅ (Best) |

#### Conclusion

The Random Forest classifier achieved the highest accuracy among all models, demonstrating strong generalization and effective handling of feature interactions.

* Evaluated models based on accuracy and overall prediction performance

## Requirements

```
pip install numpy pandas scikit-learn matplotlib seaborn
```

## Usage

Run the notebook or Python script included in this repository to train the models and view results.

## Future Enhancements

* Hyperparameter tuning for optimal model performance
* Implementing cross-validation
* Exploring neural network models

## License

This project is intended for educational and research purposes.
