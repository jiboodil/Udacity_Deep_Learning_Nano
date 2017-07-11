# Image Classification

## Overview

In this project, I use TensorFlow to build a deep Convolutional Neural Network (CNN) to classify images of 10 objects (airplanes, dogs, cats etc.) from CIFAR-10 dataset. I implemented key CNN elements including two convolutional layers with max pooling, and two fully connected layer with drop out to combat over-fitting. 

## Result
With some fine-tuning of the hyper-parameters, the model reaches 56% testing accuracy, whereas random guessing only yielded about 10%

## Further Work
The model can be further improved with batch normalization, momentum methods or regularization, and can be used as a basis for transfer learning on other classfication problems.
