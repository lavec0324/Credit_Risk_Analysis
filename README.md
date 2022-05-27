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

[](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Tools_v1_00.tsv.gz)

Pyspark was used to analyze the data.

## Results

How many Vine reviews and non-Vine reviews were there?
* After the initial filtering for total votes >= 20 and at least a 50% helpful votes to total votes, there were 31,737 reviews.
* Of those:
	* 285 were paid vine reviews
	* 31,452 were non-paid vine reviews

How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
* From the above filtered lists there were:
	* 163 were 5 star ratings for paid vine reviews
	* 14,603 were 5 star ratings for non-paid vine reviews

What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
* From the above 5 star ratings:
	* 57.2% were paid reviews
	* 46.4% were non-paid reviws

The code to produce this analysis can be seen here:

![](https://github.com/lavec0324/Amazon-Vine-Analysis/blob/main/Resources/Code1.PNG)
![](https://github.com/lavec0324/Amazon-Vine-Analysis/blob/main/Resources/Code2.PNG)
![](https://github.com/lavec0324/Amazon-Vine-Analysis/blob/main/Resources/Code3.PNG)

## Summary 

The results do seem to support that paid reviews could bias the percentage of overall ratings higher as the paid was almost 11% higher 5 star ratings.  It is possible that since the amount of vine paid reviews were much lower that the results could have also been skewed.  In addition to this analysis it might be good to also pull in 4 star ratings as this would also show top reviews.  It might also be good to determine the average of all results to see if the overall average of results was higher.




