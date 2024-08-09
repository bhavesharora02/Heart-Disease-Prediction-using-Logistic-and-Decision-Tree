# Heart-Disease-Prediction-using-Logistic-and-Decision-Tree
This project aims to predict the likelihood of heart disease in patients based on various medical attributes using machine learning techniques. 

**Project Overview**

The dataset includes features such as age, sex, chest pain type, blood pressure, cholesterol levels, and more. The goal is to build a predictive model that can accurately classify whether a patient has heart disease or not.

**Dataset**

The dataset consists of the following columns:

**age**: Age of the patient

**sex**: Gender of the patient

**cp**: Chest pain type

**trestbps**: Resting blood pressure

**chol**: Serum cholesterol level

**fbs**: Fasting blood sugar

**restecg**: Resting electrocardiographic results

**thalach**: Maximum heart rate achieved

**exang**: Exercise-induced angina

**oldpeak**: ST depression induced by exercise relative to rest

**slope**: The slope of the peak exercise ST segment

**ca**: Number of major vessels colored by fluoroscopy

**thal**: Thalassemia

**target**: Diagnosis of heart disease (1 = disease, 0 = no disease)

**Steps Involved**

**1. Data Preprocessing**

Checked for Null Values: Verified the dataset for any missing values and handled them appropriately.
Data Exploration: Used describe() and info() functions to understand the data distribution and characteristics.

**2. Feature and Target Splitting**

Split the dataset into features (independent variables) and target (dependent variable) for model training and testing.

**3. Model Training**

**Logistic Regression:**

Trained the logistic regression model on the training data.
Achieved an accuracy of 85% on the training set.

**Decision Tree:**

Trained the decision tree model on the training data.
Achieved an accuracy of 100% on the training set, indicating overfitting.

**4. Model Evaluation**

Tested both models on the test dataset:
Logistic Regression: Achieved an accuracy of 81% on the test data, indicating good generalization.
Decision Tree: Achieved an accuracy of 77% on the test data, confirming that it overfitted on the training data and is not the ideal model for this task.

**5. Model Selection**

Concluded that Logistic Regression is the better model for predicting heart disease due to its balanced performance and lack of overfitting.

**6. Predictive System**

Built a predictive system using the trained logistic regression model.
The system takes input data (e.g., age, sex, cholesterol levels) and predicts whether a person is likely to have heart disease or not.

**Conclusion**

The logistic regression model provides a reliable and interpretable method for predicting heart disease with an accuracy of 81% on the test data. The decision tree model, while accurate on the training data, was prone to overfitting and did not generalize well to new data. Therefore, logistic regression is sufficient and recommended for this task. The predictive system developed based on this model can effectively assist in the early detection of heart disease.
