# AmyloGram 2.0: MBO in the prediction of amyloid proteins

Author: Dominik Rafacz (Warsaw University of Technology)

Co-authors: Stefan Rodiger, Malgorzata Kotulska, Michal Burdukiewicz

# Description

Background: Amyloids are self-aggregating proteins commonly associated with neurodegenerative disorders (for example Alzheimer’s, Parkinson’s or Creutzfeld-Jakob diseases). The in silico identification of amyloids is challenging because their amino acid composition can be extremely variable. Recently, we were able to identify motifs occurring in amyloid sequences and create a machine learning tool, AmyloGram [1], which has outperformed other predictors of amyloids.
Methods: To improve our tool we trained the AmyloGram 2.0 using a model-based optimization framework (MBO) [2]. MBO allows finer tuning of model hyperparameters, including the length of used n-grams and the minimal level of the n-gram informativeness
Results and discussion: Thanks to the usage of MBO, on the pep424 dataset AmyloGram 2.0 reached AUC 0.91. Moreover, the new version of AmyloGram is able to detect aggregation-prone regions in proteins. Our tool is available as the R package (https://CRAN.R-project.org/package=AmyloGram) and the web server (http://www.smorfland.uni.wroc.pl/shiny/AmyloGram/).

[1] Burdukiewicz, M., Sobczyk, P., Rodiger, S., Duda-Madej, A., Mackiewicz, P., and Kotulska, M. (2017). Amyloidogenic motifs revealed by n-gram analysis. Scientific Reports 7, 12961.

[2] Bischl, B., Richter, J., Bossek, J., Horn, D., Thomas, J., and Lang, M. (2017). mlrMBO: A Modular Framework for Model-Based Optimization of Expensive Black-Box Functions. ArXiv:1703.03373 [Stat].

