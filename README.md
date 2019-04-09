# Fashion-MNIST 

## Getting Started

![](https://cdn-images-1.medium.com/max/1200/1*p2jvmf8sLET5V70nzZsAYg.png)

## Installing
This is an implementation in Keras, so we need to have Python 3.6 and the below libraries:

- [numpy]
- [Tensorflow]
- [Keras]
- [matplotlib]

## Description

This dataset contains 70,000 grayscale images  of size 28 X 28, in 10 categories:

0: 'T - shirt / top',
1: 'Trouser',
2: 'Pullover',
3: 'Dress',
4: 'Coat',
5: 'Sandal',
6: 'Shirt',
7: 'Sneaker',
8: 'Bag',
9: 'Ankleboot'

## Models

We train a Multilayer Perceptron (MLP) and a Convolutional Neural Network (CNN) to perform above classification task.
We train both models for many epochs and we use an early stopping. We also use Drop out to avoid overfitting.


[fashion mnist dataset]: <https://research.zalando.com/welcome/mission/research-projects/fashion-mnist/>
[Tensorflow]: <https://www.tensorflow.org/install>
[Keras]: <https://keras.io>
[matplotlib]: <https://matplotlib.org>
[numpy]: <http://www.numpy.org>
