# AmyloGram: the R package and a Shiny server for amyloid prediction

Author: Jaroslaw Chilimoniuk (University of Wroclaw)

Co-authors: Michal Burdukiewicz, Piotr Sobczyk, Stefan Rödiger, Malgorzata Kotulska and Pawel Mackiewicz

# Description

Amyloids are proteins associated with important clinical disorders (e.g., Alzheimer's or Creutzfeldt-Jakob"s diseases). Despite their great diversity, all amyloid proteins can undergo their aggregation initiated by 6- to 15-residue segments. The structure and the function of proteins are encoded in the linear sequence of amino acids. But the aggregation propensity seems to not depend on the exact amino acid residues, but rather on their physicochemical properties. Therefore, we created a model of amyloidogenicity incorporating this knowledge.

We have created 524,284 reduced amino acid alphabets based on diversified combinations of the physicochemical properties of amino acid residues. Using a very fast implementation of the random forest classifier from the ranger package we cross-validated all reduced alphabets and identified one that provided the best discrimination between amyloids and non-amyloids. Our feature selection method found 65 motifs that are the most relevant to the discrimination of amyloid and non-amyloid sequences.

Our toolkit, the biogram R package, provides a set of useful tools for encoding protein sequences into features understandable by machine learning algorithms. Our software, inspired by natural language processing, extracts n-grams of amino acids from proteins and selects only the most informative ones using developed by us Quick Permutation Test (QuiPT).

The reduction of amino acid alphabet turned out very efficient. Most of the predictors based on them outperformed those trained on the full amino acid alphabet. Among 65 most informative amino acid motifs identified during the analysis, 15 were independently confirmed in experimental studies. AmyloGram effectively recognizes patterns responsible for the aggregation (AUC = 0.90, Matthews correlation coefficient: 0.63) outperforming existing amyloid-predicting software. 

AmyloGram was further used to predict the properties of amyloid sequences from the AmyLoad database. We analyzed 23 peptides and validated experimentally using ThT assay. 15 out of 23 peptides had the same amyloid properties as predicted by AmyloGram. Moreover, predictions of AmyloGram were verified experimentally as our tool led to the discovery of a novel amyloid protein, MspA, produced by Methanospirillum hungatei JF-1.

Our analysis not only confirmed that amyloidogenicity depends on the general physicochemical properties of proteins but also revealed which features are the most relevant to the initiation of amyloid aggregation. 

Despite large computational requirements, the whole study was conducted in R, mostly using functions from packages biogram and ranger. AmyloGram itself is distributed as the R package and a shiny web-server at: www.smorfland.uni.wroc.pl/shiny/AmyloGram/. 

