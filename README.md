# Credit_Risk_Analysis

## Overview of the Analysis

The purpose of this analysis was to determine credit risk for our lending services company.  In order to do this, we employed different techiniques to train and evaluate models with unbalanced classes of data.  Techniques used included:

-  Naive Random Oversampling
-  SMOTE Oversampling
-  Undersampling
-  Combination (SMOTEENN)
-  Balanced Random Forest Classifier
-  Easy Ensemble Classifier

## Results

-  Naive Random Oversampling
<div class="container" align="left">
  <div style="background-image">
    <h5 align="left">Accuracy Score: 64.6%</h5>
    <img src="https://github.com/nseddon/Credit_Risk_Analysis/blob/main/images/Naive_accuracy.PNG">
  </div>
</div>

<div class="container" align="left">
  <div style="background-image">
    <h5 align="left">High-Risk Precision Score: 1%<br>High-Risk Recall Score: 71%</h5>
    <img src="https://github.com/nseddon/Credit_Risk_Analysis/blob/main/images/Naive_precision_recall.PNG">
  </div>
</div><br>

-  SMOTE Oversampling
<div class="container" align="left">
  <div style="background-image">
    <h5 align="left">Accuracy Score: 65.9</h5>
    <img src="https://github.com/nseddon/Credit_Risk_Analysis/blob/main/images/SMOTE_accuracy.PNG">
  </div>
</div>

<div class="container" align="left">
  <div style="background-image">
    <h5 align="left">High-Risk Precision Score: 1%<br>High-Risk Recall Score: 63%</h5>
    <img src="https://github.com/nseddon/Credit_Risk_Analysis/blob/main/images/SMOTE_precision_recall.PNG">
  </div>
</div><br>

-  Undersampling
<div class="container" align="left">
  <div style="background-image">
    <h5 align="left">Accuracy Score: 65.9%</h5>
    <img src="https://github.com/nseddon/Credit_Risk_Analysis/blob/main/images/Undersampling_accuracy.PNG">
  </div>
</div>

<div class="container" align="left">
  <div style="background-image">
    <h5 align="left">High-Risk Precision Score: 1%<br>High-Risk Recall Score: 69%</h5>
    <img src="https://github.com/nseddon/Credit_Risk_Analysis/blob/main/images/Undersampling_precision_recall.PNG">
  </div>
</div><br>

-  Combination (SMOTEENN)
<div class="container" align="left">
  <div style="background-image">
    <h5 align="left">Accuracy Score: 54.4%</h5>
    <img src="https://github.com/nseddon/Credit_Risk_Analysis/blob/main/images/Combination_accuracy.PNG">
  </div>
</div>

<div class="container" align="left">
  <div style="background-image">
    <h5 align="left">High-Risk Precision Score: 1%<br>High-Risk Recall Score: 72%</h5>
    <img src="https://github.com/nseddon/Credit_Risk_Analysis/blob/main/images/Combination_precision_recall.PNG">
  </div>
</div><br>

-  Balanced Random Forest Classifier
<div class="container" align="left">
  <div style="background-image">
    <h5 align="left">Accuracy Score: 75.4%</h5>
    <img src="https://github.com/nseddon/Credit_Risk_Analysis/blob/main/images/BRFC_accuracy.PNG">
  </div>
</div>

<div class="container" align="left">
  <div style="background-image">
    <h5 align="left">High-Risk Precision Score: 3%<br>High-Risk Recall Score: 64%</h5>
    <img src="https://github.com/nseddon/Credit_Risk_Analysis/blob/main/images/BRFC_precision_recall.PNG">
  </div>
</div><br>

-  Easy Ensemble Classifier
<div class="container" align="left">
  <div style="background-image">
    <h5 align="left">Accuracy Score: 93.2%</h5>
    <img src="https://github.com/nseddon/Credit_Risk_Analysis/blob/main/images/EEC_accuracy.PNG">
  </div>
</div>

<div class="container" align="left">
  <div style="background-image">
    <h5 align="left">High-Risk Precision Score: 9%<br>High-Risk Recall Score: 92%</h5>
    <img src="https://github.com/nseddon/Credit_Risk_Analysis/blob/main/images/EEC_precision_recall.PNG">
  </div>
</div><br>

## Summary
As can be seen from the results, the following models had lower than desired accuracy scores (defined as less than 75% accuracy) and recall scores:
-  Naive Random Oversampling
-  SMOTE Oversampling
-  Undersampling
-  Combination (SMOTEENN)

The Ensemble models had better accuracy scores, but the Easy Ensemble Classifer (EEC) model preformed the best with the highest scores in all categories:
-  Accuracy: 93.2%
-  High-Risk Precision: 9%
-  High-Risk Recall: 92%

With the given data, it would be recommended to perform future analysis with an EEC model, but additional data and configuration could potentially all models to be improved.
