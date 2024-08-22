# Stroke_prediction
This is machine learning project 

1. project
Stroke is one of the most dangerous diseases that can occur at any time to anyone. It often leads patients to severe disability or even death. According to the National Institute of Neurological Disorders and Stroke, approximately 800,000 people suffered from a stroke in the United States [1]. Moreover, the percentage of stroke occurrence of people under age 65 increased by approximately 15% from 2011 to 2022 [2]. Identifying the features that cause stroke and predicting it could be crucial to prevent stroke and reduce its impact.This project will focus on exploring which features affect stroke and make prediction based on the data by performing machine learning techniques (Logistic Regression, KNN, and Random Forest).

2. data
   The data from kaggle includes 5110 observations with 12 features. Out of the 12 features, One feature is an identifier, One feature is a dependent variable, and ten are independent variables. Eight features are categorical variables and three features are continuous variables.

Here is a brief description of the features.

Variable	Description	type	Value
id	Identification	-	-
stroke	whether a stroke has occurred or not
Categorical Variable, Binary	1 = yes, 0 = no
gender	patients' gender	Categorical Variable, Binary	Male, Female
hypertension	whether a patient has hypertension	Categorical Variable, Binary	1 = yes, 0 = no
heart_disease	whether a patient has heart disease	Categorical Variable, Binary	1 = yes, 0 = no
ever_married	whether a patient has married	Categorical Variable, Binary	yes, no
Residence_type	patients' residence type	Categorical Variable, Binary	Urban, Rural
work_type	patients' work type	Categorical Variable, non-Binary	Govt_job, Private, Self-employed, Children, Never-worked
smoking_status	whether a patient has smoked.	Categorical Variable, non-Binary	smokes, Unknown, formerly smoked, never smoked
age	patients' age	Continuous Variable	from 0 to 82
avg_glucose_level	patients' average glucose level	Continuous Variable	from 0 to 272
bmi	patients' bmi	Continuous Variable	from 0 to 98

GEtting start
pyplot
numpy
pandas
seaborn
