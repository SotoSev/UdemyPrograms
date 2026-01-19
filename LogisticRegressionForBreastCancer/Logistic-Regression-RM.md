## 🩺 Breast Cancer Prediction using Logistic Regression

  This project applies Logistic Regression to predict whether a breast tumor is 
  malignant or benign using medical diagnostic features. It demonstrates a full 
  machine learning pipeline, from data preprocessing to model evaluation and validation.

### 📌 Project Overview

  The objective is to build a reliable binary classification model for breast cancer diagnosis. 
  Logistic Regression is used due to its interpretability and strong performance on linearly separable medical datasets.


### 📊 Dataset

  - Source file: breast_cancer.csv
  
  - Features: Clinical and diagnostic tumor measurements
  
  - Target variable: Cancer diagnosis (binary classification)

### Data Preparation

  - Feature matrix X: All columns except ID and label
  
  - Target vector y: Diagnosis label
  
  - Dataset split:
  
    - 80% Training
  
    - 20% Testing

### 🧠 Model

 - Algorithm: Logistic Regression

 - Library: scikit-learn

 - Reproducibility: Fixed random state

 The model predicts class labels based on learned probability thresholds.

### ⚙️ Training

  - The classifier is trained on the training dataset

  - Model parameters are optimized internally by scikit-learn

### 📈 Output Metrics

  - Confusion Matrix (printed in console)

  - Cross-validation accuracy (%)

  - Accuracy standard deviation (%)
