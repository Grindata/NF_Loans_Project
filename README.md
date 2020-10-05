For this project we chose a dataset from Lending Club approved personal loans between 2007 and 2011. The data can be found on www.lendingclub.com. The purpose of the analysis is to reduce defaults, improve profitability and help the company and investors determine interest rates. We will use machine learning models to analyze credit risk as a binary classification problem.

How to choose the Performance metrics? - well the model (whichever you pick) will be used to determine who should be approved for a loan and who shouldn’t, denying the loan to a client who will end up paying in full (false positives) represents a loss, but because interest is usually only a portion of principal the company will most likely be more comfortable not taking the chance when the risk is not to get reimbursed at all and lose the entire principal which represents a higher amount. Thus the main concern here is to avoid approving somebody who won't be able to repay or in other words avoid false negatives. This is achieved by a model with a high recall rate. 
What would be the right performance metric- precision, recall, accuracy, F1 score, or something else?

We also might need to evaluate TPR to make sure we are not declined too many qualified borrowers.


Make sure to check data imbalance. 
