# RUcausal: An R package for Representing Uncertainty in causal discovery

Author: Ioan Gabriel Bucur (Radboud University Nijmegen)

Co-authors: Tom Claassen, Tom Heskes

# Descripition

Causal discovery is a fundamental problem in scientific research. Understanding the causal links between a set of observed variables is crucial for predicting the effects of interventions and policies. RUcausal is an R package intended to provide robust methods for deriving causal relations from observational data. It contains an efficient implementation of the state-of-the-art 'Bayesian Constraint-Based Causal Discovery' (BCCD) algorithm, which takes as input the data correlation matrix and outputs a single partial ancestral graph (PAG) representing the class of all possible causal graphs over the measured variables, along with estimates for the reliability of each inferred causal relation. RUcausal includes an interface for specifying relevant background knowledge regarding the structure of the graph (e.g., forbid an edge between two variables) or regarding the causal relations between variables (e.g., a variable like gender cannot be causally influenced by other variables in the system). Furthermore, the package provides a routine for generating multivariate Gaussian data from specified causal models and a routine for visualizing the output PAG, which uses the plotting library Rgraphviz. 

