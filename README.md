# Ways-to-Handle-Imbalenced-Dataset-Credit-Card-Fraud
Imbalanced data is one of the major problem in the area of machine learning. This problem can be solved by analyzing the dataset in hand. There are several approaches that will help us to handle the problem of imbalanced classes. These are oversampling, underdamping, synthetic data generation (SMOTE), adaptive synthetic technique and ensemble methods. These methods are discussed in the sections below.

• Assessed various techniques to handle imbalanced datasets. Imbalanced Datasets such as, credit card fraud, Earthquake prediction, 
Disease detection dataset creates issue of biased models

• Completed analysis by scaling imbalanced dataset with various oversampling and under sampling techniques. With AWS 
SageMaker trained and tested ML models in python and Scikit-learn

• Concluded oversampling is better than under sampling dataset, as it removes valuable data. Oversampling increased the accuracy of 
model from 86% to 99%

Summary:

Imbalanced data is one of the major problem in the area of machine learning. This problem can be solved by analyzing the dataset in hand. There are several approaches that will help us to handle the problem of imbalanced classes. These are oversampling, undersampling, synthetic data generation (SMOTE), adaptive synthetic technique and ensemble methods. These methods are discussed in the previous sections.

Some combination of these approaches will help us to create a better classifier. Simple sampling techniques may handle slight imbalance whereas more advanced methods like ensemble methods are required for extreme imbalances. The most effective technique will vary according to the dataset.

So, based on above discussion, we can conclude that there is no one solution to deal with the imbalanced class problem. We should try out multiple methods to select the best-suited sampling techniques for the dataset in hand. The most effective technique will vary according to the characteristics of the dataset.

**For this dataset oversampling works better than undersampling**

However in some cases models of oversampling are overfitting, because they are performing great on training set but performing poorly on testing set. 

Finally, While working on the imbalanced dataset one should try various methods. And should use scores like ROC AUC, Precision Recall, Confusion Matrix to check the accuracy of model.
