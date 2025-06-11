# Use of Machine Learning and SNOMED CT Encoded Health Problems to Predict Hospital Discharge Diagnoses

**Author: Cindy Chen**  

**Director/s: Santiago Frid, Juan Barrios**   

**Barcelona, 11th June 2025**  

---

## Contents  
This repository includes  the scripts developed during the project:

- Data cleaning and Exploratory Data Analysis: ```TFG_01_Data_Understanding_EDA.ipynb```
- Data pre-processing. ```TFG_02_Data_Preprocessing.ipynb```
- Feature selection. ```TFG_03_Feature_Selection.ipynb```
- The ```TFG_04_Models``` folder, contains all the scripts for model selection, training, evaluation, tuning, and testing for each subset.

## Abstract
The accurate classification of discharge diagnoses is a critical step in clinical decision-making, as it has direct effect on patient care, hospital management, and administrative tasks. Traditionally, diagnostic coding has been a manual and time-consuming process, typically done after a patient is discharged, which could lead to delays for subsequent processes such as billing, reporting, and care optimization. Recently, the Hospital Clínic de Barcelona has integrated a structured list of health problems coded in SNOMED CT into the Electronic Health Record (EHR) from the beginning of the patient’s hospitalization. This development has enabled the reuse of structured clinical data throughout the care process and has opened the door for predictive tools using Machine Learning (ML).   

The goal of this research is to determine whether there’s a significant relationship between reported health problems and the final ICD-10 discharge diagnoses. To explore this, data obtained from the Hospital Clínic de Barcelona was analysed, incorporating information from various clinical sources, such as demographics, laboratory results, prescriptions, and admissions records. Feature engineering was also carried out and methods based on decision trees, along with ANOVA tests, were used to identify the most relevant input variables. Subsequently, several supervised ML models, including Decision Trees (DTs), Random Forest (RF), and XGBoost were trained and evaluated.  

The best performing model, a Decision Tree classifier, achieved an accuracy of 69.8%, with a recall and F1-score of 0.68, and an AUC of 0.83. While no single variable served as a dominant predictor, the results show that health problems coded in SNOMED CT, combined with other clinical and demographic data, can significantly improve the model’s ability to classify discharge diagnoses. 

**Keywords**: Machine Learning, SNOMED CT, ICD-10-CM, Supervised Learning, Multiclass Classification.
