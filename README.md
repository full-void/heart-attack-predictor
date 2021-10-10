# Heart Attack Predictor
------------------------

This notebook takes tidy data and does exploratory analysis and builds models to predict heart attack. 

The data is taken from [this Kaggle dataset](https://www.kaggle.com/rashikrahmanpritom/heart-attack-analysis-prediction-dataset)

This notebook is also available on [Kaggle Here](https://www.kaggle.com/abhinavgargacb/heart-attack-eda-predictor-95-accuracy-score/notebook) and has been awarded with Silver medal.

## Brief Dataset Info
---------------------

The target variable is called `output` and contains either 0 or 1 for whether the patient had heart attack or not

Other variables have information about patient's age, sex, chest pain type, resting blood pressure, cholesterol, fasting blood sugar above certain level, resting electrocardiographic results, maximum heart rate achieved, previous peak, slope, number of major vessels, thalium stress test result, exercise induced angina

## The Notebook
---------------

The notebook contains the following processes:
* Preliminary Analysis
* Exploratory Data Analysis
	- Univariate Analysis
	- Bivariate Analysis
* Model Development
	- Feature Engineering
	- Training and testing various models including Logistic Regression, SVM, Random Forest, Gradient Boost
	- Stacking
	- Plotting the model results and comparing models