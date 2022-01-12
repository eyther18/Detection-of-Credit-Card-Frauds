# Detection-of-Credit-Card-Frauds
The objective of the project is to detect all the fraudulent transactions while minimizing incorrect fraud classification using various machine-learning techniques.
Dataset: https://www.kaggle.com/mlg-ulb/creditcardfraud

The dataset contains only numerical input variables which are the result of a PCA transformation. Due to confidentiality issues, the original features and more background information about the data are not provided. Features V1, V2, ... V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.
