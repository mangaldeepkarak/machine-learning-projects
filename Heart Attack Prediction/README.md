# Goal:
Implementing classification models that can be used to predict that heart attack will be or not .
# Dataset:
https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction
# Description
Cardiovascular diseases (CVDs) are the number 1 cause of death globally, taking an estimated 17.9 million lives each year, which accounts for 31% of all deaths worldwide. Four out of 5CVD deaths are due to heart attacks and strokes, and one-third of these deaths occur prematurely in people under 70 years of age. Heart failure is a common event caused by CVDs and this dataset contains 11 features that can be used to predict a possible heart disease.

People with cardiovascular disease or who are at high cardiovascular risk (due to the presence of one or more risk factors such as hypertension, diabetes, hyperlipidaemia or already established disease) need early detection and management wherein a machine learning model can be of great help.

# Attribute Information:
Age: age of the patient [years]
Sex: sex of the patient [M: Male, F: Female]
ChestPainType: chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]
RestingBP: resting blood pressure [mm Hg]
Cholesterol: serum cholesterol [mm/dl]
FastingBS: fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise]
RestingECG: resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria]
MaxHR: maximum heart rate achieved [Numeric value between 60 and 202]
ExerciseAngina: exercise-induced angina [Y: Yes, N: No]
Oldpeak: oldpeak = ST [Numeric value measured in depression]
ST_Slope: the slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping]

# What I have done:
Analyzed the data, searched for missing values and find categorical and numerical variable.
Performed Exploratory Data Analysis, wherein, I plotted count plots for categorical data and bar plots and distribution plot for continuous data with respect to values of Heart Disease (0 or 1). Apart from that, a correlation heatmap was also plotted.
Encoded categorical data .
Split the dataset into Train and Test data.
Trained model with the following algorithms:
Logistic Regression
Naive Bayes Classifier
Support Vector Classifier
KNN Classifier
Decision Tree Classifier
Random Forest Classifier
XGBoost Classifier
Evaluated the accuracies of models and stored them in a dataframe.
Also evaluated the performance of the model with highest accuracy using confusion matrix and classification report.

# Model Used
-> Support Vector Machine.
-> Decision Tree Classification.
->Random Forest Classification.
-> k nearest Neighbourhood.
-> XG boost.
-> Naive Baise.
# Required Libraries
Numpy,
Pandas,
Matplotlib,
Seaborn,
Scikit-learn,
# Accuracies

   Model	                  Score
	Decision Tree	         80.43,
	XG Boost	               79.89,
	K-Nearest Neighbors	   78.80, 
	Random Forest	         77.72,
	Naive Baise	            77.72,
	Logistic regression	   77.72,
	Support Vector Machine  76.09,
