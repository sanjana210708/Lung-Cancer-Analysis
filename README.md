# Lung Cancer Prediction and Data Analysis

## Project Overview

This project focuses on analyzing a lung cancer survey dataset to identify key lifestyle and health factors associated with lung cancer. Exploratory Data Analysis (EDA), feature engineering, and machine learning techniques were used to understand patterns in the data and build a predictive model.

## Objective

The main objective of this project is to analyze the relationship between lifestyle habits and lung cancer risk and to develop a machine learning model capable of predicting the likelihood of lung cancer based on various health indicators.

## Tools and Technologies Used

* Python
* Pandas and NumPy for data manipulation
* Matplotlib and Seaborn for data visualization
* Scikit-learn for machine learning models
* Jupyter Notebook for analysis and experimentation

## Project Workflow

1. Data loading and preprocessing
2. Data cleaning and formatting
3. Exploratory Data Analysis (EDA)
4. Feature engineering (creation of Risk Score and Age Group)
5. Model building using Random Forest Classifier
6. Model evaluation using accuracy and confusion matrix

## Key Insights

* Smoking, alcohol consumption, and peer pressure significantly contribute to lung cancer risk.
* Symptoms such as chest pain, wheezing, and coughing show strong correlation with lung cancer cases.
* Feature engineering helped create a combined risk indicator improving model interpretability.
* The Random Forest model achieved high prediction accuracy on the test dataset.

## Machine Learning Model

A Random Forest Classifier was trained to predict lung cancer based on lifestyle habits and medical symptoms. The model was evaluated using a train-test split and achieved strong predictive performance.

## Files in This Repository

* `Lung cancer analysis.ipynb` – Complete data analysis and machine learning workflow
* `survey lung cancer.csv` – Dataset used for the analysis
* `README.md` – Project documentation

## Future Improvements

* Implement additional models such as Logistic Regression and Gradient Boosting
* Perform hyperparameter tuning to improve prediction accuracy
* Deploy the model using a web interface for real-time predictions

## Conclusion

This project demonstrates how data analysis and machine learning can be applied to healthcare datasets to identify risk factors and predict disease outcomes, helping support data-driven decision making.
