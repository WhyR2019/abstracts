# Facial landmarking made (possible and) easy with R!

Author: Lubomir Stepanek (Institute of Biophysics and Informatics, First Faculty of Medicine, Charles University)

# Descripition

R language is definitely a powerful tool well suitable for most analytical tasks arising from an everyday routine of a scientist or data analyst. However, there are fields of data processing which R is not so much native for and other languages or tools such as Python or Octave are preferred to handle them. Some of these fields are image processing and computer vision and particularly facial computer where there are barely original R packages currently available for.

There are of course approaches how to handle missing libraries in R. In general, an API library could bridge the gap between R on the one hand and the special tool (usually built in a different programming language) on the other hand. In this work, we tried to rethink the problem and go even further such that we have developed a web-based shiny application providing facial image processing and especially facial landmarking. The facial landmarking is powered using C++ library dlib dedicated to machine-learning based computer vision algorithms, but only for C++ speaking users.

The connection between R, C++ dlib and R package shiny could open R functionality and computing power to a wider audience using comfortable and clickable way.
 

