# Predicting-diabetes-in-patients

**Business Problem:**

Identifying patients who are at high risk of becoming diabetic using patient characteristics such as Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction	and Age

**Model Approach:**

Trained three machine learning models - Logistic Regression, Random Forest and Decision tree - to classify the patient's likeliness to get diabetic basis the patient characteristics listed above.

**Model Results:**

Most important consideration in the field of medicine is the correct prediction of true positives. This is because the cost of not identifying the true positive can be patient's health. 

Since, it is very important to control false negatives i.e. properly predict true prositves, we consider RECALL to be the most important parameter to assess model performance. 

LOGISTIC REGRESSION:
We see that model correctly classifies 77.22% true positives (recall), 74.28% (precision) of patients truly have diabetes of the positively predicted patients. ROC AUC score and accuracy of the model is 75%.

RANDON FOREST:
We see that model correctly classifies 87.13% true positives (recall), 77.87% (precision) of patients truly have diabetes of the positively predicted patients. ROC AUC score and accuracy of the model is 81%.

DECISION TREE:
We see that model correctly classifies 80.19% true positives (recall), 75.70% (precision) of patients truly have diabetes of the positively predicted patients. ROC AUC score and accuracy of the model is 77%.

COMPARISON:
Most important consideration in the field of medicine is the correct prediction of true positive. This is because the cost of not identifying the true positive can be patient's health. 

As we have established that RECALL is the most important parameters to consider in the medical field, Random Forest has highest recall of 86.13% amongst all the models. Its precision and ROC AUC score are greater than the other two models. Basis this, Random Forest is the best model amongst the three to predict diabetes in the patients.
