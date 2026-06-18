# Disease Prediction Using Machine Learning

## Overview

This project is a Machine Learning-based Disease Prediction System that predicts whether a patient is diabetic or non-diabetic based on medical parameters. The project uses multiple machine learning algorithms and compares their performance.

## Features

* Dataset loading and preprocessing
* Feature and target separation
* Train-test data splitting
* Logistic Regression model
* Random Forest Classifier model
* Support Vector Machine (SVM) model
* Model performance evaluation
* Confusion Matrix
* Classification Report
* Feature Importance Analysis
* New Patient Prediction
* Probability Prediction
* Model Saving using Joblib

## Dataset

The project uses the Pima Indians Diabetes Dataset.

Features:

* Pregnancies
* Glucose
* Blood Pressure
* Skin Thickness
* Insulin
* BMI
* Diabetes Pedigree Function
* Age

Target:

* Outcome (0 = Non-Diabetic, 1 = Diabetic)

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Joblib

## Machine Learning Models

### Logistic Regression

Used as the baseline classification model.

### Random Forest Classifier

Used to improve prediction performance and analyze feature importance.

### Support Vector Machine (SVM)

Used for additional model comparison.

## Project Workflow

1. Load Dataset
2. Data Preprocessing
3. Feature Selection
4. Train-Test Split
5. Model Training
6. Prediction
7. Model Evaluation
8. Model Comparison
9. Save Trained Model

## Results

The models were evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report

The best-performing model was saved for future predictions.

## How to Run

### Clone Repository

```bash
git clone <repository-url>
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Project

```bash
python disease_prediction.py
```

## Future Improvements

* Streamlit Web Application
* Better User Interface
* Hyperparameter Tuning
* Additional Disease Prediction Models
* Deployment on Cloud Platforms

## Author

Aniket Sinha 

## Internship

This project was developed as part of the CodeAlpha Machine Learning Internship.
