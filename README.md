# 🩺 Diabetes Prediction using Support Vector Machine (SVM)

## 📌 Project Overview

This project builds a Machine Learning classification model to predict whether a person is diabetic or non-diabetic based on medical diagnostic features.

The model is implemented using **Support Vector Machine (SVM)** with a linear kernel. The project demonstrates a complete ML workflow including data preprocessing, feature scaling, model training, evaluation, and a predictive system.

---

## 📊 Dataset Information

The dataset contains **768 patient records** with 8 input features and 1 target variable.

### 🔎 Features:
- Pregnancies  
- Glucose  
- BloodPressure  
- SkinThickness  
- Insulin  
- BMI (Body Mass Index)  
- DiabetesPedigreeFunction  
- Age  

### 🎯 Target Variable:
- Outcome  
  - 0 → Non-Diabetic  
  - 1 → Diabetic  

### 📈 Class Distribution:
- Non-Diabetic: 500  
- Diabetic: 268  

---

## ⚙️ Technologies & Libraries Used

- Python  
- NumPy  
- Pandas  
- Scikit-learn  
- Jupyter Notebook  

---

## 🔄 Project Workflow

### 1️⃣ Data Collection & Analysis
- Loaded dataset using Pandas
- Checked dataset shape
- Generated statistical summary using `.describe()`
- Analyzed class distribution

### 2️⃣ Data Preprocessing
- Separated features (X) and labels (Y)
- Applied `StandardScaler` for feature scaling
- Converted data into standardized format

### 3️⃣ Train-Test Split
- 80% Training Data
- 20% Testing Data
- Stratified split to maintain class balance

### 4️⃣ Model Training
- Used `SVC` (Support Vector Classifier)
- Kernel: Linear
- Trained model on standardized training data

### 5️⃣ Model Evaluation

| Dataset | Accuracy |
|----------|----------|
| Training Data | 78.66% |
| Testing Data  | 77.27% |

The model shows good generalization with minimal overfitting.

---

## 🤖 Predictive System

The project includes a prediction system where:
- User inputs medical details
- Input is standardized using trained scaler
- Model predicts diabetes status

### Example:

Input:
```
(5,166,72,19,175,25.8,0.587,51)
```

Output:
```
The person is diabetic
```

---

## 📌 Key Learnings

- Importance of Feature Scaling in SVM
- Handling Binary Classification Problems
- Model Evaluation using Accuracy Score
- Building an End-to-End Machine Learning Pipeline
- Creating a Real-World Prediction System

---

## 🚀 Future Improvements

- Implement Cross-Validation
- Hyperparameter tuning using GridSearchCV
- Try RBF & Polynomial Kernels
- Add Confusion Matrix & ROC Curve
- Deploy using Streamlit / Flask
- Improve handling of zero values in medical features

---

## 💼 Portfolio Value

This project demonstrates:
- Strong understanding of supervised learning
- Practical ML implementation
- Clean and structured workflow
- Ability to build usable prediction systems

---

⭐ If you found this project helpful, feel free to give it a star!
