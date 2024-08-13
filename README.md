# **Predictors for Maternal Health Risk**

This project is a part of the AAI-501-01 course in the Applied Artificial Intelligence Program at the
University of San Diego (USD).

**Project Status: [Completed]**

## **Installation**
To use this project, first clone the repo on your device using the command below:

`git init`
`git clone https://github.com/mkaturiusd24/USDIntroToAIGroup1.git`

You will also need access to Jupyter Notebooks, which you can get with the following command:

`pip install jupyter notebook`

Or, you can use an IDE that's capable of running a Jupyter Notebook, such as Visual Studio Code

Then, open "AAI_501_Group1-Project.ipynb" in your IDE or run the following command in the folder where you cloned the repo:

`jupyter notebook AAI_501_Group1-Project.ipynb`

## Project Intro/Objective
The main purpose of this project is to predict Maternal Health Risk for patients in some of the developing countries. 
Prediction for Maternal Health Risk provides illustration for implementation of various statistical and Machine Learning classifying algorithms to predict the health risk status of patients and fetus. 
Since many factors in a patients' life can deeply impact on how they can fall into risk category, these machine learning and decision trees can provide insightful information about the Patient health condition and fetus health condition and how they can be supervised for better care.

## Contributors
Manikanta Katuri
Seanmark Paz
Chris A
Nabeel Khan

## Methods Used
- Support Vector Machine Algorithm
- Decision Tree Classifier Algorithm
- GridSearch CV Algorithm
- Randomized Search CV Algorithm

## Technologies
- Python
- Jupyter Notebook

## Project Description
Our dataset is called 'Maternal Health Risk' from the UCI machine learning library (https://archive.ics.uci.edu/dataset/863/maternal+health+risk).
There are a total of 1013 instances and 6 total features present in the dataset. The features include:
- Age
- Systolic BP
- Diastolic BP
- Blood Sugar(BS)
- Body Temperature(Body Temp)
- HeartRate
- RiskLevel

We initially analyzed crosstabs between many of the explanatory variables and dependent one to check for apparent relationships. We used data cleaning techniques to remove any 
variables that didn't seem to have a significant impact, and to combine certain variables that had a high likelihood of being related. 

The data is categorized into two equal halves for test and training data. The data is then fit into Machine Learning classifier models. The GridSearchCV decision tree classifier has shows highest accuracy for the predictions.

## Acknowledgements
We would like to acknowledge our instructors Andrew Vaughan and Dave Freisen for their efforts in providing us with the knowledge and guidance to complete this
project.
