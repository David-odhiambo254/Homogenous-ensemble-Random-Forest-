# Homogenous-ensemble-Random-Forest-
This repo demonstrates a Homogenous ensemble method (Random forest) using a bank churn modeling dataset. The various libraries used include pandas to read
the file, numpy and seaborn. The dataset is first loaded and checked for missing values. No null values are found in this case. The dataset is preprocessed 
by removing unwanted columns. In this case, that is  'RowNumber', 'CustomerId', and 'Surname' in the churn modeling dataset, because they play no significant
role in the analysis of the data. 

The data is taken through feature engineering by transforming categorical data into numerical data using One hot encoding. Data is split into test and 
training sets under the 0.2 test fraction. A homogenous ensemble random forest classifier is created and its accuracy score is checked, this can be repeated
many times with different numbers of trees and gini criteria. The accuracy increases with more number of trees and gini criteria. 

Feel free to star this repo, if you find it insightful and I am looking forward to your contribution.
