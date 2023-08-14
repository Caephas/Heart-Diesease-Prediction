# Heart Disease Prediction

This repository contains a simple implementation of a heart disease prediction system using logistic regression, a model well-suited for binary classification problems. The prediction is based on various features like age, sex, chest pain type, resting blood pressure, and more.

## Steps involved

### 1. Importing dependencies

Necessary libraries and modules like `numpy`, `pandas`, `sklearn` are imported.

### 2. Data Collection and Processing

- The dataset is loaded from a CSV file named `heart.csv`.
- The columns are rearranged to move the 'target' column to the end and the modified dataset is saved as `heart-data.csv`.
- Basic dataset information and statistics are displayed, including checking for any missing values.

### 3. Understanding the Target Variable

The distribution of the 'target' variable is checked, where:

- `1` signifies a defective heart.
- `0` signifies a healthy heart.

### 4. Data Splitting

Features and target variables are split into X and Y, respectively. Subsequently, the data is divided into training and test sets.

### 5. Model Training

The Logistic Regression model is chosen for its efficacy in binary classification problems. The model is trained using the training data.

### 6. Model Evaluation

The model's accuracy is determined on both training and test data.

### 7. Building the Predictive System

A sample input is passed to the trained model to predict whether a person has heart disease.

## Usage

The final part of the code uses the trained model to make a prediction based on a sample input. To test with different inputs, simply modify the `input_data` tuple.

## Dependencies

- numpy
- pandas
- scikit-learn

## Dataset

The dataset used for this project is `heart.csv`. Ensure this file is in the same directory as the code for smooth execution.
