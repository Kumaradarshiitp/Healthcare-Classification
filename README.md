# Healthcare-Classification
The “healthcare_classification.py” script applies machine learning to a healthcare dataset for automated classification of patient test results. It starts by importing essential libraries such as Pandas, Seaborn, Matplotlib, and Scikit-learn, and reads in the data after renaming columns to standardized labels for consistency
[Healthcare Classification Project]
Overview

This project demonstrates a machine learning workflow for classifying healthcare data using Python and the K-Nearest Neighbors (KNN) algorithm. It covers data loading, cleaning,exploratory data analysis, feature engineering, model training, and evaluation for medical test categorization.


Features
	•	Loads and preprocesses a healthcare dataset (renaming, encoding categorical features, dropping irrelevant columns).
	•	Performs visual and statistical analysis, including histograms, boxplots, scatterplots, and feature correlation heatmaps.
	•	Splits data into training and testing sets, applies feature scaling, and trains a KNN classifier to predict “Normal,” “Abnormal,” or “Inconclusive” test outcomes.
	•	Outputs accuracy and a classification report for healthcare prediction performance.


Requirements
	•	Python 3.x
	•	pandas
	•	seaborn
	•	matplotlib
	•	scikit-learn

  
Install dependencies with: pip install pandas seaborn matplotlib scikit-learn

Usage
	1.	Place `healthcare_classification.py` and the healthcare dataset (CSV format) in the same directory.
	2.	Run the script:python healthcare_classification.py

  	Review plots and classification metrics displayed in the output.

Dataset Structure
Key columns required:
	•	Name, Age, Gender, Doctor, Hospital, Room Number, Blood Type, Medical Condition, Date of Admission, Insurance Provider, Billing Amount, Admission Type, Discharge Date, Medication, Test Results.

Output
	•	Visualizations for data distribution and relationships.
	•	Model accuracy and classification report for medical test results.
