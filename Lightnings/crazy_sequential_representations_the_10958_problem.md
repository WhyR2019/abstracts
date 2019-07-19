# Crazy Sequential Representations - The 10958 Problem 

Author: Anne Bras (Erasmus University, the Netherlands)

Co-authors: Vincent van der Velden 

# Descripition

Inder Taneja (an Indian mathematician) attempted to write the integers from 1 up to 11111 in terms of 1 to 9 (in increasing and decreasing order) by using addition, subtraction, multiplication, division, exponentiation, parenthesis and/or digit concatenation. For example:

    9617 = 1+2^3*(45+(6+7)*89) = 9*876+5+(4*3)^(2+1) 
    9618 = 1*(2+3+4+5)*(678+9) = (9+8+7*(6+54+3))*21 
    9619 = 1+(2+3+4+5)*(678+9) = 9*87+(6*5+4^3)^2/1 

These representations are generally referred to as crazy sequential representations (CSR). Interestingly, within the 1 up to 11111 range, only one CSR remains to be identified, namely the increasing CSR for 10958.

Pure brute force approaches to "the 10958 problem" are unfeasible, as billions of lexicographical unique expressions can be generated. However, various techniques can be used to reduce the number of candidate expressions, as was done in this project.

Efficient algorithms (generalizing the concept of CSR to arbitrary bases) were designed and implemented from scratch. Millions of CSR were identified (for the integers from -2147483647 up to 2147483647, in base 3 up to 62). Given the nature of CSR, one might consider CSR to be proof-of-work, as identification is complex, while verification is trivial. 
