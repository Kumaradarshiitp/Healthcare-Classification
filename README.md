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





    • Emergency-tipo: This image shows the categories and counts for “tipo_admissao” (type of hospital admission such as Elective, Emergency, Urgent) and “medicacao” (medication types like Aspirin, Lipitor, etc.). These topics belong to Hospital Admission and Medication respectively.
	•Idade-age-and-genero-gender: Displays the age distribution (“idade”) and gender (“genero”) of patients, belonging to Demographics topics.
	• Provedora_seguro-valor_cobranca: Shows counts for “provedora_seguro” (insurance providers) and billing amount distribution (“valor_cobranca”), belonging to Insurance and Healthcare Cost topics.
	•  Tipo_sangue-condicao_medica: Illustrates “tipo_sangue” (blood type) and “condicao_medica” (medical conditions like Diabetes, Asthma, etc.), which belong to Biological Profile and Chronic Conditions topics.
	•	Normal-resultado: Visualizes “resultado_exame” (exam results - Inconclusive, Normal, Abnormal), corresponding to Diagnostic Results 
	
Definition of Each Topic

	  •	Hospital Admission: Information about how and why patients are admitted to a hospital (Elective, Emergency, Urgent).
	  •	Medication: Types of medicines commonly given to patients and their distribution.
	  •	Demographics: Statistical data that describes patient characteristics such as age and gender.
	  •	Insurance: Details about medical insurance providers for patients.
	  •	Healthcare Cost: Data concerning the costs or charges for hospital services and treatments.
	  •	Biological Profile: Inherent patient attributes such as blood type.
	  •	Chronic Conditions: Long-term health problems that individuals might have.
	  •	Diagnostic Results: Outcomes of clinical tests performed for patients.


Emergency-tipo :
https://github.com/Kumaradarshiitp/Healthcare-Classification/blob/main/Emergency%20tipo.png

Idade-age-and-genero-gender:
https://github.com/Kumaradarshiitp/Healthcare-Classification/blob/main/%20idade%20(age)%20and%20genero%20(gender).png

Provedora_seguro-valor_cobranca:
https://github.com/Kumaradarshiitp/Healthcare-Classification/blob/main/provedora_seguro%20%26%20valor_cobranca.png

Tipo_sangue-condicao_medica:
https://github.com/Kumaradarshiitp/Healthcare-Classification/blob/main/tipo_sangue%20%26%20condicao_medica.png

Normal-resultado: Visualizes:
https://github.com/Kumaradarshiitp/Healthcare-Classification/blob/main/Normal%20resultado.png


Histograma de Idade por Gênero

    • 	Demographics: The chart compares genders (male and female), which is a key feature in demographic analysis.
	•	Age Distribution: The x-axis represents different age groups, making age structure the principal variable visualized.
	•	Gender Analysis: The image makes a direct comparison across genders, highlighting differences or similarities in age frequency between male and female populations

Histograma de Idade por Gênero: 
https://github.com/Kumaradarshiitp/Healthcare-Classification/blob/main/Histograma%20.png

Boxplot

    •	Value Distribution: The plot shows how billing amounts are spread for each insurer.
	•	Median: The line in each box represents the median value for billing.
	•	Interquartile Range (IQR): The colored box captures the middle 50% of data (from Q1 to Q3).
	•	Whiskers/Range: The vertical lines (whiskers) show the spread beyond the IQR, typically up to 1.5 times the IQR from the quartiles.
	•	Insurance Provider Comparison: Each box represents a different company, enabling direct visual comparison of billing variability and central tendency between providers.
	
This chart is useful for identifying differences in billing practices, median costs, and overall variability across insurance providers.

Boxplot:
https://github.com/Kumaradarshiitp/Healthcare-Classification/blob/main/Boxplot%20.png

Idade(Age) & Valor de Cobranca (Charge Value or Billing Amount) 

    •	“Idade” (Age) on the horizontal axis, representing the age of individuals.
	•	“Valor de Cobrança” (Billing or Charge Value) on the vertical axis, representing the associated financial charge.
This visual examines the relationship or distribution pattern between a person’s age and the amount billed, which is a common analysis in fields like healthcare billing, insurance, or finance

Idade(Age) & Valor de Cobranca (Charge Value or Billing Amount) :
https://github.com/Kumaradarshiitp/Healthcare-Classification/blob/main/Idade.png

Correlation Matrix

	•	idade: Patient age
	•	genero: Gender
	•	tipo_sangue: Blood type
	•	condicao_medica: Medical condition
	•	provedora_seguro: Insurance provider
	•	valor_cobranca: Billing amount
	•	tipo_admissao: Type of admission
	•	medicacao: Medication
	•	resultado_exame: Exam result

Correlation Matrix:
https://github.com/Kumaradarshiitp/Healthcare-Classification/blob/main/Grafico%20para%20analisar.png

