Convolutional Neural Network

- CNN's are used to perform image classification and then proceeds to decide an outcome based on the information given
- Different than a regular Neural Network



Convolution:

A 3x3 filter has been used
   - Need to import numpy as np
       - Download in CMD, pip install numpy
       - pip show numpy, to observe if the environment is installed on your CPU

- In the conv.py file a Class is created to store objects within it contains several functions
- Conv3x3 takes in one argument which is the number of filters and then uses Numpy's built in np.random.randn function
  to generate random numbers freely
- Numbers are divided by 9 to assure that they do not get too large and cause errors later on

- iterate_regions() = assisting method which halts all 3x3 images and can be used to implement more backend events later on
- Several different built in functions are used to make the process easier for the user to observe and operate


  Moving Forward...

  - mnist is downloaded on your CPU
  - pip install mnist
  - This continues as a part of the convolution process
 
Pooling:

A MaxCool class file with a MaxPool2 class is implemented and works relatively similar to Conv3x3 but here the max is found 

np.amax() = Our primary max method 

General Statements:

Includes (Conv layers, Pooling layers, Softmax layers):

All are able to combine and operate to produce a CNN

This is a watered down version of what CNN's are truly able to  do.
