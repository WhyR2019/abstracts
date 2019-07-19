# autobiograML: towards automated machine learning in protein function prediction

Author: Dominik Rafacz (Warsaw University of Technology)

Co-authors: Katarzyna Sidorczuk, Stefan Rodiger, Przemyslaw Gagat, Michal Burdukiewicz

# Descripition

Background: The advancements in various 'omics' fields have resulted in the discovery of many new protein sequences. Their functional annotations, however, come in at a much slower pace because they require laborious and often expensive experimental procedures. The machine learning models fill in this gap by providing estimates of protein functions. Although they do not replace the experiments, the in silico methods undoubtedly help scientists to understand the ever-growing protein datasets. The challenges of developing appropriate models for protein data exclude from the field scientists with limited machine learning expertise and resources. Therefore, we propose autobiograML, an R package designed to automatically apply our framework for protein function prediction [1, 2]. 
Methods: autobiograML models the relationships between provided protein sequences (encoded as amino acid motifs) and annotations. The Bayesian framework optimizes the hyperparameters of the model in nested cross-validation. The outer layer of the cross-validation is later used to select the optimal machine learning algorithm. Our software produces not only a model but also a list of important motifs for further studies. Moreover, autobiograML generates Shiny web servers that might be later distributed between less R-savvy users.
Results and discussion: Although autobiograML does not cover all the intricacies of machine learning, it offers a reliable way to create a model for the prediction of protein function. Our tool will be a valuable machine learning assistant for many research groups studying areas that are too new to have already well-established computational methods.

[1] Burdukiewicz, M., Sobczyk, P., Rodiger, S., Duda-Madej, A., Mackiewicz, P., and Kotulska, M. (2017). Amyloidogenic motifs revealed by n-gram analysis. Scientific Reports 7, 12961.

[2] Burdukiewicz, M., Sobczyk, P., Chilimoniuk, J., Gagat, P., and Mackiewicz, P. (2018). Prediction of Signal Peptides in Proteins from Malaria Parasites. International Journal of Molecular Sciences 19, 3709. 

