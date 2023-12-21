# Fraud_Detection_Project


The datasets contains transactions made by credit cards in September 2013 by european cardholders. 
This dataset presents transactions that occurred in two days, where it has 492 frauds out of 284,807 transactions. 
The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

### The aim of this project is to predict whether a credit card transaction is fraudulent or not.


we did some Data Integrity Checks using Deepchecks.
<img width="1252" alt="Screenshot 2023-12-21 at 8 16 44 PM" src="https://github.com/atheermoh/CreditCard-Fraud-Detection-Project/assets/51926875/31b4a5e6-a246-4678-b568-742648ef5c9c">

<img width="1134" alt="Screenshot 2023-12-21 at 8 17 36 PM" src="https://github.com/atheermoh/CreditCard-Fraud-Detection-Project/assets/51926875/72c24573-1594-4b35-aa12-e12bf800c053">

<img width="1153" alt="Screenshot 2023-12-21 at 8 18 08 PM" src="https://github.com/atheermoh/CreditCard-Fraud-Detection-Project/assets/51926875/a654795e-7abb-44c9-bd6d-7ed20bcaac31">

### Performing (PCA) Principle Component Analysis 
we performed PCA for dimentionality reduction and visualizing the data in a scatterplot, the plot after the PCA 
gives a better visualization of the imbalance in the datasets.
<img width="638" alt="Screenshot 2023-12-21 at 8 26 56 PM" src="https://github.com/atheermoh/CreditCard-Fraud-Detection-Project/assets/51926875/c5dd431d-3b5f-4ae1-8cc2-a533b112ab1e">


### Checking messing values and outliers 
the box represents the (IQR) The Interquartile Range, the line inside the box is the median and these small spots extend to the minimum and maximum 
values within a certain range.
<img width="924" alt="Screenshot 2023-12-21 at 8 27 32 PM" src="https://github.com/atheermoh/CreditCard-Fraud-Detection-Project/assets/51926875/c9b218d7-196a-4163-8e5a-1ec1d13877b0">

### Comparing our built models

<img width="566" alt="Screenshot 2023-12-21 at 8 22 49 PM" src="https://github.com/atheermoh/CreditCard-Fraud-Detection-Project/assets/51926875/05cc9c2e-be22-423c-98ad-0bb4d67a2855">
<img width="1163" alt="Screenshot 2023-12-21 at 8 20 32 PM" src="https://github.com/atheermoh/CreditCard-Fraud-Detection-Project/assets/51926875/09297374-1985-47a6-9630-1554b6fd352a">



### our App after model deployment
<img width="1238" alt="Screenshot 2023-12-21 at 8 21 39 PM" src="https://github.com/atheermoh/CreditCard-Fraud-Detection-Project/assets/51926875/8b07598d-02c5-482d-b447-f161dada858c">


