This project is a partner project of mluetje and PsychOpilio. 

We chose a dataset from Lending Club (www.lendingclub.com), an American peer-to-peer lending company, headquartered in San Francisco, California.

The purpose of the project was to use machine learning models and insights from exploratory data analysis in order to help Lending CLub investors to decide whom to support with a loan. That is, the risk of losing money by supporting borrowers who will end up not paying back is to be minimized. The problem is treated as a binary classification problem (positive = borrower paying back, negative = borrower not paying back).

The main concern is to avoid approving somebody who won't be able to repay. Therefore, the main performance metric of our models is the F beta score combining both recall and precision, with a much greater weight on precision (since it is particularly heavy to classify a 'non-payer' as 'payer', i.e., false-positive). 

Since the data is imbalanced with regard to target variable class frequencies, we pay much attention to handling this imbalance. Also, the data needed much preprocessing. 

The project contains the following notebooks: 
* [01 Data Cleansing](01_Data_Cleansing.ipynb)
* [02 Exploratory Data Analysis](02_EDA.ipynb)
* [03 Modelling](03_Modelling_Train_Data.ipynb)
* [04 Model Evaluation](04_Model_Evaluation.ipynb)

Our best models are a random forest classifier and , surprisingly, a logistic regression model. In the latter, recall and accuracy scores were higher, so our final decision went for this model.

