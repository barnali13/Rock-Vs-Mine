Rock vs Mine Prediction 🎯

This project is a Machine Learning classification model that predicts whether an object detected by sonar is a rock or a mine (metal).
It uses the Sonar Dataset (from the UCI Machine Learning Repository) where each instance is described by 60 features representing sonar signals.

📌 Project Overview

Input: 60 features from sonar signals.

Output: Prediction → Rock (R) or Mine (M).

Algorithm: Logistic Regression

Goal: Build and evaluate a classifier for binary classification.

📂 Dataset

Dataset Name: Sonar Dataset

Source: UCI Machine Learning Repository - Sonar Data

Format: CSV file

Features:

60 numeric values (sonar frequency readings)

1 target label (R for Rock, M for Mine)

⚙️ Tech Stack

Python 3

Libraries:

numpy → numerical operations

pandas → data handling

matplotlib / seaborn → visualization

scikit-learn → model training & evaluation

🚀 Steps in the Project

Import Dependencies

Load Dataset

Data Exploration

Shape of data

Value counts

Statistical summary

Preprocessing

Label encoding target values (R → 0, M → 1)

Train-test split

Standardization (if used)

Model Training

Example: Logistic Regression

Model Evaluation

Accuracy score

Prediction System

User can input sonar data to get prediction (Rock or Mine).
