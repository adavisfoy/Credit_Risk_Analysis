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

We can evaluate a model's performance based on various metrics including balanced accuracy scores, precision scores, and recall scores. 

- "Recall" (or sensitivity) measures how many people who actually have a condition were correctly predicted as such. This metric takes into account all positives, including both true positives and false negatives.  
  - Recall = TP / (TP + FN) 
  - In the context of our credit risk analysis, recall evaluates both whether an applicant is a high credit risk and was predicated to be so (true positive) taking into account any false negatives (those who have high credit risk but were not identified as such). 
  - In the contact of our credit risk analysis, high recall means that among people who actual are high risk loan candidates, most of them will be identified by the model as such.
- Measuring "Precision" (aka positive predictive value - PPV) gives us the ability to say whether or not our predicated positive observations actually were positive observations. 
- Precision = TP / (TP + FP).   
  - In the contact of our credit risk analysis, high precision means that if an applicant was identified as high risk, there's a high likelihood that the applicant actually is high risk. Said another way: Among people who actual are high risk loan candidates, most of them will be identified by the model as such. 
- For example, let's say that among 100 people, 50 are high risk credit applicants and 50 are not. A very aggressive machine learning algorithm labels everyone as a high risk applicant. Since everyone who actually is high risk is detected, the recall is 1.0 (100%). However, the precision is low: being identified as high risk in this case only means a 50% likelihood of actually being high risk. In other words, there are many false positives. 
- Since there is a tradeoff between precision and sensitivity, we must determine which is more important for our particular use case: high precision or high recall. 
  - In the context of our credit risk analysis, high recall seems more important since it is better to detect all high risk credit applicants, even if there might be some false positives. It would be very costly if we missed these applicants and may be worth lenders' time to pursue further analysis to confirm or rule out false-positive high risk applicants.  

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
