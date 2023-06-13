This is the README for group 7 of STATS 170. This project is trying to predict and analyze Credit Card Default Rates using Survival Analysis and other methods.

Created by Ethan So, Michael Chong, Rex Kim, Yoon Kim, and William Chiang

This repository contains the following files:

Main scripts:  
preprocessing.Rmd:  Preprocesses the dataset to get it ready for modeling. Outputs a new csv file of the merged data.  
eda.ipynb:  Exploratory data analysis  
classification_models.ipynb:  Builds the logistic classifier  
survival_models.Rmd:  Builds the Kaplan-Meier and Cox Proportional Hazards models  
project.Rmd:  Demonstration of the project  

Data files:  
application_record.csv:  original dataset taken from Kaggle  
credit_record.csv:  original dataset taken from Kaggle  
data.csv:  the merged data file (can be created by preprocessing.Rmd)  
data_as_numerical.csv:  data.csv but datatypes converted to numerical for model building  

The following files should be run in order to produce output that was used for the project:
1. preprocessing.Rmd (optional if using the data.csv and data_as_numerical.csv provided)  
2. eda.ipynb
3. classification_models.ipynb
4. survival_models.Rmd
