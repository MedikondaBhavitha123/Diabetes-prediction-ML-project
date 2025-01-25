# Diabetes Prediction using Machine Learning

## Introduction
Diabetes is a chronic (long-lasting) health condition that affects how your body turns food into energy. In order to receive their reports following consultation, the patient must go to a diagnostic facility. Due to this, they have to invest their time and money. The risk factor and severity of diabetes can be reduced significantly if precise early prediction is possible.

With the growth of Machine Learning methods, we have the flexibility to find a solution to this issue. The robust and accurate prediction of diabetes is highly challenging due to the limited number of labeled data and the presence of outliers (or missing values) in diabetes datasets. The aim of this analysis is to develop a system that can predict the diabetic risk level of a patient with better accuracy. In this study, we propose a robust framework for diabetes prediction where outlier rejection, filling missing values, data standardization, feature selection, K-fold cross-validation, and different Machine Learning (ML) classifiers are utilized.

## Objective
We aim to build a machine learning model to accurately predict whether or not the patients in the dataset have diabetes.

## Details about the Dataset
- **Summary of data**: 768 rows, 9 columns, no null values.
- **The 9 columns in our dataset are:**
  1. **Pregnancies** - Number of times pregnant.
  2. **Glucose** - Plasma glucose concentration for 2 hrs in an oral glucose tolerance test.
  3. **Blood Pressure** - Diastolic blood pressure (mm Hg).
  4. **Skin Thickness** - Triceps skin fold thickness (mm).
  5. **Insulin** - 2-hour serum insulin (mu U/ml).
  6. **BMI** - Body mass index (weight in kg/(height in m)^2).
  7. **DPF** - Diabetes pedigree function.
  8. **Age** - Age in years.
  9. **Outcome** - Class variable (0 or 1).

## Result
As the project is totally based on the prediction of a person
whether he/she was diabetic or not. Inorder to get our
desired results. We first visualized the data using different
graphs. And then we started splitting the data in order to
perform the machine learning algorithms. KNN, SVM,
MLP, Logistic, Linear and so on are the algorithms that are
performed to classify the data.
After testing these models, we found that **Logistic Regression** was the best classifier for diabetes prediction, achieving an **accuracy of 78%**.

## Conclusion
Using machine learning techniques, we developed a system capable of predicting diabetes with good accuracy. Further improvements can be made by fine-tuning the model, handling outliers better, and incorporating deep learning approaches for enhanced performance.

