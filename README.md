Water Quality Analysis – Machine Learning Assignment

Overview

This repository contains a data analysis and machine learning project developed as part of the course Machine Learning for Brain and Cognition (MLBC). Although the course focuses on applications to neuroscience and cognition, this assignment applies the same methodological pipeline to a real-world environmental dataset on water quality.

The project demonstrates the full workflow of a machine learning study, from exploratory data analysis to model evaluation and interpretation.

Objectives
	•	Explore and understand a multivariate real-world dataset
	•	Perform data cleaning and preprocessing
	•	Apply supervised machine learning models for prediction
	•	Evaluate model performance using appropriate metrics
	•	Critically interpret the results and discuss limitations

Dataset
	•	Domain: Water quality / environmental monitoring
	•	Samples: Multiple water observations
	•	Features: Physico-chemical measurements (e.g. nutrient concentrations, oxygen levels, temperature)
	•	Target variable: Water quality indicator / classification label
	•	Source: Provided for educational purposes

The dataset is used exclusively for academic and non-commercial use.

Methods

The analysis follows a standard machine learning pipeline:
	•	Exploratory Data Analysis (EDA)
	•	Data preprocessing (handling missing values, scaling, feature selection)
	•	Model training (e.g. baseline models and more advanced classifiers/regressors)
	•	Model evaluation using suitable performance metrics

Results

The results highlight how different machine learning models capture relationships between water quality indicators and environmental variables. Performance differences between models are discussed, together with potential sources of bias and overfitting.

Generated figures and plots are included directly in the notebook.

Repository Structure
	•	Water_Quality_Assignment.ipynb: main notebook containing the full analysis
	•	data/: dataset used in the project


How to Run

Install the required dependencies and open the notebook:

pip install -r requirements.txt
jupyter notebook Water_Quality_Assignment.ipynb

Author

Davide Cantavenera
MSc Student – Machine Learning for Brain and Cognition