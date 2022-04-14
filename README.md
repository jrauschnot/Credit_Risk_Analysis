# Credit_Risk_Analysis

# Project Overview:
An analysis of credit default risk using supervised machine learning algorithms and pandas.  Various models were used to predict probability of default and accuracy of data. 


## Resources:

* Data Sources -  LoanStats_2019Q1.csv
* Software - Pandas, Machine Learning

## Results:

1. Naive Random Sampling:

<img width="796" alt="naive_random_oversampling" src="https://user-images.githubusercontent.com/93015602/163493568-d8a36e30-50bb-40c9-8469-91d38fe3a913.png">

2. SMOTE:

<img width="788" alt="smote" src="https://user-images.githubusercontent.com/93015602/163493593-efe24347-062f-43e6-a15b-ae21f5fd3e62.png">

3. Undersampling:

<img width="784" alt="undersampling" src="https://user-images.githubusercontent.com/93015602/163493597-dfb8aba4-34df-4b95-a392-67d72ad8da8d.png">

4. Combo:

<img width="789" alt="combo" src="https://user-images.githubusercontent.com/93015602/163493618-11cd2d0a-b078-4600-9674-d0380fbbb8f1.png">

5. Random Forest:

<img width="549" alt="random_forest" src="https://user-images.githubusercontent.com/93015602/163493605-723de32f-fd21-4dbf-a6ee-9ac359ed2447.png">

<img width="492" alt="RF_sorted" src="https://user-images.githubusercontent.com/93015602/163493608-3222e3a8-f1ac-4c05-8a91-1d548fd3e020.png">

6. Easy Ensemble

<img width="502" alt="adaBoost" src="https://user-images.githubusercontent.com/93015602/163493622-1f356e4f-3458-41d6-bbb2-edb99330bfd8.png">

## Summary:

- Upon review of the various machine learning models, we can determine the following:

* The balanced_random forrest model had the best accuracy score, precision, and F1 score.  The other machine learning models did not predict a balanced accuracy score or F1 that adequately represented the data. The Naive randome sampling, SMOTE, and Undersampling models were all similar with balanced accuracy scores of approximately 65% but very low F1 scores suggesting a pronounced imbalance between sensitivity and precision.


