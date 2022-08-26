# Credit_Risk_Analysis
## Overview of Project
### Purpose of Project
In this project, I demonstrated my proficiency with supervised machine learning to:  split the data into training and testing sets, perform logistic regression, Calculate accuracy, precision, and sensitivity, and  create a confusion matrix.
### Background of Project
Fast Lending, a peer to peer lending services wants to use machine learning to predict credit risk. Management believes that this will provide a quicker and more reliable loan experience. It also believes that machine learning will lead to a more accurate identification of good candidates for loans which will lead to lower default rates. I have designed, implemented, and evaluated the performance of six machine learning algorithms that can be used to predict credit risk. 

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
The EasyEnsembleClassifier is the best of the six algorithms. It has the best results across all metrics including an accuracy of 92.5%. However, there is concern about the precision of the high risk loans. Since precision is the true high risk loans divided by the sum of the true high risk loans and loans incorrectly labeled high risk (i.e. Precision = TP/(TP + FP)), the algorithm is labeling a significant number of loans high risk that would otherwise be labeled low risk. In fact, for every 100 loans labeled high risk, only 7 of them would actually be high risk. If Fast Lending uses this algorithm, there will be many loans inaccurately labeled high risk. Therefore, it would be best not to use any of these models.  
