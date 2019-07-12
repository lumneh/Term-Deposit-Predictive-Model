# Term-Deposit-Predictive-Model
Implementation of a machine learning algorithm to predict if a customer to a bank will subscribe to term deposit.

### Goal
The objective is to implement a classifier with a high accuracy that the bank can use to develop a more efficient campaign strategy that will guarantee the subscription of more customers to term deposit hence generating more profits for the bank while minimising the cost spent on the campaign.

### Dataset
1) The data is related with direct marketing campaigns of a bank. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed.
2) This data analytics project was carried out using a bank dataset of 15,111 non-duplicate instances with 16 attributes.
3) Of these attributes, 9 were categorical and the remaining 7 were numerical.
4) The target or class is the subscribed column which shows the outcome of the campaign with a ‘yes’ or ‘no’ hence, the predictor variable showing if a client subscribed for a term deposit or not.

### Method
Among the Support Vector Machine (SVM) and Neural Network (NN) machine learning algorithms require to implement the model,  SVM was chosen to build the classifier as shown in the code.

### Result
The accuracy score indicated a 96.9% accuracy which is viewed as a very good accuracy score. The accuracy is computed by comparing the predicted values to the actual test values
From the Classification report, the recall and precision all show a 97%.
