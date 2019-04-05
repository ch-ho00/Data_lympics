# Data_lympics
PwC data science hackathon.

## Aim of the Project

Given a large dataset of financial transactions of customers , how do we predict the expected loan repayment date? 

## Project work flow

1. Receive Data
2. Convert data into computable form
3. Feature filter
4. Classification/ Regression algorithms
5. Analysis of Result

## Libraries Used

1. Sklearn - logistic regression and xgboost model
2. Numpy  - for data processing and visualisation
3. Pandas - for data processing 
4. Keras - neural network model

## Detail of Project
#### 1. Receive Data
     
     Csv file containing 20k+ rows.
     Data contains 20 features which are
        ['InvoiceAmount', 'DocumentNo', 'PaymentDocumentNo', 'InvoiceItemDesc', 'ReferenceDocumentNo', 'duration', 'InvoiceDesc', \
        'Vendor 00332', 'UserName', 'TransactionCode', 'Vendor 01089', 'Vendor 00415', 'Period', 'Vendor 01024', 'Vendor 00070',  \
        'CompanyCode', 'TransactionCodeDesc', 'Vendor 01689', 'PO_FLag', 'Vendor 01532']
#### 2. Convert data into computable form

    Filling missing data with median data

    String data to one hot encoding

   
#### 3. Feature filter

    By checking colinearity of feature through VIF
    
    By checking correlation heat map 

    Feature extraction using PCA

  
#### 4.Classification/ Regression algorithms

    Logistic regression using

    Support Vector Machine
    
    Xgboost

    Neural Network

#### 5. Analysis of Result

    Check confusion matrix 
    
    Check the R square score

    Is it the problem of overfitting?
    If so, Possible approaches:
    1.  Oversampling.		
    2.  Early stopping by evaluating log loss.	
    3.  Feature reduction 
    4.  Regularization
    5.  Stratify data ( split data according to the labels proportion ) 

    What if it is not the problem of overfitting?

    1. Preprocessing work-flow 
    2. Retrieve Data 
    3. temp_data_process ( imputation with median or zeros ) 
    4. Oversampling with SMOTE ( Enable minor data to be sampled)
    5. Scale data to small range numbers 


