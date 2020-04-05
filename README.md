# Skoltech-ML-2020-AutoEncoder-by-Forest
Typically, autoencoders (AEs) are assotiated with Neural Networks. Yet in [the paper](https://arxiv.org/pdf/1709.09018.pdf) the authors propose to use Decision Tree for AE and claim that their approach has reasonable performance. Here we have reproduced the paper results: we have implemented AE forest algorithm and compared its performance with MLP &amp; CNN  AEs on image datasets (MNIST, CIFAR-10, Omniglot).

![](https://github.com/Olga013/Skoltech-ML-2020-AutoEncoder-by-Forest/blob/master/images/autoencoder.png)

The code was written by:

- Egor Sevriugov - Tree ensemble based AE (MNIST, CIFAR-10, Omniglot), 
- Kirill Shcherbakov - CNN based AE (MNIST, CIFAR-10, Omniglot), 
- Maria Begicheva - MLP based AE (MNIST, Omniglot),
- Olga Novitskaya - MLP based AE (CIFAR-10, Omniglot)

**AEbyForest: [Project](https://github.com/Olga013/Skoltech-ML-2020-AutoEncoder-by-Forest) | [Paper](https://arxiv.org/pdf/1709.09018.pdf) | [Report](https://www.overleaf.com/project/5e7cb16864f7d40001746376) | [Presentation](https://www.overleaf.com/project/5e8205f195665c0001cc66b7) | [Video]()**

Train MNIST/Test MNIST
![](https://github.com/Olga013/Skoltech-ML-2020-AutoEncoder-by-Forest/blob/master/images/Merged_MNIST.png)

Train CIFAR10/Test CIFAR10
![](https://github.com/Olga013/Skoltech-ML-2020-AutoEncoder-by-Forest/blob/master/images/Merged_CIFAR10.png)


## Colab Notebook
- Tree ensemble based AE (MNIST, CIFAR-10, Omniglot): [Google Colab](https://colab.research.google.com/github/Olga013/Skoltech-ML-2020-AutoEncoder-by-Forest/blob/master/eForest_models/eForest_ml%20.ipynb) | [Code](https://github.com/Olga013/Skoltech-ML-2020-AutoEncoder-by-Forest/tree/master/eForest_models)
- CNN based AE (MNIST, CIFAR-10, Omniglot): [Google Colab](https://colab.research.google.com/github/Olga013/Skoltech-ML-2020-AutoEncoder-by-Forest/blob/master/CNN_models/CNNs_models.ipynb) | [Code](https://github.com/Olga013/Skoltech-ML-2020-AutoEncoder-by-Forest/tree/master/CNN_models)
- MLP based AE (MNIST, Omniglot): [Google Colab](https://colab.research.google.com/github/Olga013/Skoltech-ML-2020-AutoEncoder-by-Forest/blob/master/MLP_models/MLP_MNIST.ipynb) | [Code](https://github.com/Olga013/Skoltech-ML-2020-AutoEncoder-by-Forest/blob/master/MLP_models/MLP_MNIST.ipynb)
- MLP based AE (CIFAR-10, Omniglot): [Google Colab](https://colab.research.google.com/github/Olga013/Skoltech-ML-2020-AutoEncoder-by-Forest/blob/master/MLP_models/MLP_CIFAR_10.ipynb) | [Code](https://github.com/Olga013/Skoltech-ML-2020-AutoEncoder-by-Forest/blob/master/MLP_models/MLP_CIFAR_10.ipynb)

## Prerequisites
- Python 3
- Google Colaboratory service

## Datasets info
- MNIST and CIFAR-10 datasets were got from keras.datasets module:  [MNIST dataset](https://keras.io/datasets/#mnist-database-of-handwritten-digits) | [CIFAR-10 dataset](https://keras.io/datasets/#cifar10-small-image-classification)
- Omniglot dataset was got from torchvision.datasets module: [Omniglot dataset](https://github.com/pytorch/vision/blob/master/torchvision/datasets/omniglot.py)

## Results


## Related Projects

- The official implementation for the paper "AutoEncoder by Forest" by Ji Feng and Zhi-Hua Zhou 2017:  [Paper](https://arxiv.org/pdf/1709.09018.pdf) | [Code](https://github.com/kingfengji/eForest)
- Non-official implementation of the paper "AutoEncoder by Forest" by Ji Feng and Zhi-Hua Zhou 2017 by Antoine Passemiers:  [Paper](https://arxiv.org/pdf/1709.09018.pdf) | [Code](https://github.com/AntoinePassemiers/Encoder-Forest)
