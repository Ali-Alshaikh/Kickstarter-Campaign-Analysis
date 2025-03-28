# Kickstarter Campaign Analysis

## Overview

This repository contains a machine learning pipeline for analyzing Kickstarter campaign data. The notebook in this repository performs data preprocessing, feature engineering, and model training using Random Forest and Gradient Boosted Trees. The goal is to predict the amount of money pledged for a campaign based on various features.


# Sample Output

<img width="721" alt="form and prediction" src="https://github.com/user-attachments/assets/5b90063d-89e9-41a2-94d5-5f23f17d3ca8" />






the following description is based on the `final_functions.ipynb` located in the `Machine Learning Learner` file: 

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
   1. 95% training, 5% testing split
   2. 20% validation split from training data

### Model Training:

Decision Tree Regressor

Random Forest Regressor with hyperparameter tuning

Gradient Boosted Trees with hyperparameter tuning


### Feature Importance Analysis:

Identifies most impactful features using Random Forest importance scores


# How to Run

1. Clone the repository

2. Run the `final_functions.ipynb` Jupyter notebook from start to end - `make sure to do this`

3. Run the Graphical user interface notebook -> `UI_ML.ipynb`:
     1. make sure to press the `save changes` button in the FORM in the picture below- THE GREEN BUTTON

   <img width="1426" alt="image" src="https://github.com/user-attachments/assets/f11056b7-b827-493b-9f19-db263b7b56b2" />


# Model Performance

The notebook implements a **weighted prediction** based on a combination of two models (Random Forest and Gradient Boosted Trees) to predict Kickstarter campaign success. The model’s performance is evaluated using RMSE:

**Evaluation Metric:** RMSE calculated for training and validation data.

# Future Improvements

- Experiment with Gradient Boosted Trees

- Tune hyperparameters further for improved accuracy

- Apply cross-validation for more robust evaluation

- use new update data 2025, the data is from 2009-2012
  
- Make a deep learning neural network 

- Deploy as an API for real-time predictions

# Contributing

- Pull requests are welcome! If you have suggestions or improvements, feel free to submit an issue or contribute to the repository.

# Contact

For any inquiries or contributions, feel free to reach out via GitHub issues or discussions!


# Happy Ramadan 🌙
