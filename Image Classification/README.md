## Problem Statement
The problem I am going to solve in this project is: classify an image among the 100 lower level classes, defined by [The CIFAR-100 dataset](Learning Multiple Layers of Features from Tiny Images, Alex Krizhevsky, 2009.). So this is a multi class classification problem.
The input would be a image with a minimum dimension of 100px by 100px.

## Dataset and Inputs
I am going to use the CIFAR-100 dataset. This dataset is publicly available at the [University of Toronto website](https://www.cs.toronto.edu/~kriz/cifar.html). It is comprised by 6000 small images correctly labeled with one of 100 available classes.
The CIFAR dataset is a subset of the [80 million tiny dataset](http://groups.csail.mit.edu/vision/TinyImages/), and all the images have a 32x32 dimension. Those are quite small images, but I don't believe this would be an issue while training the model.
The input images will have variable dimensions, the only constraint being that the image should be at least 32x32 in dimensions.

## Dependencies

The following packages are nedeed to run this project:

- keras, tensorflow, scikit-learn, cv2, numpy

## Training the classifiers
There are 2 classifiers in this project. The main one is a CNN classifier developed with Keras. There is also a SVM classifier built with Scikit-learn that is used to compare results for benchmark reasons

## Predictions
There are iPython Notebooks that can be used to run predictions for the CNN and SVM classifiers. They are:

- Prediction CNN.ipynb
- Prediction SVM.ipynb
