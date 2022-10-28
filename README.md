# Credit_Risk_Analysis


## Overview:
The purpose of analysis is to build and evaluate several machine learning models to predict credit risk which can help banks and financial institutions predict anomalies, reduce risk cases, monitor portfolios, and provide recommendations on what to do in cases of fraud
       we used the statistical algorithms to perform tasks to know the data patterns and making predictions to predict cradict risk.
 
 
 ## Results:
 After performing all the basic data cleaning we Split the Data into Training and Testing to perform and check the efficiency, credibility and accuracy of different machine learning models.Following are the results of six different machine learning models.
 
## 1: Naive Random Oversampling(LogisticRegression)
 
### Confusion matrix:
 
  [   56,    36]
  
  [ 6021, 11092]
 
### classification report:

 ![1](https://user-images.githubusercontent.com/108497494/198456887-d74a2bc4-a0eb-419d-8a1c-9bdd55c38d83.jpg)
 
## 2: SMOTE Oversampling:

### Confusion matrix:
 
  [   54,    38]
  
  [6014, 11099]
 
### classification report:
 
 ![2](https://user-images.githubusercontent.com/108497494/198456974-d5155af0-9058-406b-94f9-6d6f2f882dc4.jpg)

 
## 3: Undersampling:

### Confusion matrix:
 
  [54,   38]
  
  [9847, 7266]
 
### classification report:
 
 ![3](https://user-images.githubusercontent.com/108497494/198457033-2889e566-717d-4aa0-8f34-df1e171e5d74.jpg)

 
## 4: Combination (Over and Under) Sampling:

### Confusion matrix:
 
  [66,   26]
  
  [7407, 9706]
 
### classification report:
  
  ![4](https://user-images.githubusercontent.com/108497494/198457161-cbe65a53-63bc-4638-b411-a154959a2255.jpg)

  
## 5: Balanced Random Forest Classifier:

### Confusion matrix:
 
  [62,    30]
  
  [1991, 15122]
 
### classification report:
 
 ![5](https://user-images.githubusercontent.com/108497494/198457242-a0b91d94-720f-4bce-87d5-918abead20f8.jpg)

 
## 6: Easy Ensemble AdaBoost Classifier:

### Confusion matrix:
 
  [  85,     7]
  
  [1117, 15996]
 
### classification report:
 
 ![6](https://user-images.githubusercontent.com/108497494/198457302-3a43f013-82c9-4412-8b97-441b96438a8d.jpg)

 
 
 ## Summary:
 the results show the performance of different models using the same dataset.
  Easy Ensemble AdaBoost Classifier performed best among all with very less FALSE NEGATIVEs and comparatively less FALSE POSITIVEs.
 
 
 
