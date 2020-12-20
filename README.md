# Machine-Learning-Projects
Beginner-level machine Learning projects in Phyton

### General Info
Machine learning is the study of computer algorithms that improve automatically through experience. It is seen as a subset of artificial intelligence.

Machine Learning approaches:
* Supervised Learning
  * Regression
    * Simple Linear Regression
    * Multiple Regression
    * Polynomial Regression
  * Classification
    * Logistic Regression
    * K-NN
    * SVM
    * Decision Tree Classification
    * Naive Bayes
    * Random Forest Classification
* Unsupervised Learning

Algrithms that are used in this repo are based on the approach mentioned above. Different groups have different datasets, but algorithms that belong to the same group use the same dataset (f.e. regression and classification don't have the same dataset, but simple linear regression and polynomial regression have). 
In that way, it's easier to understand which algorithm does the best prediction for our dataset.
Based on the results that was given by the *accuracy_score(X, y)* method, here are some conclusions for both Regression and Classification:

## Regression

Regression Model          | PROS                                                                            | CONS
------------------------- | ------------------------------------------------------------------------------- | --------------
Linear Regression         | Works on any size of the dataset, gives information about relevance of features | The Linear Regression Assumptions
Polynomial Regression     | Works on any size of the dataset, works very well on non-linear problems.       |Need to choose the right polynomial degree for a good bias/variance tradeoff        
