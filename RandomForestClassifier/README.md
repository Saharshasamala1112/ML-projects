**Diabetes Prediction using Random Forest Classifier**

**Overview**

This project applies a Random Forest Classifier to predict whether a person is likely to have diabetes based on health indicators such as glucose level, BMI, blood pressure, and age. It uses the PIMA Indians Diabetes Dataset from Kaggle to demonstrate how ensemble learning techniques can improve healthcare predictions.

The notebook includes data preprocessing, visualization, model training, and evaluation, providing an in-depth exploration of Random Forest and its performance in a real-world dataset.

**Problem Statement**

Diabetes is one of the most common and serious chronic diseases worldwide. Early detection is vital for effective management and prevention of complications.

The goal of this project is to build a Random Forest–based predictive model that classifies whether an individual has diabetes based on key medical features. The model aims to enhance diagnostic accuracy and provide data-driven insights for healthcare decision-making.

**Dataset Information**

Dataset Name: PIMA Indians Diabetes Dataset
Source: Kaggle – Pima Indians Diabetes Database

File Used: diabetes.csv

**Attributes include:**

->Pregnancies: Number of times pregnant

->Glucose: Plasma glucose concentration

->Blood Pressure: Diastolic blood pressure (mm Hg)

->Skin Thickness: Triceps skinfold thickness (mm)

->Insulin: 2-Hour serum insulin (mu U/ml)

->BMI: Body Mass Index (weight in kg/(height in m)^2)

->Diabetes Pedigree Function: Family history-based diabetes likelihood

->Age: Age of the patient

->Outcome: 0 = No Diabetes, 1 = Diabetes

**Machine Learning Model Used**

->Algorithm: Random Forest Classifier

**Key Steps:**

->Data Cleaning: Handling missing and zero values

->Exploratory Data Analysis (EDA): Correlation heatmaps, histograms, and boxplots

->Feature Scaling: Standardizing numerical columns

->Model Training: Using Scikit-Learn’s RandomForestClassifier

**Model Evaluation:**

->Accuracy Score

->Confusion Matrix

->ROC Curve and AUC Score

->Feature Importance Plot

**Visualizations**

The notebook provides several insightful visuals, including:

->Correlation Heatmap

->Feature Distribution Charts

->Confusion Matrix

->ROC Curve

->Feature Importance Bar Chart

**Conclusion**

The Random Forest Classifier effectively predicted diabetes outcomes with high accuracy and robustness.
Important predictors such as Glucose, BMI, and Age were identified as significant contributors to diabetes risk.

The ensemble learning approach helped reduce overfitting and improved predictive performance compared to simpler models.
Future work could involve tuning hyperparameters, testing Gradient Boosting or XGBoost, and exploring real-time clinical data integration.

**Technologies Used**

->Python 3

->NumPy

->Pandas

->Matplotlib & Seaborn

->Scikit-Learn (RandomForestClassifier)
