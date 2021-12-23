# Credit_Risk_Analysis :busts_in_silhouette:

Evaluate models with techniques to train and evaluate unbalanced classes.
Using imbalanced-learn and scikit-learn libraries to build and evaluate models for resampling.
By building two machine learnings, the goal is to reduce bias, `BalancedRandomForestClassifier` and `EasyEnsembleClassifier`, to predict credit risk.

The challege include:
Deliverable 1: Use Resampling Models to Predict Credit Risk
Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk
Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk

## Project Overview :eye_speech_bubble:

There are two machine learning models that predit through differnt algorithms to predict credit risk.
It has been used six methods:
1. Ensamble AdaBoost Classifier
2. Random Forest Classifier
3. Naive Random Oversampling
4. SMOTE Oversampling
5. SMOTEENN Analysis
6. Undersampling Analysis

## Resources

Through `Supervised Data` it is classified the data by: Assess Accuracy, Precision and Sensitivity.
The data is processed trough one of each model mentioned before where data is split in testing and training, so that compare accuracies, confusion matries and classification reports as the final results.

## Analysis and Challenges
 
* Credit Risk Ensamble Analysis

### Ensamble AdaBoost Classifier
Accuracy Score: 91.70%
Precision High Risk: 5%
Precision Low Risk: 100%
Recall High Risk: 91%
Recall Low Risk: 93%

![Ensemble_Adaboost_Classifier]()

### Random Forest Classifier
Accuracy Score: 64.81%
Precision High Risk: 56%
Precision Low Risk: 100%
Recall High Risk: 30%
Recall Low Risk: 93%

![Random_Forest_Classifier]()

* Credit Risk Resampling

### Naive Random Oversampling
Accuracy Score: 67.52%
Precision High Risk: 10%
Precision Low Risk: 100%
Recall High Risk: 66%
Recall Low Risk: 69%

![Naive_Random_Oversampling]()

### SMOTE Oversampling
Accuracy Score: 67.71%
Precision High Risk: 10%
Precision Low Risk: 100%
Recall High Risk: 70%
Recall Low Risk: 65%

![SMOTE_Oversampling]()

### SMOTEENN Analysis
Accuracy Score: 68%
Precision High Risk: 10%
Precision Low Risk: 100%
Recall High Risk: 76%
Recall Low Risk: 60%

![SMOTEENN_Analysis]()

### Undersampling Analysis
Accuracy Score: 51.94%
Precision High Risk: 0%
Precision Low Risk: 100%
Recall High Risk: 64%
Recall Low Risk: 40%

![Undersampling_Analysis]()

## Summary :raised_back_of_hand:

We can conclude after identifying all the efficiency of all the models used on detecting high or low risk of identifying least amount of high risk of loan to be undetected.
The correlating statistics for this is recall rate for high risk. 

- The best models that got the highest score is:
Ensamble AdaBoost Classifier with an accuracy of 91.70%

- The most precise model to detect low risk of undetectived loans is:
All models show 100%

- The most precise model to detect high risk of undetectived loans is
Random Forest Classifier

- Recall rate for low risk as it shows how many loans are flagged as hihg risk, the one that scored the higher rate is:
Ensamble AdaBoost Classifier

After factoring the main statistics, it is possible to say that Ensamble AdaBoost Classifier is the best model to predict high risk loans.
