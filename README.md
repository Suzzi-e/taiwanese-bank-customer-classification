# Taiwanese Bank Customer Classification
python · machine-learning · data-science · classification · scikit-learn · pandas · data-analysis

## Project Overview

This project is a machine learning classification project focused on predicting whether a bank customer will subscribe to a term deposit.

The project was completed as a group capstone project virtually at Dedan Kimathi University of Technology (DeKUT), with a focus on applying the machine learning workflow to a real-world banking dataset.

The project involved data exploration, preprocessing, feature selection, model development, hyperparameter tuning, and evaluation.

---

## Problem Statement

Banks conduct marketing campaigns to reach customers who may be interested in their financial products. However, contacting customers who are unlikely to subscribe can result in inefficient use of time and resources.

The objective of this project was to develop classification models that could predict whether a customer would subscribe to a term deposit based on information available about the customer and the marketing campaign.

This can potentially help financial institutions identify customer groups that are more likely to respond positively to marketing campaigns.

---

## Dataset

The project uses a Taiwanese banking marketing dataset containing information about customers and their interactions with a bank's marketing campaign.
[View the original dataset](https://archive.ics.uci.edu/dataset/222/bank%2Bmarketing)

The features include information relating to areas such as:

* Customer demographics
* Financial information
* Contact information
* Marketing campaign details

The target variable represents whether the customer subscribed to a term deposit.

---

## Exploratory Data Analysis

Exploratory data analysis was performed to understand the structure and characteristics of the dataset.

The analysis included:

* Examining the distribution of the target variable
* Exploring relationships between features and the target
* Identifying patterns within customer characteristics
* Investigating categorical and numerical variables
* Visualizing relevant patterns in the data

These steps helped inform the preprocessing and modelling stages.

---

## Data Preprocessing

Before training the models, the data was prepared for machine learning.

The preprocessing workflow included steps such as:

* Cleaning and preparing the dataset
* Selecting relevant features
* Encoding categorical variables
* Preparing the target variable
* Splitting the data into training and testing sets
* Preparing the feature matrix for model training

---

## Machine Learning Models

Three classification approaches were explored:

### 1. Logistic Regression

Logistic Regression was used as a baseline classification model for predicting the probability of a customer subscribing to a term deposit.

### 2. Decision Tree

A Decision Tree classifier was trained to capture potentially non-linear relationships between customer characteristics and the target variable.

### 3. Random Forest

A Random Forest classifier was also developed. Hyperparameter tuning was performed to improve the model's performance.

---

## Model Evaluation

The models were evaluated using **accuracy** and **F1-score**.

F1-score was particularly useful because the classification problem involved an imbalance between the target classes.

| Model                   | Accuracy | F1-score |
| ----------------------- | -------: | -------: |
| Logistic Regression     |   71.03% |   48.24% |
| Decision Tree           |   77.53% |   51.37% |
| Tuned Random Forest     |   77.35% |   51.79% |
| Majority Class Baseline |   78.12% |        — |

The majority-class baseline was included as a reference point when interpreting model accuracy.

The results demonstrate why relying on accuracy alone can be misleading for an imbalanced classification problem. Although the baseline achieved a higher accuracy than the trained models, the machine learning models provided additional predictive information about the minority class, which is reflected more clearly by the F1-score.

---

## Key Takeaways

Some of the key lessons from this project were:

* Real-world datasets often require substantial preprocessing before machine learning can be applied.
* Accuracy should not be considered in isolation when dealing with imbalanced classification problems.
* F1-score can provide additional insight into a model's ability to correctly identify the relevant class.
* Different machine learning algorithms can produce noticeably different results on the same dataset.
* Hyperparameter tuning can affect model performance.
* Establishing a simple baseline is useful when determining whether a machine learning model provides meaningful improvement.

---

## Technologies & Tools

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Scikit-learn**
* **Jupyter Notebook / Google Colab**
* **GitHub**

---

## Project Presentation

[View the Project Presentation](./GROUP-7%20-Capstone-Presentation.pdf)

---

## Skills Demonstrated

This project provided practical experience with:

* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Data visualization
* Feature preparation
* Classification algorithms
* Model evaluation
* Hyperparameter tuning
* Handling imbalanced classification problems
* Python-based data analysis
* Interpreting machine learning results

---
