# fraud-credit-card-detection
A project that addresses a challenge many financial institutions face: Credit Card Fraud Detection. With the digital economy growing rapidly, online transactions are becoming the norm. Unfortunately, this has also made fraudsters more sophisticated, leading to significant financial losses and eroding customer trust.

## Why is this project important?

In 2023 alone, credit card fraud accounted for billions in losses globally.
The average financial institution detects only a fraction of fraudulent transactions, while others slip through unnoticed.
Our goal in this project is to design a machine learning system that identifies fraudulent transactions with high accuracy and efficiency, focusing on minimizing false negatives, where fraud goes undetected.

## Understanding and Defining Fraud
Credit card fraud is any dishonest act and behaviour to obtain information without the proper authorization from the account holder for financial gain. Among different ways of frauds, Skimming is the most common one, which is the way of duplicating of information located on the magnetic strip of the card. Apart from this, the other ways are:
- Manipulation/alteration of genuine cards
- Creation of counterfeit cards
- Stolen/lost credit cards
- Fraudulent telemarketing

## Data set:
The data set includes credit card transactions made by European cardholders over a period of two days in September 2013. Out of a total of 2,84,807 transactions, 492 were fraudulent. This data set is highly unbalanced, with the positive class (frauds) accounting for 0.172% of the total transactions. The data set has also been modified with Principal Component Analysis (PCA) to maintain confidentiality. Apart from ‘time’ and ‘amount’, all the other features (V1, V2, V3, up to V28) are the principal components obtained using PCA. The feature 'time' contains the seconds elapsed between the first transaction in the data set and the subsequent transactions. The feature 'amount' is the transaction amount. The feature 'class' represents class labelling, and it takes the value 1 in cases of fraud and 0 in others.

