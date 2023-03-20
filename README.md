# Detecting_CreditCard_Fraud
This notebook looks into the use of ML algorithms to detect fraudulent credit card transactions from non-fraudulent transactions.  
 
 
The dataset is from [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud?select=creditcard.csv) and contains transactions made by European credit card holders from Sept 2013 that occurred over 2 days. There are 492 frauds out of 284,807 transactions making this dataset highly unbalanced. Because the positive fraud cases account for 0.172 of all transactions, different preprocessing techniques are investigated to mitigate the effects of the skewed nature of the dataset on the ML algorithms. Manual under sampling was be performed to account for the skewed nature of the dataset. 

Overall eight different machine learning algorithms were evaluated for their performance. The model's hyperparameters were then fine tuned using gridsearch to optimize performance. 