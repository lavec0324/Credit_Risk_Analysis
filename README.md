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

The results do seem to support that paid reviews could bias the percentage of overall ratings higher as the paid was almost 11% higher 5 star ratings.  It is possible that since the amount of vine paid reviews were much lower that the results could have also been skewed.  In addition to this analysis it might be good to also pull in 4 star ratings as this would also show top reviews.  It might also be good to determine the average of all results to see if the overall average of results was higher.




