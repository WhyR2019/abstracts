# *tfprobably* correct - adding uncertainty to deep learning with TensorFlow Probability

Author: Sigrid Keydana (RStudio)

# Description

In deep learning, it's the numbers that count - mean squared error, accuracy, F2 score, IOU and what not (possibly, or hopefully, in relation to training time and hardware resources). These metrics are commonly obtained for point estimates, like a numeric or a class prediction. In real life though, as they say, "nothing is certain besides death and taxes". Luckily, we can obtain uncertainty estimates from deep neural networks with tfprobability, the R interface to TensorFlow Probability: tfprobability provides distribution layers that are used seemlessly in a Keras network. Beyond deep learning, it lets you build complex hierarchical models, to be fitted with MCMC or variational inference. As expected, TensorFlow Probability being built on top of TensorFlow, we profit from GPU and distributed training. This talk gives an overview of tfprobability, its features and applications, and shows how you can add back uncertainty where it belongs.

# Bio

Sigrid is an Applied Researcher at RStudio. She has experience as a psychologist, software developer and data scientist. She is passionate about exploring the frontiers of deep learning and especially helping users employ the power of deep learning from R.
