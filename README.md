# Detecting Potential Fraud Applications using SOM
For explanation on SOM, kindly refer to the file `Credit_card_fraud_customer_segmentation.ipynb`. Everything is described with references.

### Algorithm Used: 
Self Organising Maps (Unsupervised Learning)

### Code in:
Python 3

### Libraries: minisom package (<a href='https://pypi.org/project/SimpSOM'>Download from here</a>)

### Basis of Decision-making (fraud/non-fraud)

Fraudulent transactions are the outliers in the dataset, i.e., the attributes values do not follow the 'average normal' trend that fraudulent transactions follow.

Assuming null hypothesis to be true, outliers in the dataset will be marked as frauds. Further investigation would be required to possibly find examples that support the alternate hypothesis.

