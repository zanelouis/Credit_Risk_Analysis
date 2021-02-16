# Credit_Risk_Analysis

## Overview
In this module we will be using data preparation, statistical reasoning and apply machine learning to solve a real-world challenge: credit card risk. To begin, the imbalanced-learn and scikit-learn libraries are utilized to build and evaluate models using resampling. The credit card dataset from LendingClub is used to oversample data with the RandomOverSampler and SMOTE algorithms, then undersample that data with the ClusterCentroids algorithm. A combinational approach of over- and undersampling using the SMOTEENN algorithm is then applied. To conclude, we compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit card risk. 

## Resources
- Data Source: LoanStats_2019Q1.csv
- Software: Python 3.7.9, Anaconda Navigator 1.9.12, Conda 4.8.4, Jupyter Notebook 6.0.3, NumPy (v1.11 or later), SciPy (v0.17 or later), Scikit-learn (v0.21 or later)
- Environment: mlenv:

![image](https://user-images.githubusercontent.com/71358697/108029294-0e693500-6fe2-11eb-87df-1ff96059634c.png)

Results: the accuracy score is 65%, the precision is 99% and the recall is 61%

![image](https://user-images.githubusercontent.com/71358697/108029318-15904300-6fe2-11eb-836a-7fea363cd873.png)

Results: the accuracy score is 66%, the precision is 99% and the recall is 69%

![image](https://user-images.githubusercontent.com/71358697/108029335-19bc6080-6fe2-11eb-913d-ea595d8029e4.png)

Results: the accuracy score is 66%, the precision is 99% and the recall is 41%

![image](https://user-images.githubusercontent.com/71358697/108029342-1c1eba80-6fe2-11eb-986f-7dd9164bd909.png)

Results: the accuracy score is 54%, the precision is 99% and the recall is 57%

![image](https://user-images.githubusercontent.com/71358697/108029353-20e36e80-6fe2-11eb-92fa-1514ddd1abd5.png)

Results: the accuracy score is 79%, the precision is 99% and the recall is 87%

![image](https://user-images.githubusercontent.com/71358697/108029358-23de5f00-6fe2-11eb-8b5e-466e073cb774.png)

Results: the accuracy score is 93%, the precision is 99% and the recall is 94%

## Conclusion
The Easy Ensemble AdaBoost Classifier is the most accurate of all the tests due to having the highest accuracy and precision scores.
