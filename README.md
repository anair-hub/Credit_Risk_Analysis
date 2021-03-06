# Credit_Risk_Analysis
Credit Risk Analysis

## Overview of the loan prediction risk analysis:

 This module involves credit risk which is an inherently unbalanced classification problem. Differennt techniques will be employed to train and evaluate models with unbalanced classes.

## Results:

There is a bulleted list that describes the balanced accuracy score and the precision and recall scores of all six machine learning models (15 pt)

Precision Score= (Predicted True/ (Predicted True + False Positive)
Precision(Precision, also known as positive predictive value (PPV)) = TP/(TP + FP)

Recall Score= (Predicted True/ Predicted True + False Negative)
Sensitivity(Recall) = TP/(TP + FN)

Recall Score= (Predicted True/ Predicted True + False Negative)

F1 Score(Harmonic Mean) =2(Precision * Sensitivity)/(Precision + Sensitivity)

### BalancedRandomForestClassifier

![Balanced_Random_Forest_Classifier](Images/Balanced_Random_Forest_Classifier.PNG)
 
Accuracy_score (r_squared)= .78
Precision= .99
Recall= .87

### Ensemble AdaBoost Classifier

![Easy_Ensemble_AdaBoost_Classifier](Images/Easy_Ensemble_AdaBoost_Classifier.PNG)

Accuracy_score (r_squared)= .91
Precision= .99
Recall= .90

### Naive Random Oversampling w/ Logistic Regression

![Naive_Random_Oversampling](Images/Naive_Random_Oversampling.PNG)

Accuracy_score (r_squared)= .64
Precision= .99
Recall= .60

### SMOTE Oversampling w/ Logistic Regression

![SMOTE_Oversampling](Images/SMOTE_Oversampling.PNG)

Accuracy_score (r_squared)= .66
Precision= .99
Recall= .69

### ClusterCentroids Undersampling w/ Logistic Regression

![Undersampling](Images/Undersampling.PNG)

Accuracy_score (r_squared)= .54
Precision= .99
Recall= .40

### Combination (Over and Under) Sampling w/ Logistic Regression

![Combination_(Over_and_Under)_Sampling](Images/Combination_(Over_and_Under)_Sampling.PNG)

Accuracy_score (r_squared)= .63
Precision= .99
Recall= .58



## Summary:

  Based on results, the best models that were generated to predict the unbalanced classification problem of credit risk are the Balanced Random Forest Classifier and Ensemble AdaBoost Classifier due to their scores(Balanced, precision and recall ~ 1). But I would recommend the Ensemble AdaBoost Classifier due to its higher overall scores for a classification prediction.
  My recommendation would be the Ensemble AdaBoost Classifier model due it it's higher overall scores. But in general observation was none of these results were accurate in predicting high-risk loans and the best was the Ensemble AdaBoost Classifier model if we were to choose one.
  
  
