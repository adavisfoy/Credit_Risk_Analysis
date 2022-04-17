# Credit Risk Analysis: Analysis of Supervised Machine Learning Models


## Overview of the analysis: 
The purposes of this analysis was to evaluate the performance of 6 different machine learning models for predicting credit risk. The models we evaluated included two oversampling algorithms, one undersampling algorithm, one combination over-and-undersampling algorithm, and two Ensemble algorithms as follows:  

1. Naive Random Oversampling
2. SMOTE Oversampling
3. Cluster Centroids Undersampling
4. SMOTTEENN Over- and Under-Sampling
5. Ensemble Balanced Random Forest Classification
6. Easy Ensemble AdaBoos Classification


## Results: 
Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models.

- Measuring "Precision" (aka positive predictive value - PPV) gives us the ability to say whether or not our predicated positive observations actually were positive observations. 
  - Precision = TP / (TP + FP).   
- Measuring "Recall" (or sensitivity) helps us evaluate whether or not we are missing out on other positive observations (e.g. false negatives). We must evaluate both true positives and false negatives. Recall is a measure of how many of our actual positives were correctly predicted. 
  - Recall = TP / (TP + FN) 


**Supervised Learning Models: Performance Summary**

![Model_Performance_Summary.png](images/Model_Performance_Summary.png)


**Naive Random Oversampling**

![Naive_Random_Oversampling.png](images/Naive_Random_Oversampling.png)


**SMOTE Oversampling**

![SMOTE_Oversampling.png](images/SMOTE_Oversampling.png)


**Cluster Centroids Undersampling**

![Cluster_Centroids_Undersampling.png](images/Cluster_Centroids_Undersampling.png)


**SMOTEENN Over- & Under- Sampling**

![SMOTEENN_Over_Under_Sampling.png](images/SMOTEENN_Over_Under_Sampling.png)


**Ensemble: Balanced Random Forest Classifier**

![Ensemble_Balanced_Random_Forest_Classifier.png](images/Ensemble_Balanced_Random_Forest_Classifier.png)


**Easy Ensemble AdaBoost Classifier**

![Easy_Ensemble_AdaBoost_Classifier.png](images/Easy_Ensemble_AdaBoost_Classifier.png)


## Summary: 
Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. 
If you do not recommend any of the models, justify your reasoning.
