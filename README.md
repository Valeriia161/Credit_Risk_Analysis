# ` Credit_Risk_Analysis `

## `Project Overview ` <br/>
The purpose of Credit_Risk_Analysis is to apply machine learning techniques to solve a real-world challenge: credit card risk.  <br/>
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. 
In this project I had  access to dataset from LendingClub, a peer-to-peer lending services company. I  oversampled the data using the RandomOverSampler and SMOTE algorithms, and undersampled the data using the ClusterCentroids algorithm. Then, I used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, I compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Then I  evaluated the performance of these models and made a written recommendation on whether they should be used to predict credit risk. <br/>


#### Resources <br/>
• Data Source: [Google](https://www.google.com/), [LendingClub Credit Card Credit Dataset](https://github.com/Valeriia161/Credit_Risk_Analysis/blob/main/LoanStats_2019Q1.zip) <br/> 
• Software: Jupiter, Python, Git Bash, GitHub. <br/>

Deliverable 1. <br/>
Using knowledge of the imbalanced-learn and scikit-learn libraries, I evaluated three machine learning models by using resampling to determine which is better at predicting credit risk.  <br/>
First, I used the oversampling RandomOverSampler  algorithm to resample the dataset, view the count of the target classes, train a logistic regression classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report. <br/>

![image](https://user-images.githubusercontent.com/110998103/205531530-b4d6f05a-f2f8-4bb1-95af-b6748bee282d.png)



Second, I used the oversampling  SMOTE  algorithm to resample the dataset, view the count of the target classes, train a logistic regression classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report. <br/>

![image](https://user-images.githubusercontent.com/110998103/205531589-1be34e7d-baa9-4af5-a987-ce55393bfd0b.png)


Third, I used the undersampling ClusterCentroids  algorithm to resample the dataset, view the count of the target classes, train a logistic regression classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report. <br/>
 
![image](https://user-images.githubusercontent.com/110998103/205531833-86ec117d-0d03-483b-9f59-1d49361cb073.png)

