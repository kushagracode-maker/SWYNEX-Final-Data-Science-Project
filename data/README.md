# Titanic Survival Prediction — Data Science Project

## Project Overview

This project was developed as part of my Data Science Internship at **SWYNEX Technologies**.

The objective is to analyze the Titanic passenger dataset, identify patterns influencing passenger survival, and build a Machine Learning classification model to predict whether a passenger survived the disaster.

## Problem Statement

The sinking of the Titanic resulted in significant loss of life. This project investigates how passenger characteristics such as age, gender, passenger class, family size, and fare relate to survival.

The goal is to build a baseline classification model using Logistic Regression.

## Dataset

- **Dataset:** Titanic Dataset
- **Source:** [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic)
- **Original dataset:** 891 passenger records
- **Target variable:** `Survived`
  - 0 — Did not survive
  - 1 — Survived

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

## Project Workflow

### 1. Data Preparation

- Loaded and inspected the Titanic dataset.
- Identified missing values.
- Performed data cleaning and preprocessing.
- Handled missing values and prepared features for modelling.
- Checked data types and duplicate records.

### 2. Exploratory Data Analysis (EDA)

Explored passenger survival patterns using visualizations and statistical analysis.

Key variables investigated included:
- Gender
- Passenger class
- Age
- Fare
- Family size

### 3. Model Building

- Implemented Logistic Regression as the baseline classification model.
- Split the dataset into training and testing sets.
- Used preprocessing techniques for model preparation.
- Generated predictions on the test dataset.

### 4. Model Evaluation

The model was evaluated using accuracy, precision, recall, F1-score, classification report, and confusion matrix.

## Model Results

**Model:** Logistic Regression

**Test samples:** 179

| Metric | Score |
|---|---:|
| Accuracy | 80.45% |
| Precision (Survived) | 0.79 |
| Recall (Survived) | 0.67 |
| F1-score (Survived) | 0.72 |
| Macro F1-score | 0.79 |
| Weighted F1-score | 0.80 |

### Confusion Matrix

| Actual / Predicted | Did Not Survive | Survived |
|---|---:|---:|
| Did Not Survive | 98 | 12 |
| Survived | 23 | 46 |

The model correctly classified 144 out of 179 passengers.

## Model Limitations

- Logistic Regression provides a baseline and may not capture complex relationships between passenger features.
- The model's recall for the survived class is lower than its recall for the non-survived class.
- Further feature engineering and hyperparameter tuning may improve performance.
- The dataset represents a historical event and has limitations in terms of available passenger information.

## Conclusion

This project demonstrates an end-to-end Data Science workflow, from data preparation and exploratory analysis to machine learning and model evaluation.

The Logistic Regression baseline achieved **80.45% accuracy** on the test dataset.

The project provided practical experience in data cleaning, visualization, feature preprocessing, classification, and model evaluation.

## Future Improvements

- Experiment with Random Forest and Decision Tree classifiers.
- Perform hyperparameter tuning.
- Explore additional feature engineering techniques.
- Compare multiple classification algorithms.
- Improve recall and overall model performance.

## Repository Structure

```text
SWYNEX-Final-Data-Science-Project/
│
├── data/
│   └── Titanic-Dataset.csv
│
├── notebooks/
│   ├── 01_Data_Preparation.ipynb
│   ├── 02_Exploratory_Data_Analysis.ipynb
│   └── 03_Modeling_and_Evaluation.ipynb
│
├── README.md
└── requirements.txt
```

## Acknowledgement

I would like to thank **SWYNEX Technologies** for providing this internship opportunity and helping me gain practical experience in Data Science and Machine Learning.
