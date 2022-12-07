# ` Credit_Risk_Analysis `

## `Project Overview ` <br/>
The purpose of Credit_Risk_Analysis is to apply machine learning techniques to solve a real-world challenge: credit card risk.  <br/>
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. 
In this project I had  access to dataset from LendingClub, a peer-to-peer lending services company. I  oversampled the data using the RandomOverSampler and SMOTE algorithms, and undersampled the data using the ClusterCentroids algorithm. Then, I used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, I compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Then I  evaluated the performance of these models and made a written recommendation on whether they should be used to predict credit risk. <br/>


#### Resources <br/>
• Data Source: [Google](https://www.google.com/), [LendingClub Credit Card Credit Dataset](https://github.com/Valeriia161/Credit_Risk_Analysis/blob/main/LoanStats_2019Q1.zip) <br/> 
• Software: Jupiter, Python, Git Bash, GitHub. <br/>

`Deliverable 1.` <br/>
Using knowledge of the imbalanced-learn and scikit-learn libraries, I evaluated three machine learning models by using resampling to determine which is better at predicting credit risk.  <br/>
First, I used the oversampling RandomOverSampler  algorithm to resample the dataset, view the count of the target classes, train a logistic regression classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report. <br/>

![image](https://user-images.githubusercontent.com/110998103/205531530-b4d6f05a-f2f8-4bb1-95af-b6748bee282d.png)



Second, I used the oversampling  SMOTE  algorithm to resample the dataset, view the count of the target classes, train a logistic regression classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report. <br/>

![image](https://user-images.githubusercontent.com/110998103/205531589-1be34e7d-baa9-4af5-a987-ce55393bfd0b.png)


Third, I used the undersampling ClusterCentroids  algorithm to resample the dataset, view the count of the target classes, train a logistic regression classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report. <br/>
 
![image](https://user-images.githubusercontent.com/110998103/205531833-86ec117d-0d03-483b-9f59-1d49361cb073.png)


`Deliverable 2.` <br/>
Using knowledge of the imbalanced-learn and scikit-learn libraries, I used a combinatorial approach of over- and undersampling with the SMOTEENN algorithm to determine if the results from the combinatorial approach are better at predicting credit risk than the resampling algorithms from Deliverable 1. <br/>

![image](https://user-images.githubusercontent.com/110998103/205532247-e3edfbd8-16aa-4347-a5e5-ee4ed8f57ea7.png)

`Deliverable 3`. <br/>
Using knowledge of the imblearn.ensemble library, I trained and compared two different ensemble classifiers, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk and evaluate each model. <br/>

<img src="https://user-images.githubusercontent.com/110998103/205533225-bf0905b8-1eac-434d-a29d-c9f7408e3c0f.png" width=50% height=50%><img src="https://user-images.githubusercontent.com/110998103/205533943-d78699ef-a9ff-4093-aa43-16ee2156144c.png" width=50% height=50%>





<img src="https://user-images.githubusercontent.com/110998103/205533325-fb474ef4-9a7d-425c-a4a4-6f9c90c9a522.png" width=50% height=50%>


## `Summary` <br/>
Easy Ensemble AdaBoost Classifier outperformed the other models with an accuracy score of 93.15% while the other models were below 65%. But we should be extremely cautious about the 9 percent precision that it provides for High Risk Loans in the Easy Ensemble Adaboost Classifier.
Also The Easy Ensemble AdaBoost Classifier had the highest recall score, making it the best Machine Learning Model to choose for further credit card analysis.


