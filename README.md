# Credit_Risk_Analysis
## Background
Machine learning is the use of statistical algorithms to perform tasks such as learning from data patterns and making prefictions. In this module, machine learning is used to predict loan status, such as whether the borrower is good for the bank to lend money. Several techniques are used such as resampling and ensemble. 

Different models are used in this module to predict data, the accuracy of models are analyzed. 


##Results

### Resampling

The accuracy score is shown below for the resampling method used: 
  Naive Random Oversampling: 0.65
  SMOTE Oversampling:0.66
  Undersampling: 0.54
  Combination Sampling: 0.64
  
According accuracy score, SMOTE oversampling performs the best among the four methods; 

The precision score is shown below for the resampling method used: 
  Naive Random Oversampling: 0.99
  SMOTE Oversampling:0.99
  Undersampling: 0.99
  Combination Sampling: 0.99

According precision score, the four resampling used give out the same results as performance;that maybe becuase too small number of of high risk in the y_test. y test need to scaled as well in order to have precision score shows significances of differenrece. 



### Ensemble

The accuracy score is shown below for the ensemble methods used: 
  Balanced Random Forest Classifier: 0.73
  Easy Ensemble AdaBoost Classifier:0.93

Easy Ensemble AdaBoost indicated a high accuracy score comparing to Balanced Random Forest. 

Both ensemble classifier shows similar precision number. 

##Summary

based on the analysis, Easy Ensemble AdaBoost classifier shows the highest accuracy score thus is recommended as the best modeling to use. 

Loan prediction is not the same as diagnosing cancer, high sensitivity will introduce problems as good borrower cannot get the loan from the bank. In this case, accuracy is more important than sensitivity. 

