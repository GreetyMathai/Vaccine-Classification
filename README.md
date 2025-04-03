# Vaccine-Classification
Based on various factors, we are trying to classify if the person has received H1N1 Vaccine

This project helps identify key factors influencing H1N1 vaccination, enabling governments, healthcare providers, and researchers to improve vaccination strategies and awareness campaigns. It supports public health by predicting vaccine hesitancy, optimizing resource allocation, and enhancing targeted outreach. Beneficiaries include policymakers, hospitals, epidemiologists, NGOs, and insurance companies seeking data-driven insights for better healthcare decisions.

The steps covered in this project are:

Step 1: Data Cleaning
      
      This step we have dealt with:
        1. Missing values : Dropped some and replace some 
        2. Outliers : replaced with the mean

Step 2. Data PreProcessing
      
      In this step we have dealt with
	1. Chategorical data : Using a sparse matrix(get_dummies) and Labeling
	2. Data imbalance : Using Smote 
						
Step 3: Data Splitting
     
     In this step we have dealt with split data into test and train

Step 4: Model Fitting
     
     In this step we have applied 4 algorithms:
	1. Logistic regression
	2. Decision Tree Classifier
	3. Randon Forest Classifier
	4. XG Boost Classifier

Step 5: Model Selection
     
     In this step we have compared the accuracy, precision, recall and confusion matrix of the models and selected the best model

					

					

