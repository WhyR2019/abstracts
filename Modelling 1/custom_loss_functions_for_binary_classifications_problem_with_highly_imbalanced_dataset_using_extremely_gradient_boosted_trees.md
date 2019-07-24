# Custom loss functions for binary classifications problem with highly imbalanced dataset using Extremely Gradient Boosted Trees

Author: Bartosz Kolasa (DataWalk SA)

Co-authors: Patryk Wielopolski

# Description

One of the most common approaches used in binary classification problem is building a model using Extremely Gradient Boosted Trees algorithm that utilizes cross-entropy as a loss function. Unfortunately in context of highly imbalanced dataset this approach is underperforming. While this function is insensitive to the identity of the assigned class in the case of misclassification, in practice it is a very common situation to have skewed  sensitivity to error, meaning wrong assignments for one class are much worse than for other. 
During our talk we would like to present results of experiment where we tested different custom loss function using Extremely Gradient Boosted Trees algorithms for real world application where cost of misclassification error was highly asymmetrical and how to implement such solution in R. 

