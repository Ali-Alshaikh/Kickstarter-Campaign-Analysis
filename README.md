# Kickstarter Campaign Analysis

## Overview

This repository contains a machine learning pipeline for analyzing Kickstarter campaign data. The notebook in this repository performs data preprocessing, feature engineering, and model training using Random Forest and Gradient Boosted Trees. The goal is to predict the amount of money pledged for a campaign based on various features.

## Features

### Data Cleaning & Preprocessing:

1. Removing unnecessary columns

2. Handling missing values

3. Converting categorical variables

4. Feature engineering for reward levels

### Outlier Handling & Transformations:

1. Log transformation of skewed columns

2. Interquartile Range (IQR) method for outlier removal

3. Train/Test Split:

95% training, 5% testing split

20% validation split from training data

### Model Training:

Decision Tree Regressor

Random Forest Regressor with hyperparameter tuning

### Feature Importance Analysis:

Identifies most impactful features using Random Forest importance scores

# Installation

To set up the environment and install dependencies, run:

## Clone the repository:

1. Run the Jupyter notebook:

Data Processing Steps

Load Kickstarter campaign data

Perform feature engineering

Handle missing values and outliers

Train machine learning models

Evaluate model performance using RMSE

Identify key predictive features

# Model Performance

The notebook implements a Decision Tree and a Random Forest model to predict Kickstarter campaign success. The model performance is evaluated using RMSE:

Decision Tree: RMSE calculated for training and validation data

Random Forest: Uses optimized hyperparameters to reduce overfitting

# Future Improvements

Experiment with Gradient Boosted Trees

Tune hyperparameters further for improved accuracy

Apply cross-validation for more robust evaluation

Deploy as an API for real-time predictions

# Contributing

Pull requests are welcome! If you have suggestions or improvements, feel free to submit an issue or contribute to the repository.

# License

This project is licensed under the MIT License. See LICENSE for details.

# Contact

For any inquiries or contributions, feel free to reach out via GitHub issues or discussions!

