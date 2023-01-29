# SCI-Classification

This repository holds the source code and final results for the machine learning pipeline used to classify spinal cord injuried (SCI) patients. The binary class designations for these patients were Tetra and Para, both describing the region and severity of injury. This project encompassed the complete development and implementation of a machine learning pipeline. The purpose of this pipeline was to use autonomic sensory data to predict the level of SCI in participants.

The 'figures' directory holds the various graphs and tables that were produced during the exploratory data analysis and hyperparameter tuning excersies. Through a comprehensive review of the data we were able to determine which features may correlate most strongly with the target variable. This analysis helped to inform the approach used for developing models that would attempt to classify patient's injury.

Ultimately, after a comprehensive review of the data and pipeline processes, the Random Forest Classifier was determined to be the most predictive model. 

Software used throughout project:

Python version is 3.10.5
numpy version 1.22.
matplotlib version 3.5.2
sklearn version 1.1.1
pandas version 1.4.2
xgboost version 1.5.1
shap version 0.40.0
