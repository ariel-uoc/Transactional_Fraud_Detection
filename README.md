# Transactional_Fraud_Detection
This is a machine learning project that uses a synthetic dataset of mobile money transactions for fraud detection.  
The dataset contains 2 classes: frauds and valid transactions, and frauds only account for 0.13% of the data. Due to the significant class imbalance, resampling
was performed where necessary and the evaluation metrics chosen were the recall of frauds (more emphasis) and the precision of non-frauds. 
Outlier detection algorithms were used, including local outlier factor, isolation forest and cost-sensitive logistic regression. 
Other machine learning models were built, including XGBoost, Multilayer Perceptron and Autoencoder. 
