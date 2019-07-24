# PepBay: Implementation of Bayesian inference in the analysis of peptide arrays

Author: Katarzyna Sidorczuk (University of Wroclaw)

Co-authors: Andreas Weinhäusel, Michal Burdukiewicz

# Description

Biomarkers are biological features measurable in biological media, such as human tissues or fluids, that may be indicators of a health state or presence of a disease. To this date, a wide variety of biomarkers in the form of proteins have been identified and routinely used for clinical diagnoses of many diseases, including cancers. The search for new biomarkers may be facilitated by the use of peptide arrays, collections of short protein fragments displayed on a solid surface, as they allow testing thousands of peptides simultaneously.

However, analysis of the data derived from peptide arrays is challenging because of the 'large p small n' problem. It is a common issue in medical studies, where the availability of patients is limited and the number of available covariates is significantly larger than the sample size. Traditional methods fail in such cases, as the correction for multiple testing results in very high p-values. In consequence, it is difficult to distinguish significant effects from noise. 

To address these problems, we propose a novel Bayesian approach that utilizes similarities between peptides to better find their associations with the health condition of patients. In addition to its accuracy, our approach also eliminates bias-inducing data pre-processing. To perform Bayesian modeling, we used the R package BEST based on JAGS. In contrast to frequentist methods, it provides a widespread value distribution over, e.g., the effect size that is more interpretable than p-values. Our approach will be implemented in the application PepBay, a tool to facilitate analysis of the results derived from peptide arrays.
 

