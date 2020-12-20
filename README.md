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

Algrithms that are used here are based on the approach mentioned above. Different groups have different datasets, but algorithms that belong to the same group use the same dataset (f.e. regression and classification don't have the same dataset, but simple linear regression and polynomial regression have). 
In that way, it's easier to understand which algorithm does the best prediction for our dataset.
Based on the results that was given by the *accuracy_score(X, y)* method, here are some conclusions for both Regression and Classification:

## Regression

Regression Model          | PROS                                                                            | CONS
------------------------- | ------------------------------------------------------------------------------- | --------------
Linear Regression         | Works on any size of the dataset, gives information about relevance of features | The Linear Regression Assumptions
Polynomial Regression     | Works on any size of the dataset, works very well on non-linear problems.       |Need to choose the right polynomial degree for a good bias/variance tradeoff




## Classification
Classification Model      | PROS                                                                                  | CONS
------------------------- | ------------------------------------------------------------------------------------- | --------------
Logistic Regression       | Probabilistic approach, gives informations about statistical significance of features | The Logistic Regression Assumptions
K-NN                      | Simple to understand, fast and efficient                                              | Need to choose the number of neighbors K
SVM                       | Performant, not biased by outliers, not sensitive to overfitting                      | Not appropriate for non linear problems, not the best choice for large number of features
Kernel SVM                | High performance on nonlinear problems, not biased by outliers, not sensitive to overfitting | Not the best choice for large number of features, more complex
Naive Bayes               | Efficient, not biased by outliers, works on nonlinear problems, probabilistic approach | Based on the assumption that features have same statistical relevance.
Decision Tree Classification              | Interpretability, no need for feature scaling, works on both linear / nonlinear problems | Poor results on too small datasets, overfitting can easily occur
Random Forest Classification              | Powerful and accurate, good performance on many problems, including non linear | No interpretability, overfitting can easily occur, need to choose the number of trees
                                                                                                             


