# Prediction-of-Risk-of-Heart-Disease---Machine-Learning
## ABSTRACT:
Coronary Heart Disease is becoming one of the most prevalent chronic diseases in the United States impacting millions of Americans every year and exerting a significant financial burden on the economy. It is estimated that heart disease alone claims 647,000 lives each year making it a leading cause of death. This project aims to use the machine learning techniques towards the prediction of risk of heart disease using the 2015 Behavioral Risk Factor Surveillance System (BRFSS) survey. We trained multiple supervised classifiers namely Logistic Regression, Decision Tree, K-Nearest Neighbours, Support Vector Machine and we compared the accuracies and identified what models perform better for heart disease prediction. The Heart Health indicators dataset as part of the 2015 Behavioral Risk Factor Surveillance System (BRFSS) survey was highly imbalanced and this was addressed using methods such as Synthetic Minority Over Sampling Technique (Smote) Sampling for better classification and prediction results.

## BACKGROUND AND MOTIVATION:
The burden of heart disease is affecting millions of people annually across the world and millions are getting affected in United States. Heart disease risk is influenced by numerous factors. Three major risk factors for heart disease have been recognized by the Centers for Disease Control and Prevention: smoking, high blood pressure, and high blood cholesterol. These three risk factors are present in about half of the American population. This fact highlights the importance of preventative measures and tests that can accurately predict heart disease in the population prior to negative outcomes like myocardial infarctions (heart attacks) taking place.
The motivation of this project is to employ various machine learning models to predict the heart disease. This is a supervised learning task where we are trying the predict the risk of disease based on the historical data collected through the Behavioral Risk Factor Surveillance System. This task is important in order to take preventative measures through early intervention and this will help in reducing the burden of the disease on both the individual and the society as a whole.

## DATA DESCRIPTION:
We chose this dataset from Kaggle and this dataset consists of data indicators that lead to heart attacks among individuals.

Source Link: https://www.kaggle.com/datasets/alexteboul/heart-disease-health-indicators-dataset/data

The dataset contains the following:
Number of observations: 253680 survey responses
Total Number of Attributes: 22 (21 are continuous variables, 1 target variable is binary)
Target Variable (y): HeartDiseaseorAttack (binary)
Total number of null values: 0
 
This dataset has strong class imbalance with 229,787 respondents do not have/have not had heart disease while 23,893 have had heart disease.
