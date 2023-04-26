# Transfer-Learning

This project demonstrates how to use transfer learning with the VGG16 architecture to train a model for image classification. The code is written in Python and uses the Keras library with the TensorFlow backend.

## Code Overview

The transfer_learning_vgg16.ipynb notebook contains the following sections:

- Importing the required libraries
- Setting the image size and dataset paths
- Loading the pre-trained VGG16 model and freezing its layers
- Adding custom layers on top of the VGG16 model
- Compiling the model and specifying the loss function, optimizer, and metrics
- Data augmentation using ImageDataGenerator
- Training the model with fit_generator
- Plotting the loss and accuracy curves
