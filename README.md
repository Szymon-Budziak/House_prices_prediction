# Real Estate House Prices Prediction

---

This repository contains a Jupyter Notebook that demonstrates a comprehensive process for predicting real estate house prices using various machine learning techniques. The notebook walks through data exploration, preprocessing, model training, evaluation, and selection, ultimately culminating in a robust predictive model.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Notebook Overview](#notebook-overview)
  - [1. Data Loading and Initial Exploration](#1-data-loading-and-initial-exploration)
  - [2. Exploratory Data Analysis (EDA)](#2-exploratory-data-analysis-eda)
  - [3. Data Cleaning and Preprocessing](#3-data-cleaning-and-preprocessing)
  - [4. Model Training and Evaluation](#4-model-training-and-evaluation)
  - [5. Hyperparameter Tuning](#5-hyperparameter-tuning)
  - [6. Model Comparison](#6-model-comparison)
  - [7. Final Model and Pipeline](#7-final-model-and-pipeline)
  - [8. Conclusion](#8-conclusion)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project aims to predict real estate hosue prices using a dataset containing various features such as area, furnishing status, and more. It employs multiple machine learning algorithms to find the best model for the task.

## Dataset

The dataset used in this project is a structured CSV file containing information about real estate properties. Key features include price, area, and furnishing status.

## Installation

The project uses Poetry to manage dependencies. To install the dependencies, run the following command:

```bash
poetry install
```

## Notebook Overview

### 1. Data Loading and Initial Exploration

- Load the dataset.
- Display basic statistics and the first few rows of the data.
- Check for unique values and missing data.

### 2. Exploratory Data Analysis (EDA)

- Visualize the distribution of the target variable (price) using histograms and KDE plots.
- Examine the relationship between price and other features using scatter plots and box plots.
- Generate a heatmap to understand feature correlations.
- Create pair plots to visualize relationships between multiple features.

### 3. Data Cleaning and Preprocessing

- Handle binary categorical variables and create dummy variables for other categorical data.
- Standardize or normalize numerical features as needed.

### 4. Model Training and Evaluation

- Train multiple regression models including Linear Regression, Lasso, Ridge, Polynomial Regression, and Random Forest.
- Evaluate models using metrics like R², MSE, and RMSE.

### 5. Hyperparameter Tuning

- Use Optuna for hyperparameter tuning of the Random Forest model to improve performance.

### 6. Model Comparison

- Compare the performance of various models on the training and test sets.
- Visualize and interpret model performance metrics.

### 7. Final Model and Pipeline

- Save the best model using pickle.
- Create a prediction pipeline with the best model and necessary preprocessing steps.
- Demonstrate making predictions with the final model.

### 8. Conclusion

- Summarize findings, model performance, and insights gained from the project.