# Credit_Risk_Analysis

The written analysis has the following:

Overview of the loan prediction risk analysis:

The purpose of this analysis is well defined (4 pt)
Results:

There is a bulleted list that describes the balanced accuracy score and the precision and recall scores of all six machine learning models (15 pt)

Results: Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

Summary:

There is a summary of the results (2 pt)
There is a recommendation on which model to use, or there is no recommendation with a justification (3 pt)


## Overview of Project
### Purpose of Project
In this project, I demonstrated my proficiency with supervised machine learning to:  split the data into training and testing sets, perform logistic regression, Calculate accuracy, precision, and sensitivity, and  create a confusion matrix.
### Background of Project
Fast Lending, a peer to peer lending services wants to use machine learning to predict credit risk. Management believes that this will provide a quicker and more reliable loan experience. It also believes that machine learning will lead to a more accurate identification of good candidates for loans which will lead to lower default rates. I have designed, implimented, and evulated the preformance of six machine learning algorithms that can be used to predit credit risk. 

---
## Results
There is a class imbalance between high and low risk credit loans. Since there are 347 high risk loans and 68,470 low risk loans, they will be labeled minority class and majority class respectively.  

<ins>Algorithm 1: RandomOversampler</ins>

Accuracy: 63.5%

Precision 

* High Risk (Minority Class): 1%
* Low Risk (Majority Class): 100%

Recall

* High Risk (Minority Class): 61% 
* Low Risk (Majority Class): 66%
 
<ins>Algorithm 2: SMOTE</ins>

Accuracy: 63.7%

Precision 

* High Risk (Minority Class): 1%
* Low Risk (Majority Class): 100%

Recall

* High Risk (Minority Class): 62% 
* Low Risk (Majority Class): 65%
 

<ins>Algorithm 3: ClusterCentroids</ins>

Accuracy: 52.9%

Precision 

* High Risk (Minority Class): 1%
* Low Risk (Majority Class): 100%

Recall

* High Risk (Minority Class): 61% 
* Low Risk (Majority Class): 45%
 

<ins>Algorithm 4: SMOTEENN</ins>

Accuracy: 63.8%

Precision 

* High Risk (Minority Class): 1%
* Low Risk (Majority Class): 100%

Recall

* High Risk (Minority Class): 70% 
* Low Risk (Majority Class): 57%
 

<ins>Algorithm 5: BalancedRandomForestClassifier</ins>

Accuracy: 77.8%

Precision 

* High Risk (Minority Class): 3%
* Low Risk (Majority Class): 100%

Recall

* High Risk (Minority Class): 67% 
* Low Risk (Majority Class): 89%
 

<ins>Algorithm 6: EasyEnsembleClassifier</ins>

Accuracy: 92.5%

Precision 

* High Risk (Minority Class): 7%
* Low Risk (Majority Class): 100%

Recall

* High Risk (Minority Class): 91% 
* Low Risk (Majority Class): 94%
 

---
## Summary 
June is a warmer month than December in O’ahu; however, the temperate difference between the months is inconsequential.  **By and large June is approximately 2-4 degrees warmer across statistical comparisons.** Therefore, the temperatures in June and December are so similar that temperature will not be a hindrance in opening the Surf and Shake shop. 

Two additional weather factors to consider are wind speed and amount of sunlight for June and December. 
* Since wind speed is an important element to surfing vis-à-vi waves, wind speed data may indicate if either month is more, less, or equally lucrative.  Do wind speeds vary from June to December in O’ahu?
* Sunlight is likely to bring in more customers for both surfing and ice cream. How do the number of sunny days, partly sunny days, and total days with sun vary from June to December in O’ahu?

