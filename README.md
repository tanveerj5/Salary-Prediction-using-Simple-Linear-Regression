# Salary Prediction using Simple Linear Regression

This project demonstrates the use of a **simple linear regression** model to predict **salary** based on **years of experience**. It uses the popular dataset `Salary_Data.csv`, where the target variable is the salary, and the feature is the years of experience. The model is trained and tested using the **Scikit-learn** library.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Libraries Required](#libraries-required)
3. [Dataset](#dataset)
4. [Steps for Training the Model](#steps-for-training-the-model)
   - [Step 1: Importing Libraries](#step-1-importing-libraries)
   - [Step 2: Loading the Dataset](#step-2-loading-the-dataset)
   - [Step 3: Splitting the Dataset into Training and Test Sets](#step-3-splitting-the-dataset-into-training-and-test-sets)
   - [Step 4: Training the Model](#step-4-training-the-model)
   - [Step 5: Making Predictions](#step-5-making-predictions)
   - [Step 6: Evaluating the Model](#step-6-evaluating-the-model)
   - [Step 7: Visualizing the Results](#step-7-visualizing-the-results)
5. [Why Feature Scaling is Not Applied](#why-feature-scaling-is-not-applied)
6. [Usage](#usage)
7. [Conclusion](#conclusion)

## Project Overview

This project aims to build a simple linear regression model to predict **salary** based on **years of experience**. The dataset contains two variables: one feature (years of experience) and one target (salary). After training the model on a training dataset and evaluating it on a test dataset, the performance is analyzed using various evaluation metrics. Finally, the results are visualized to understand the model's effectiveness.

## Libraries Required

To run this project, the following libraries are required:
- `pandas`: For loading and manipulating the dataset.
- `numpy`: For numerical operations.
- `matplotlib`: For data visualization.
- `seaborn`: For enhanced data visualization.
- `sklearn`: For machine learning model training and evaluation.

Install the dependencies using:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
