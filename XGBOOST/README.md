**🍷 Wine Classification using XGBoost**

📄 **Project Overview**

This project applies Extreme Gradient Boosting (XGBoost) to classify wines into three customer segments based on their chemical composition.
By analyzing 13 features (like Alcohol, Flavanoids, and Color Intensity), the model predicts the type of wine with high precision.

🎯 **Objective**

To accurately predict the Customer_Segment (1, 2, or 3) for each wine sample using the Wine.csv dataset.

🧰 **Technologies Used**

Python 3

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

XGBoost

⚙️ **Workflow**

**Data Import & Exploration**

Loaded the dataset and explored column distributions.

Verified absence of missing or duplicate values.

Identified Customer_Segment as the target variable.

**Data Preprocessing**

Converted labels to numerical format.

Split the dataset into training (70%) and testing (30%).

Scaled numerical features for optimal gradient boosting performance.

**Model Building**

Implemented XGBClassifier with the objective multi:softmax.

Tuned key hyperparameters like learning_rate, max_depth, and n_estimators.

Trained and validated the model on the dataset.

**Evaluation**

Used classification metrics and visualized feature importances.

Generated a confusion matrix and performance summary.

📊 **Model Performance Summary**
Metric	                     Score
Accuracy                    	98%
Precision (Weighted Avg)	   0.98
Recall (Weighted Avg)	       0.98
F1-Score (Weighted Avg)	     0.98

**Confusion Matrix Summary**

Class 0: Precision 0.96, Recall 1.00

Class 1: Precision 1.00, Recall 0.95

Class 2: Precision 1.00, Recall 1.00

🔍 **Key Insights**

Alcohol, Flavanoids, Proline, and Color_Intensity are the strongest predictors of wine category.

XGBoost’s ensemble approach captures subtle feature interactions, outperforming traditional models like KNN or Logistic Regression.
