Comparing Classifiers
=====================

Overview
--------

This project analyzes the performance of classifiers 
(KNN, LogisticRegression, DecisionTree and Support Vector Maschines).
The performance will be measured for a given dataset related to marketing 
bank products sold via telephone. 

Dataset
-------

For analyzing and modeling the following features of the dataset are used:
 1.) Age of the client
 2.) Job status of the client
 3.) Marital status of the client
 4.) Education of the client
 5.) Credit status of the client (has client current credits running)
 6.) Housing_credit status. Has the client a credit for house
 7.) Personal_credit status. Has the client a credit running for personal things.

Baseline
--------
 The baseline for a good performing classifier is an accuracy of greater than 85%.


Findings
--------

The analyzation was done with four models to find out which performs best for the end user.
The end user are business or marketing manager of a bank.


The following results was found:
  # All four classifiers show the same accuracy results of 87%.
  # The 'DecisionTree' model could be easy used from the marketing people to understand the behavior of the telephone clients.
    Furthermore the 'DecisionTree' is usable with out computer. Therefore the bank employee can use the tree plot to understand
    the behavior.
  # The 'LogisticRegression' classifier is good for computing the classification.
    Therefore the classification could be done in a small excel sheet.
  # The SVM classifier was similar good from the accuracy, but is hard to compute the predictions.
    For each prediction around 13500 samples have to be computed.
    This is not usable for the end user.
  # The KNN classifier was similar good from the accuracy, but is also not easy to compute the predictions.
    There is also a computer program necessary to predict new samples.
     
The exact parameter will be shown in the attached jupyter notebook file (practial_app_III.ipynb).
  

Recommendation
--------------

The prediction could be done easiest with the 'DecisionTree' classifier if no computer should be used.
--> Use the DecisionTree plot

The prediction could also be done in an simple way with the 'LogisticRegression' classifier and an excel sheet calculation.


Next Steps
----------

For further improve the model performance additional features could be created and proved.
Maybe new features could be:
# Current available amount of money on a bank account
# Monthly savings
