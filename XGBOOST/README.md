**🍷 Wine Classification using Machine Learning**

**📄 Project Overview**
This project classifies wine samples into customer segments based on their chemical composition.
Using the Wine dataset (commonly known from UCI/Kaggle), the model applies supervised machine learning algorithms to predict the wine class.

🎯 **Objective**

To accurately predict the Customer_Segment (1, 2, or 3) of each wine sample based on 13 physicochemical attributes such as alcohol, magnesium, flavanoids, and color intensity.

🧰 **Technologies Used**

Python 3

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

⚙️ **Workflow**

**Data Loading and Exploration**

Imported the Wine.csv dataset.

Inspected column types and missing values.

Identified Customer_Segment as the target variable.

**Data Preprocessing**

Normalized/standardized feature values for uniform scaling.

Split data into training and testing sets.

Ensured balanced class distribution.

**Model Building**

Applied Logistic Regression, KNN, or SVM (depending on notebook content).

Trained the model using scikit-learn.

Evaluated performance metrics such as:

Accuracy

Precision

Recall

Confusion Matrix

**Results and Evaluation**

Achieved high prediction accuracy on test data.

Identified the most influential chemical properties for classification.

**Visualization**

Correlation heatmaps for feature relationships.

Pair plots for visualizing class separation.

**📊 Key Insights**

Alcohol, Flavanoids, and Proline are the most significant predictors.

Machine learning models can clearly distinguish wine segments.

Feature scaling significantly improved model performance.
