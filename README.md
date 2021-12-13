# Credit_Risk_Analysis

## Purpose

The purpose of this analysis is to use the different types of machine learning models (unsupervised) to predict credit risk. Comparing the different models and choosing the best model for the company Fast Lending.

## Results

### Oversampling
	
* Naïve
	
	The results from this model show an accuracy of 64%. With precision 	rates for high and low risk at 1% and 100%. The recall for high and 	low risk at 62% and 65%.

* SMOTE
	The results from this model show an accuracy of 63%. With precision 	rates for high and low risk at 1% and 100%. The recall for high and 	low risk at 62% and 64%.


### Under sampling

The results from this model show an accuracy of 52%. With precision rates for high and low risk at 1% and 100%. The recall for high and low risk at 60% and 43%.

### Combination Sampling

The results from this model also shows an accuracy of 52%. With precision rates for high and low risk at 1% and 100% as well. The recall for high and low risk at 70% and 57%.

### Balanced Random Forest Classifier

The results from this model also shows an accuracy of 78%. With precision rates for high and low risk at 4% and 100%. The recall for high and low risk at 67% and 91%.

## Summary

The accuracy scores in this circumstance aren’t the best indicator have a great machine learning model as 90% of the data set could’ve been low risk and if the machine predicted all to be low risk, then it would’ve only missed 10% yielding good accuracy scores. 

Looking over the precision to see how the models fare in identifying between the two classifications. It seems none of the models are spectacular. However, the majority of the models do have a significantly lower precision rate for predicting high risk than low risk. As for the recall numbers the models were able to identify high risk better than low risk. 

Overall, I wouldn’t recommend any of these models as they didn’t yield the best results in predicting high credit risk. I recommend trying out decision tree in filtering for high and low risk in lending out loans. 
