**Rain Prediction in Australia — Logistic Regression Project**

📄** Project Overview**

This project predicts whether it will rain tomorrow in Australia using the Rain in Australia dataset from Kaggle.
It applies Logistic Regression, a supervised learning algorithm used for binary classification problems.

**🧩 Problem Statement**

The goal is to build a machine learning model that can predict the probability of rainfall the next day (RainTomorrow) based on various meteorological parameters such as:

Temperature

Humidity

Wind Speed

Pressure

Cloud Cover

Sunshine Duration

**🧰 Technologies Used**

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

**⚙️ Steps Performed**

**Importing Libraries**

Essential libraries for data manipulation, visualization, and model building.

**Loading the Dataset**

Dataset: weatherAUS.csv (Kaggle)

**Data Preprocessing**

Replaced True/False with 1/0

Converted the Date column into Year, Month, Day

Handled missing values

Encoded categorical variables using pd.get_dummies()

**Exploratory Data Analysis (EDA)**

Visualized distributions, correlations, and missing data patterns.

Explored numerical and categorical features.

**Model Building**

Implemented Logistic Regression using sklearn.

Split data into training and testing sets.

Evaluated performance with accuracy, precision, recall, and confusion matrix.

**Results**

Model achieved good accuracy in predicting rain occurrence.

Demonstrated that weather variables can effectively indicate rainfall likelihood.

**📊 Conclusion**

Logistic Regression provided a strong baseline for binary weather prediction. The analysis highlights the importance of humidity, temperature, and pressure as key factors influencing rainfall.
