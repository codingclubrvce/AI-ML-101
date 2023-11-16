### Dog vs Cat Classification Project 🐾📸


# Overview 🌟

This project focuses on the captivating task of classifying images of our furry friends – dogs 🐶 and cats 🐱. We explore two different approaches to achieve this: a conventional Convolutional Neural Network (CNN) model and a fine-tuned VGG-16 module. The ultimate goal is to compare the performance of these models in distinguishing between images of dogs and cats.

# Table of Contents📜:

[Packages](#Packages)

[About the model](#About-the-model)

[Dataset](#Dataset)

[Usage](#Usage)

# Packages 📦

Find it [here](https://github.com/codingclubrvce/AI-ML-101/blob/6fd8c4c61eb1cf64f5f2c3f0ab709db89e6ebb4d/Deep-Learning-Models/DogVsCat-classification/requirements.txt) (All of the packages are not important. But tensorflow is the preferred library in this project)

# About-the-model🤖

*Model 1* : Our baseline model employs a straightforward Convolutional Neural Network with convolution and max-pooling layers. It serves as a reference for comparison with the fine-tuned VGG-16 model.

Check out more about [CNN models](https://datagen.tech/guides/computer-vision/cnn-convolutional-neural-network/) 

*Model 2* : The second model utilizes the pre-trained VGG-16 architecture, fine-tuned on our dataset. This approach leverages transfer learning, adapting knowledge gained from a broad dataset to the specific task of dogs vs cats classification. 

Deep Dive on [VGG 16 model](https://medium.com/@mygreatlearning/everything-you-need-to-know-about-vgg16-7315defb5918) and [transfer learning](https://machinelearningmastery.com/transfer-learning-for-deep-learning/)

# Dataset

Download the dataset [here](https://www.kaggle.com/competitions/dogs-vs-cats/data?select=train.zip). Extract the zip file and arrange the directory structure or the code to make it work.

# Usage🚀 

You can run the code locally. Data will be needed to download the VGG16 model and necessary libraries. The only additional that you need to do is to adjust directory structure of your dataset according to the code.

You can find more help [here](https://www.youtube.com/watch?v=qFJeN9V1ZsI)




