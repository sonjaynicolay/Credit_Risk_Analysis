# Credit Risk Analysis


## Overview of the loan prediction risk analysis


Credit risk is an unbalanced classification problem due to good loans highly outnumbering risky loans. The following analysis utilized numerous techiniques to train and evaluate models created to analyze loan risk with unbalanced classes. To get the results of this analysis first models were built and evaluated using resampling. The data was then oversampled and undersampled using different algorithms, the bias was reduced to predict credit risk and the performance evaluated based on those results.
 
---
## Results of the loan prediction risk analysis


###  Random Over Sampler
####    -Balanced Accuracy Score: .66
####    -Precision: High Risk: .01 Low Risk: 1.00
####    -Recall Scores: High Risk: .66 Low Risk: .67

###  Smote Oversampling
####    -Balanced Accuracy Score: .63
####    -Precision: High Risk: .01 Low Risk: 1.00
####    -Recall Scores: High Risk: .62 Low Risk: .64

###  Cluster Centroids
###      -Balanced Accuracy Score: .63
####     -Precision: High Risk: .01 Low Risk: 1.00
####     -Recall Scores: High Risk: .62 Low Risk: .41

###  SMOTEENN
####     -Balanced Accuracy Score: .64
####     -Precision: High Risk: .01 Low Risk: 1.00
####     -Recall Scores: High Risk: .70 Low Risk: .57

###  Balanced Random Forest Classifier
####     -Balanced Accuracy Score: .66
####     -Precision: High Risk: .01 Low Risk: 1.00
####     -Recall Scores: High Risk: .66 Low Risk: .67

###  Random Oversampler
####     -Balanced Accuracy Score: .66
####     -Precision: High Risk: .01 Low Risk: 1.00
####     -Recall Scores: High Risk: .66 Low Risk: .67
 
There is a bulleted list that describes the balanced accuracy score and the precision and recall scores of all six machine learning models (15 pt)
## Summary of the risk analysis

There is a summary of the results (2 pt)
There is a recommendation on which model to use, or there is no recommendation with a justification (3 pt)
Submission
