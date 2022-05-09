# Diabetes-Prediction-ML-Model
Build a model to accurately predict whether the patients in the dataset have diabetes or not?
**Dataset Description**-The datasets consists of several medical predictor variables and one target variable (Outcome).
Predictor variables includes the number of pregnancies the patient has had, their BMI, insulin level, age, and more.

**Perform descriptive analysis**. Understand the variables and their corresponding values. On the columns below,
a value of zero does not make sense and thus indicates missing value:
Visually explore these variables using histograms.
We find out that data is imbalanced.
We analyse the data with help of various graph like count plot, histogram, bar plot, heat map,pair plot etc.
**Model Building**. after analysing data we go for model builduing so we split data with train test split.
first we trained our data set with Logistic regression it gives 72% accuracy.also checked with confusion matrix
we found FPR and FNR is high so obviously this is not appropriate model. so we tried Random forest and KNN classifier.
we got approximately simmilar results.
So we balanced our data with smote function and try again.This time we got better results .
We check with ROC and AUC curve and we found KNN giving best results.

We also analyse data on Tableau



