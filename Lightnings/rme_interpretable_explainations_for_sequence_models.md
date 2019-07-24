# RME: interpretable explainations for sequence models

Author: Mateusz Kobylka (MI2 DataLab)

# Description

Explainable Artificial Intelligence is evolving rapidly and many useful tools have been developed to investigate and expound decisions of complex machine learning models in the past few years, yet there are many fields where XAI is still in its infancy. 
In the lighting talk I would like to preview a novel method of explaining AI’s decisions that is dedicated to models working on sequential data. Recurrent Memory Explainer (RME) is a tool that focuses on the memory of sequential model and tries to explain the decision by pointing important places in the sequence that had an effect on the prediction. RME is based on so-called ,,memory profiles”, which are intuitive and can be easily visualised on simple plot charts. Thanks to the explanations produced by RME, it is possible to determine, for example, whether the more recent or past events had bigger influence on the final decision. 
The new method of explaining predictions will be presented on the example of medical data and LSTM-based model. The model tries to predict patient's next disease given their disease history, stored in a sequence. RME is able to show which diseases in the history, according to the model, had an impact on the final prediction and how big this impact was.
RME was created as a part of master thesis at Warsaw University of Technology, supervised by Przemyslaw Biecek. We would like to thank the LekSeek company for the access to anonymized data. 

