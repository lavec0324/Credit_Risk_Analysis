# Credit Risk Analysis
Module 17

## Overview of the Analysis
The purpose of this analysis is to anaylyze a portfolio of loans and based on six different machine learning models determine whether the models can accurately predict whether each loan is a low or high credit risk.

The six difference machine learning models are:

* Naive Random Oversampling
* SMOTE Oversampling
* Cluster Centroid Undersampling
* SMOTEENN (Combination over and undesampling)
* Balanced Random Forest Classifier
* Easy Ensemble AdaBoost Classifier


## Results

By combining the results of each of the learning models in the below table you can visualize comparison results:

![](https://github.com/lavec0324/Credit_Risk_Analysis/blob/main/resources/summary_graph.png)

In addition, you can see from the balanced random forest classifier top ten fields that were used in terms of importance:

![](https://github.com/lavec0324/Credit_Risk_Analysis/blob/main/resources/top_ten_features.png)


## Summary 

In summary there were varying degrees of success with models but the Easy Ensemble AdaBoost Classifier consistently provided at least or better results than the five other models. One note to identify is while the accruacy was very high on the high_risk predictions, the precision and F1 scores were very low.  Filtering out high risk loans would be a main imperative of this model and none of these models are able to do that at a high rate. With the current configuration it may not make sense to use these model to predict Credit Risk however these models could potentially be tweaked to limit the fields used in the analysis to more definitive indicators such as DTI and it may produce better results.



