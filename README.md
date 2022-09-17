# Logistic-Regression-to-predict-Heart-Disease
Predicting and diagnosing heart disease is the biggest challenge in the medical industry and relies on factors such
as the physical examination, symptoms and signs of the patient.

Factors that influence heart disease are body cholesterol levels, smoking habit and obesity, family history of illnesses,
blood pressure, and work environment. Machine learning algorithms play an essential and precise role in the prediction of heart disease.

Advances in technology allow machine language to combine with Big Data tools to manage unstructured and exponentially growing data. 
Heart disease is seen as the world’s deadliest disease of human life. 

In particular, in this type of disease, the heart is not able to push the required amount of blood to the remaining organs of the human body to perform regular functions.

Heart disease can be predicted based on various symptoms such as age, gender, heart rate, etc. and reduces the death rate of heart patients.

Due to the increasing use of technology and data collection, we can now predict heart disease using machine learning algorithms. Now let’s go further for heart disease prediction using machine learning with Python.

Our primary alignment to the project involves
- Predicting whether a patient should be diagnosed with Heart Disease (binary outcome).
- Positive (+) = 1 => patient is diagnosed with Heart Disease.
- Negative (-) = 0 => patient is not diagnosed with Heart Disease.
- Experimenting with various Classification Models & see which yields the greatest accuracy.
- Examine trends & correlations in our data.
- Determine the features that are most important to Positive/Negative Heart Disease diagnosis.

## ABSTRACT
As per the recent study by WHO, heart related diseases are increasing. 17.9 million
people die every-year due to this. With a growing population, it gets further difficult to
diagnose and start treatment at an early stage. But due to the recent advancement in
technology, Machine Learning techniques have accelerated the health sector by multiple
researches. Thus, the objective of this paper is to build a ML model for heart disease
prediction based on the related parameters. We have used a benchmark dataset of UCI Heart
disease prediction for this research work, which consist of 14 different parameters related to
Heart Disease. Machine Learning algorithms such as Random Forest, Support Vector
Machine (SVM), Naive Bayes and Decision tree have been used for the development of
models. In our research we have also tried to find the correlations between the different
attributes available in the dataset with the help of standard Machine Learning methods and
then using them efficiently in the prediction of chances of Heart disease. Result shows that
compared to other ML techniques, Random Forest gives more accuracy in less time for the
prediction. This model can be helpful to the medical practitioners at their clinic as a decision
support system.

## Features & Predictor:
Predictor (Y, Positive or Negative diagnosis of Heart Disease) is determined by 13 features (X):
1. age (#)
2. sex : 1= Male, 0= Female (Binary)
3. (cp)chest pain type (4 values -Ordinal):Value 1: typical angina ,Value 2: atypical
angina, Value 3: non-anginal pain , Value 4: asymptomatic
4. (trestbps) resting blood pressure (#)
5. (chol) serum cholesterol in mg/dl (#)
6. (fbs)fasting blood sugar > 120 mg/dl(Binary)(1 = true; 0 = false)
7. (restecg) resting electrocardiography results(values 0,1,2)
8. (thalach) maximum heart rate achieved (#)
9. (exang) exercise induced angina (binary) (1 = yes; 0 = no)
10. (oldpeak) = ST depression induced by exercise relative to rest (#)
11. (slope) of the peak exercise ST segment (Ordinal) (Value 1: up sloping , Value
2: flat , Value 3: down sloping )
12. (ca) number of major vessels (0–3, Ordinal) colored by fluoroscopy
13. (thal) maximum heart rate achieved — (Ordinal): 3 = normal; 6 = fixed defect; 7 = reversible defect

There are 3 types of Data:
- Continuous (#): which is quantitative data that can be measured
- Ordinal Data: Categorical data that has a order to it (0, 1, 2, 3, etc)
- Binary Data: data whose unit can take on only two possible states ( 0 & 1 )

The accuracy determined is 78.6%
