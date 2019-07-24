# A Case Study for Image Classification using Transfer Learning

Author: Olgun AYDIN (Senior Data Scientist / PwC)

# Description

Deep Learning (DL) is rising star of Machine Learning (ML) and Artificial Intelligence (AI) domains and it has been proven that deep neural networks(DNN) are one of the most crucial inventions for the 21th century. Nowadays, DNNs are being used as a key technology for many different domains: self-driven vehicles, smart cities, security, automated machines. 
For the purpose of this use case, DNN has been trained by using images of products on the store shelves as input, product categories (cereals, milk, soda, etc.) as label . Transfer Learning(TL) has been used during to train such a deep neural network predicts product category regarding given image of product. For the training of the DNN, open source Freiburg Grocery Dataset has been used. The VGG16 network, developed by Oxford University researchers, has been used to perform TL. Due to the nature of TL, it is necessary to freeze some layers and retrain them with a new structure. For this purpose, only the final layer has been frozen first, then the last five layers have been frozen. These networks have been trained using different combinations of epoch and batch sizes. After comparing the performance of those networks, best performed model has been used for creating user interface. Shiny application has been created using to provide user interface to end users. This Shiny application basically calls the trained model and predicts product class for the image uploaded by the user. 

