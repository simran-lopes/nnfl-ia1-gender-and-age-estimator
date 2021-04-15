# Gender-Recognition-and-Age-Estimator using CNN

# Introduction‭ ‭ ‬‬
Face  detection,  recognition ‭ ‬and  gender ‭ ‬estimation have  significant  values  in  multiple  sectors  in ‭ ‬real  life application and study as well. In real life, Face detection, recognition  and gender  
estimation ‭ ‬are  used ‭ ‬in  multiple 
sectors ‭ ‬like ‭ ‬security, ‭ ‬conference, ‭ ‬for ‭ ‬surveillance, ‭ ‬to identify a particular human, to recognize the persons face 
etc. 

![IMG_5106](https://user-images.githubusercontent.com/67309506/114904566-ab005580-9e20-11eb-97b9-11efcd280b9a.jpg)


# Abstract
Face detection, ‭ ‬recognition and ‭ ‬gender ‭ ‬estimation are one ‭ ‬of ‭ ‬the ‬
most ‭ ‬significant research ‭ ‬areas ‭ ‬in  computer ‭ ‬vision, ‭ ‬not ‭ ‬only ‭ ‬because ‭ ‬of ‭ ‬the challenging ‭ ‬nature ‭ ‬of  faces ‭ ‬as  an ‭ ‬object ‭ ‬but ‭ ‬also  due ‭ ‬to ‭ ‬the ‭ ‬countless 
applications  that ‭ ‬require ‭ ‬the ‭ ‬application ‭ ‬of ‭ ‬face ‭ ‬detection, ‭ ‬tracking ‭ ‬and 
recognition.

# What is a CNN?
A Convolutional Neural Network is a deep neural network (DNN) widely used for the purposes of image recognition and processing and NLP. Also known as a ConvNet, a CNN has input and output layers, and multiple hidden layers, many of which are convolutional. In a way, CNNs are regularized multilayer perceptrons.


# Project description 
Face and gender detection using keras and tensorflow
We have a pertained model which is haarcascade_frontalfac and weights.18-4.06.hdf5( which could not be uploaded since its size is 186mb larger than 25mb which is allowed in github) this pretrained model has been trained on more than 10,000 images so it will easily be able to classify images based on gender and age. 
We use resnet neural network and opencv.
In this code we first give the path for haarcascade_frontalface_alt which is present in our pertained model.
We used classes to create different functions.
we first call the main() function  which then calls the def main() which calls various functions including the facecv() method as soon as facecv() method is called it picks up the haarcascade_frontalface_alt and weights.18-4.06.hdf5
after that we call the def init where we will load all the weights of the neural network and the neural network code that is the wide_resnet.py which is a 2 layer convolutional neural network in which we use batch normalization and averagepooling method not maxpooling or minpooling
which helps us to give a good result
