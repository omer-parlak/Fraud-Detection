# Fraud Detection
https://www.kaggle.com/c/ieee-fraud-detection


<p align="center">
  <img width="700" height="350" src="https://user-images.githubusercontent.com/99130519/157931029-b9408951-3413-4116-b8a0-cf6336047253.png">
</p>

## Business Problem

Can we predict the probability of an online transaction being fraudulent?



## Transaction Table
TransactionDT: timedelta from a given reference datetime (not an actual timestamp)

TransactionAMT: transaction payment amount in USD

ProductCD: product code, the product for each transaction

card1 - card6: payment card information, such as card type, card category, issue bank, country, etc.

addr: address

dist: distance

P_ and (R__) emaildomain: purchaser and recipient email domain

C1-C14: counting, such as how many addresses are found to be associated with the payment card, etc. The actual meaning is masked.

D1-D15: timedelta, such as days between previous transaction, etc.

M1-M9: match, such as names on card and address, etc.

Vxxx: Vesta engineered rich features, including ranking, counting, and other entity relations.


## Identity Table
Variables in this table are identity information – network connection information (IP, ISP, Proxy, etc) and digital signature (UA/browser/os/version, etc) associated with transactions.
They're collected by Vesta’s fraud protection system and digital security partners.
(The field names are masked and pairwise dictionary will not be provided for privacy protection and contract agreement)

id_01 - id_38

DeviceType

DeviceInfo

# Results

![Kaggle Final Submission Scores (1)](https://user-images.githubusercontent.com/99130519/157930708-feff97a9-6007-40d6-b3e2-8dbb8250e239.png)
