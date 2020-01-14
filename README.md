# Image-Classification
Classification of Dogs and Cats from images collected of various dogs and cats


4000 images of cats and 4000 images of dogs of different geographies and different breeds were downloaded. 
The same was used to train a model to classify each image as a dog or cat.

The first model was developed by using 3 layers of convolution neural network followed by two dense layers. 
Each convolutional layer was followed by maxpooling which helped with reducing dimension while retaining the overal structure of outputs
from the conv layer. The output from the last layer of convolution was flattened before being fed to the Dense layer. 
Each dense layer was ofcourse associated with batch normalization and drop out to prevent overfitting.
To introduce non-linearity, RELU was used as the activation function across all hidden layers. Only last layer i.e. output layer
had sigmoid as the activation function since it is a binary classification.

The data can be imported from here : https://drive.google.com/drive/folders/19QG5iMoQOs0RbCuRqLLVacVyCMaAgyG2?usp=sharing
