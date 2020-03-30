# Skoltech-ML-2020-AutoEncoder-by-Forest
Typically, autoencoders (AEs) are assotiated with Neural Networks. Yet in [the paper](https://arxiv.org/pdf/1709.09018.pdf) the authors propose to use Decision Tree for AE and claim that their approach has reasonable performance. Here we have reproduced the paper results: we have implemented AE forest algorithm and compared its performance with MLP &amp; CNN  AEs on image datasets (MNIST, CIFAR-10).

The code was written by:

- Egor Sevriugov - Tree ensemble based AE (MNIST, CIFAR-10, Omniglot), 
- Kirill Scherbakov - CNN based AE (MNIST, CIFAR-10, Omniglot), 
- Maria Begicheva - MLP based AE (MNIST, Omniglot),
- Olga Novitskaya - MLP based AE (CIFAR-10, Omniglot)

## Colab Notebook
- Tree ensemble based AE (MNIST, CIFAR-10, Omniglot): [Google Colab] () | [Code] ()
- CNN based AE (MNIST, CIFAR-10, Omniglot): [Google Colab] () | [Code] ()
- MLP based AE (MNIST, Omniglot): [Google Colab] () | [Code] ()
- MLP based AE (CIFAR-10, Omniglot): [Google Colab] () | [Code] ()

## Prerequisites
- Python 3
- Google Colaboratory service

## Datasets info
- MNIST and CIFAR-10 datasets were got from keras.datasets module
- Omniglot dataset was got from torchvision.datasets module. However, Egor has the different order of pictires in this dataset, and we saved our unified set of pictures for his experiments.

## Results

