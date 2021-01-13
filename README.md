# Wisconsin-Breast-Cancer--Data-analysis
Data Analysis of the Wisconsin breast cancer dataset. Finding the best algorithm for model creation using Machine Learning and determining the accuracy using confusion matrix.

The project includes data collection, data cleaning, data manipulation using various visual aids like plots and matrices. Further, univariate and multivariate analysis 
was performed to get a clearer understanding of the data. EDA was done, followed by data interpretation. 
Various ML algorithms were then used to find the best one for predictions and accuracies of each was measured using confusion matrix. 

Multiple models were used to train the prepared dataset. The models used included:
1.	Random Forest Classification (81% accuracy)
2.	Univariate Feature selection using chi square test (78% accuracy)
3.	RFE with Cross validation 
4.	RFE- Recursive feature elimination using random forest classification
      It uses one of the classification methods (random forest in our example) to assign weights to all the features.
      Features having the least absolute weights are pruned from the original set of features. 
      This procedure is recursively repeated on the pruned set until the desired number of features are obtained.
5.	Tree based feature selection (61% accuracy) 
6.	L1 based feature selection (76% accuracy)
