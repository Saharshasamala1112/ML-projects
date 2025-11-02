🦟 **Dengue Outbreak Prediction using Naive Bayes**

📄 **Project Overview**

This project applies Naive Bayes Classification to predict dengue outbreaks in Bangladesh based on climatic factors such as temperature, humidity, and rainfall.
By analyzing patterns between environmental conditions and outbreak trends, the model supports early warning systems and epidemic preparedness.

🎯** Objective**

To build a probabilistic model that classifies whether a dengue outbreak is likely to occur given specific climate conditions.

🧰 **Technologies Used**

Python 3

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn (GaussianNB)

⚙️ **Workflow**

**Data Import & Cleaning**

Loaded DengueAndClimateBangladesh.csv

Checked for missing values and inconsistencies

Explored seasonal and yearly dengue trends

**Feature Engineering**

Climate variables used: MIN, MAX, HUMIDITY, RAINFALL

Converted dengue counts into binary labels:

df['DENGUE_CLASS'] = df['DENGUE'].apply(lambda x: 1 if x > 0 else 0)

**Model Training**

Implemented Gaussian Naive Bayes

Split dataset (70% train, 30% test)

Trained and evaluated classification performance

**Model Evaluation**

Generated confusion matrix and classification report

Compared predicted vs actual outbreak values

📊**Model Performance Summary**
Metric	                 Value
Accuracy                 	85%
Precision (Weighted Avg)	0.90
Recall (Weighted Avg)   	0.85
F1-Score (Weighted Avg) 	0.86

**Class-wise Details:**

Class	              Precision 	Recall	F1-score	Support
0 (No Outbreak)      	0.68     	1.00    	0.81	    13
1 (Outbreak)	        1.00	    0.79    	0.88	    28

🔍 **Key Insights**

Rainfall and Humidity strongly correlate with dengue outbreak frequency.

Naive Bayes achieved high sensitivity (recall) for detecting outbreak absence, ensuring minimal false alarms.

The model’s simplicity allows for fast retraining and easy interpretability, making it ideal for public health deployment.
