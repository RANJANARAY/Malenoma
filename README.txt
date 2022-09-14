Melanoma Detection via Convolutional Neural Network (CNN)
The objective of this project is to create a Convolutional Neural Network (CNN) to classify a dermoscopic image of a skin lesion as Melanoma or Non-Melanoma. A dermoscopic image is a picture of the skin using a microscope and illumination.
Motivation
Melanoma is the deadliest and most aggressive form of skin cancer.
Built With
TensorFlow
Keras
Python
Models
Two CNN architectures were explored for this project:
Simple CNN built from scratch with Keras, TensorFlow, and Python.
Deep (AlexNet-based) CNN built with MATLAB's Deep Learning Toolbox. Final 3 layers (Fully Connected, Softmax, and Classification Output) are adapted to my dataset.
The block diagram of the Keras model may be seen below.

Data
Neural Networks are a form of supervised learning, so training, testing, and validation data is required. This dataset has been acquired from sources (ISIC)
MelanomaNon-MelanomaTrain751754Test214215Validation106108Total1,0711,077Results
Keras CNN
Accuracy78.8Sensitivity69.2Specificity88.3
 


Future Work
I plan to improve this accuracy .I also plan to integrate this model into a website or app so that users may upload an image and get detection result. 

## Technologies Used
Library like numpy,pandas,seaborn,matplotlib,tensorflow is used
Programming with python


## Contact
Created by [@RANJANARAY] - feel free to contact me!
