# machine-learning
diagnostic and predictive models using  Scikit-learn
_________
In this notebook we try a few classification algorithmss to predict if loans will go into collections or will be paid off. 


We load a dataset using Pandas library, and apply the following algorithms, and find the best one for this specific dataset by accuracy evaluation methods.

1. K Nearest Neighbor(KNN)
K nearest neighbors is a simple algorithm that stores all available cases and classifies new cases based on a similarity measure (e.g., distance functions). 

2. Decision Tree
A decision tree is a flowchart-like structure in which each internal node represents a "test" on an attribute (e.g. whether a coin flip comes up heads or tails), each branch represents the outcome of the test, and each leaf node represents a class label (decision taken after computing all attributes)

3. Support Vector Machine
A Support Vector Machine (SVM) performs classification by finding the hyperplane that maximizes the margin between the two classes. The vectors (cases) that define the hyperplane are the support vectors.

4. Logistic regression 
Logistic regression is the appropriate regression analysis to conduct when the dependent variable is dichotomous (binary). ... Logistic regression is used to describe data and to explain the relationship between one dependent binary variable and one or more nominal, ordinal, interval or ratio-level independent variables.

_____
We will evaluate the models using 
1. Jaccard Index
The Jaccard Index, also known as the Jaccard similarity coefficient, is a statistic used in understanding the similarities between sample sets. The measurement emphasizes similarity between finite sample sets, and is formally defined as the size of the intersection divided by the size of the union of the sample sets.

2. F1-Score
F1 score - F1 Score is the weighted average of Precision and Recall. Therefore, this score takes both false positives and false negatives into account. Intuitively it is not as easy to understand as accuracy, but F1 is usually more useful than accuracy, especially if you have an uneven class distribution.
Precision= True_positive/(True_positive+False_positive)
or Precision= True_positive/Total predicted positive

Recall= True_positive( True_positive + False_negative
or Recall= True positive/total Actual_positive

F1= (Precision * Recall)/ (Precision+ Recall)
