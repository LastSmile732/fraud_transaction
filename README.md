# fraud_transaction
Taiwan AI Academy Midterm Competition 1

https://www.kaggle.com/c/taiwan-aia-financefraud

Data Fields:
step - The number represents the time in reality, 1 is 1 hour, a total of 744 (30 days of data).

type - CASH-IN: save money, CASH-OUT: withdrawal, DEBIT: pay, PAYMENT: payment, TRANSFER: transfer

amount - The amount of the transaction, in local currency

nameOrig - The customer who started the transfer

oldbalanceOrg - initial balance before transaction

newbalanceOrig - new balance after transaction

nameDest - the transfer object

oldbalanceDest - the transfer object, the initial balance before the transaction, does not include people who starts with M

newbalanceDest - the transfer object, the new balance after the transaction, does not include people who start with M

Fraud - the goal of this exercise, to predict whether this transaction is a fraud.

Data Set:
https://www.kaggle.com/c/taiwan-aia-financefraud/data
