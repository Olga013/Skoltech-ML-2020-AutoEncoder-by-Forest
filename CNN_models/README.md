# Instructions

## Prerequisites

- Python 3
- Google Colaboratory service
- PyTorch 1.4.0, Tensorflow 2.1.0, Keras 2.3.0

## Datasets info

- MNIST and CIFAR-10 datasets were got from keras.datasets module:  [MNIST dataset](https://keras.io/datasets/#mnist-database-of-handwritten-digits) | [CIFAR-10 dataset](https://keras.io/datasets/#cifar10-small-image-classification)
- Omniglot dataset was got from torchvision.datasets module: [Omniglot dataset](https://github.com/pytorch/vision/blob/master/torchvision/datasets/omniglot.py)


## How to launch the code?

- Firstly, you should open the corresponding notebook in [Google Colaboratory service](https://colab.research.google.com/)

- In each notebook the code is arranged in a sequential way. In order to reproduce the corresponding results, you need to open a notebook in Google colab (preferably using GPU runtime) and run each cell of the code sequentially, then wait for the result to run.

- The following training parameters are available for modification: the number of epochs ("epochs"), the loss criterion ("criterion"), the optimizer algorithm during training mode ("optimizer") and the learning rate scheduler ("scheduler"). 
