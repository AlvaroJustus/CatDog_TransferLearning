# Cat An dDog Transfer Learning Image Classifier - VGG16
![1](https://user-images.githubusercontent.com/37225643/91213669-502aba00-e6e8-11ea-8ede-64afa2112456.png)


The aim of this study is to apply Transfer Learning knowledgment using the classic classifier of dogs and cats (image classifier model)

## Dataset Download:

[Download here](https://www.kaggle.com/tongpython/cat-and-dog)

## What is Transfer Learning?

Transfer Learning means the use of knowledge and skills previously acquired in new situations of learning or problem solving. Thus, similarities and analogies between content and previous learning processes can play a crucial role. The transference phenomenon is presented within a general learning perspective.

## What was the approach of the topics?

* Transfer Learning
* Convolutional Neural Network (CNN)
* Imagenet
* Neural Networks Architecture
  * Layers
  * Inputs
  * Weights
* VGG16
* Save and Load trained Model
* Data Augmentation
* Keras
* Flask
* Tensorflow
* Computational Vision

## VGG16 Architecture

VGG16 was publised in 2014 and is one of the simplest (among the other cnn architectures used in Imagenet competition). It's Key Characteristics are:

* This network contains total 16 layers in which weights and bias parameters are learnt.
* A total of 13 convolutional layers are stacked one after the other and 3 dense layers for classification.
* The number of filters in the convolution layers follow an increasing pattern (similar to decoder architecture of autoencoder).
* The informative features are obtained by max pooling layers applied at different steps in the architecture.
* The dense layers comprises of 4096, 4096, and 1000 nodes each.
* The cons of this architecture are that it is slow to train and produces the model with very large size.

The VGG16 architecture is given below:

![4](https://user-images.githubusercontent.com/37225643/91336105-cb06da00-e7a7-11ea-9028-ad83abb304cd.png)

## Dataset example

![3](https://user-images.githubusercontent.com/37225643/91218015-d1854b00-e6ee-11ea-9ccb-8533879600c6.jpeg)
