🩺 Diabetes Prediction using Support Vector Machine (SVM)
📌 Project Overview

This project focuses on building a Machine Learning model to predict diabetes using patient medical attributes. The model is developed using the Support Vector Machine (SVM) algorithm with a linear kernel to classify whether a person is diabetic or non-diabetic.

The objective of this project is to demonstrate practical implementation of:

Data preprocessing

Feature scaling

Model training

Model evaluation

Real-time prediction system

📊 Dataset Information

The dataset consists of 768 patient records with 8 medical input features and 1 target variable:

🔎 Features:

Pregnancies

Glucose

BloodPressure

SkinThickness

Insulin

BMI (Body Mass Index)

DiabetesPedigreeFunction

Age

🎯 Target Variable:

Outcome

0 → Non-Diabetic

1 → Diabetic

📈 Class Distribution:

Non-Diabetic: 500

Diabetic: 268

⚙️ Technologies & Libraries Used

Python

NumPy

Pandas

Scikit-learn

Jupyter Notebook

🔄 Project Workflow
1️⃣ Data Collection & Analysis

Loaded dataset into Pandas DataFrame

Performed statistical analysis using .describe()

Checked class distribution

Analyzed feature means grouped by outcome

2️⃣ Data Preprocessing

Separated features (X) and target (Y)

Applied StandardScaler to normalize feature values

Ensured all features are scaled before training SVM

3️⃣ Train-Test Split

80% Training Data

20% Testing Data

Stratified sampling to maintain class balance

4️⃣ Model Training

Used SVC (Support Vector Classifier) with linear kernel

Trained model on standardized training dataset

5️⃣ Model Evaluation
Dataset	Accuracy
Training Accuracy	~78.66%
Testing Accuracy	~77.27%

The model shows good generalization with minimal overfitting.

🤖 Predictive System

The project includes a predictive system where:

User inputs patient data

Input is standardized using trained scaler

Model predicts whether the person is diabetic or not

Example Prediction:

Input: (5,166,72,19,175,25.8,0.587,51)
Output: The person is diabetic
