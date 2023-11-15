# Overview:

This project aims to classify images of dogs and cats using two different approaches: a normal Convolutional Neural Network (CNN) model and a fine-tuned VGG-16 module. The purpose is to compare the performance of these two models in distinguishing between images of dogs and cats.

# Table of Contents:

[Packages](#Packages)
[About the model]
[Dataset]
[Usage]

# Packages

Find it in -- (All of the packages are not important. But tensorflow is the preferred library in this project)

# About the model

*Model 1* : CNN model with Convolution and MaxPooling layers. The normal CNN model is a simple convolutional neural network with a few convolutional layers followed by fully connected layers. This model serves as a baseline for comparison with the fine-tuned VGG-16 model.

Check out more about [CNN models](https://datagen.tech/guides/computer-vision/cnn-convolutional-neural-network/) 

*Model 2* : The fine-tuned VGG-16 model uses the pre-trained VGG-16 architecture with additional training on our dataset. This transfer learning approach leverages the knowledge gained from training on a large dataset and adapts it to the specific task of dogs vs cats classification.

Check out more about [VGG 16 model](https://medium.com/@mygreatlearning/everything-you-need-to-know-about-vgg16-7315defb5918) and [transfer learning](https://machinelearningmastery.com/transfer-learning-for-deep-learning/)

Dataset: Download the dataset [here](https://www.kaggle.com/competitions/dogs-vs-cats/data?select=train.zip). Extract the zip file and arrange the directory structure or the code to make it work.

Usage: You can run the code locally. Data will be needed to download the VGG16 model and necessary libraries. The only additional that you need to do is to adjust directory structure of your dataset according to the code.

You can find more help [here](https://www.youtube.com/watch?v=qFJeN9V1ZsI)




