# Decision_tree_from_scratch
## Wahat is decision tree ?
-> Decision Tree 
is a Supervised machine learning algorithm, that resembles flowchart structure, representing decisions and their potential consequences, used for classification and regression.

-  Each internal node represents a feature
-  Each branch represents a decision rule
-  Each leaf node represents the prediction

## How does it works?
-> The decision tree algorithm works by recursively partitioning the data based on the feature that best separates the classes or reduces the variance in the target variable. The goal is to create a tree that is able to make accurate predictions on unseen data.

## When did you use it?
- classification and regression
- feature selection
- gain insights into the relationships between variables in the dataset
- ensemble methods such as random forests and gradient boosting

## When stop repeating ?
- when entropy be equal zero
- you specify a maximum depth 
- information gain less than certain thtreeshold 
- when number of exambles in leaf node less than certain thtreeshold 
=> most  stopping points you put it

## Some Advantages 
- interpretable and easy to understand
- can capture nonlinear relationships between features and the target variable.
- handling both categorical and numerical data
- dentify the most important feature (inforamtion gain)

## Some Disadvantages 
- single dt can be highly sensitive to small changes in data so we using multiplt dt (Random forest) 
- Overfitting at situation of there is a noise or irrelevant patterns in training data









