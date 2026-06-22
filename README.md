# ml-breast-cancer-project
Predictive Modeling Using Machine Learning

Breast Cancer Classification Project

Project Overview

This project builds a supervised machine learning model to predict whether a breast tumor is Malignant (0) or Benign (1) based on 30 tumor measurement features.
The dataset used is the Breast Cancer Wisconsin Dataset, built into the scikit-learn library. No external download required.


Project Structure

ml-breast-cancer-project/
|
|-- ml_project.ipynb        - Main Jupyter Notebook
|-- confusion_matrices.png  - Confusion Matrix Visualization
|-- roc_curve.png           - ROC Curve Visualization
|-- README.md               - Project Documentation


Dataset Details

DetailInfoSourcesklearn.datasets.load_breast_cancerTotal Samples569 patientsFeatures30 tumor measurementsTarget Classes0 = Malignant, 1 = BenignTask TypeBinary ClassificationTrain/Test Split80% / 20%


Models Used

ModelAccuracyLogistic Regression97.37% (Best)Random Forest96.49%Decision Tree94.74%


Detailed Results

Logistic Regression - 97.37% Accuracy

ClassPrecisionRecallF1-ScoreSupport0 (Malignant)0.980.950.96431 (Benign)0.970.990.9871Weighted Avg0.970.970.97114


Random Forest - 96.49% Accuracy

ClassPrecisionRecallF1-ScoreSupport0 (Malignant)0.980.930.95431 (Benign)0.960.990.9771Weighted Avg0.970.960.96114


Decision Tree - 94.74% Accuracy

ClassPrecisionRecallF1-ScoreSupport0 (Malignant)0.930.930.93431 (Benign)0.960.960.9671Weighted Avg0.950.950.95114


Visualizations

Confusion Matrices
Show Image
ROC Curve
Show Image


Key Findings
Best Model: Logistic Regression with 97.37% accuracy
Logistic Regression achieved the highest F1-score of 0.97 across both classes
Random Forest came close at 96.49%, showing strong ensemble performance
Decision Tree had the lowest accuracy at 94.74% but still performed well
All three models showed high precision for Malignant detection, which is critical in medical diagnosis



Libraries Used

pandas          - Data manipulation
numpy           - Numerical operations
scikit-learn    - ML models and evaluation
matplotlib      - Plotting
seaborn         - Enhanced visualizations


What I Learned

How to load and explore built-in sklearn datasets
Data preprocessing and scaling features using StandardScaler
Training and comparing multiple ML algorithms
Evaluating models using accuracy, precision, recall, and F1-score
Visualizing results with confusion matrices and ROC curves



Training and comparing multiple ML algorithms
Evaluating models using accuracy, precision, recall, and F1-score
Visualizing results with confusion matrices and ROC curves
