# Detecting topics in civil service job offers using Latent Dirichlet Allocation model

Author: Adam Bień (SKN Estymator (Poznan University of Economics and Business))

Co-authors: Maciej Beresewicz

# Description

The main goal of this presentation is an application of Latent Dirichlet Allocation model (LDA) on data scraped from Chancellery of the Prime Minister’s official website (https://nabory.kprm.gov.pl), containing characteristics concerning each job offer published on mentioned page. The LDA model’s purpose is to determine what topics the job offers’ descriptions consist of and use that information to approximate demand on the labour market.

All information about valid and archived job offers had been retrieved with the “rvest” package. Next the dataset was tidied, the descriptions’ words split up, stop words removed, and finally the words transformed to respective stems using packages “tidyverse”, “lubridate”, “tidytext”, “stringi”.  The modified data was then used in creating the LDA model with “topicmodels” package, which was able to distinguish different topics brought up in descriptions. The topics generated via the model were then adequately labelled and the demand approximated by summing probabilities of affiliation for every job offer to each topic.
