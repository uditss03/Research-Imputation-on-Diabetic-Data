# Research-Imputation-on-Diabetic-Data

AIM – To find the combination of imputation method and classification Algorithm that will predict the best outcome in Pima Diabetes dataset.

## Context
This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage. This data is requested from the Govt. Of INDIA (data.gov.in).

## Content
The datasets consists of several medical predictor variables and one target variable, Outcome. Predictor variables includes the number of pregnancies the patient has had, their BMI, insulin level, age, and so on. The aim is impute the dataset with the best model and to use the suitable classification algorithm to predict the outcome.

* SVD ITERATIVE IMPUTER AND NAIVE BAYES CLASSIFIER – 
                   70.129% of Accuracy

* SOFT IMPUTATION AND KNN CLASSIFIER –
                  72.42% of Accuracy

* KNN IMPUTATION AND LOGISTIC REGRESSION - 
                   75% of Accuracy
                   
### CHARGEUP IMPUTATION
Using the nuclear norm as a regularizer, we provide a simple and very efficient convex algorithm for minimizing the reconstruction error subject to a bound on the nuclear norm. ChargeUp iteratively replaces the missing elements with those obtained from a thresholded SVD. With warm starts this allows to efficiently compute an entire regularization path of solutions on a grid of values of the regularization parameter. The computationally intensive part of algorithm is in computing a low-rank SVD of a dense matrix. Exploiting the problem structure, shown that the task can be performed with a complexity of order linear in the matrix dimensions. 

CLASSIFICATION ALGS RESULTS AFTER CHARGEUP IMPUTATION :-

Logistic reg - 72.72%

Deep learning(3 Hidden layers) - 71.42%

