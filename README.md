# Australian Weather Prediction using Machine Learning

This project focuses on predicting whether it will rain tomorrow using a real-world large-scale Australian weather dataset. Multiple machine learning classification models were trained and evaluated to achieve high prediction accuracy.


# Table of Contents
- Project Overview
- Objectives
- Dataset Description
- Technologies Used
- Data Preprocessing
- Handling Class Imbalance (SMOTE)
- Models Implemented
- Model Evaluation & Results
- Performance Comparison
- Installation & Usage
- How to Run the Project
- Project Structure
- Results & Discussion
- Conclusion
- Future Work
- Author
- License


# Project Overview
Rainfall prediction plays a crucial role in agriculture, weather forecasting, and disaster management. This project uses supervised machine learning techniques to classify whether it will rain the next day based on past meteorological data from Australia.

The dataset contains over 147,000 records with 23 weather-related features. Several classification models were trained and optimized to achieve high accuracy.


# Objectives
- To clean and preprocess a large real-world weather dataset  
- To handle missing and imbalanced data  
- To implement multiple classification models  
- To compare model performance using evaluation metrics  
- To achieve more than 80% classification accuracy  
- To select the best-performing model  


# Dataset Description
- Dataset Name: Australian Weather Dataset  
- Total Rows: ~147,000  
- Total Columns: 23  
- Target Variable: `RainTomorrow`  
- Type: Binary Classification (Yes / No)  


# Key Features:
- MinTemp, MaxTemp  
- Rainfall  
- Humidity  
- WindSpeed, WindDirection  
- Pressure  
- Sunshine  
- CloudCover


# Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- SMOTE (Imbalanced-learn)  
- Jupyter Notebook  


# Data Preprocessing
- Handled missing values using mean, median, and mode
- Converted categorical variables using Label Encoding
- Feature scaling using StandardScaler
- Dropped irrelevant and highly correlated columns
- Converted date features into useful numerical format


# Handling Class Imbalance (SMOTE)
The target variable was highly imbalanced, where rainy days were significantly fewer than non-rainy days.

To solve this issue, the **Synthetic Minority Oversampling Technique (SMOTE)** was applied:
- Balanced both classes
- Improved model fairness
- Increased recall and F1-score


# Models Implemented
The following machine learning models were trained:

- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Decision Tree Classifier  
- Random Forest Classifier  
- Naive Bayes  
- Support Vector Machine (SVM)  


# Model Evaluation & Results
Each model was evaluated using multiple performance metrics:

- Accuracy  
- Precision  
- Recall  
- F1-Score   

# Best Performing Model:
**Random Forest Classifier** achieved the highest accuracy (above 80%) with balanced precision and recall after applying SMOTE.


# Performance Comparison
All models were compared using an accuracy bar chart to visualize their performance and select the best model.
