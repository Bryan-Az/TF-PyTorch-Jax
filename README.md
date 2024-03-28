# TF-PyTorch-Jax

In this repo, I will create custom neural networks using the tensorflow, pytorch, and jax libraries commonly used for deep learning.

## Tensorflow Neural Networks

References: 
https://docs.google.com/presentation/d/1r0u-mOhrkDMRXkd4g2wgtbudZ2VCmCE0N3pTgTDWSw0/edit#slide=id.gbb803640d1_0_76 (Course resource)

https://colab.research.google.com/drive/1HS3qbHArkqFlImT2KnF5pcMCz7ueHNvY?usp=sharing&authuser=1#scrollTo=EGkS6nN6dQaz (Colab resource)

### Tensorflow High-Level (class-based) API Networks

Colab References: 

https://colab.research.google.com/drive/1UCJt8EYjlzCs1H1d1X0iDGYJsHKwu-NO?authuser=1#scrollTo=SyC7KfV-YcYS

https://colab.research.google.com/drive/169PfzM0kvtA5UP4k6Sl1yCG9tsE2MLia?authuser=1#scrollTo=C_2FyZeXjHd1

#### A linear Tensorflow Neural Network
A 3 layer deep neural network using matrix multiply.

#### A non-linear Tensorflow Neural Network
A 3 layer deep neural network using tensorflow einsum instead of matrix multiply. 3 variables will be using in the non linear equation. Synthetically generated data will be processed with the non-linear equation and plotted using a 4d plot.

#### A non-linear (custom) Numpy Neural Network
I build a numpy only model having a 3-layer deep network for non linear regression. I'll be using a non linear activation function and identifying the proper number of hidden layer neurons by evaluating the results (loss and epochs training, prediction output). 

> In this section, manual backprop and chain rule based gradient propagation will be used.

#### Tensorflow Low-Level (custom) API Network

In this section I built a Tensorflow model built using the low level (functional) api.

Colab References: 
https://colab.research.google.com/drive/1UCJt8EYjlzCs1H1d1X0iDGYJsHKwu-NO?authuser=1#scrollTo=KC5RgwGeBP-9

https://colab.research.google.com/drive/1UCJt8EYjlzCs1H1d1X0iDGYJsHKwu-NO?authuser=1#scrollTo=KC5RgwGeBP-9

https://colab.research.google.com/drive/1UCJt8EYjlzCs1H1d1X0iDGYJsHKwu-NO?authuser=1#scrollTo=WavMVtXGQk-z



## Jax Neural Network

Jax's high-level class-based API will be used to create a custom neural network.


## Pytorch Neural Networks
In this section, I use custom and built-in PyTorch methods to build non-linear regression models.


References: 
https://docs.google.com/presentation/d/13Oo5gXwcsoq9oMC4XriAyxkvgicatBxfI4cZzDhRyiE/edit#slide=id.g826a355833_0_525 (Course resource)


https://colab.research.google.com/drive/1HS3qbHArkqFlImT2KnF5pcMCz7ueHNvY?usp=sharing&authuser=1#scrollTo=EGkS6nN6dQaz (Colab resource)

### A non-linear (custom) Pytorch Neural Network
I build a custom non-linear pytorch neural network from scratch, having a 3-layer deep network, for linear regression 

> In this section, PyTorch built-in layer functionality will not be used.

 
### A non-linear (classes-based) Pytorch Neural Network
I build pytorch classes based - 3 layer deep neural network for non linear regression using pytorch builtin functionality of modules etc.,. backprop etc.,.


### A non-linear (classes-based) Pytorch Lightning Neural Network
A colab  pytorch lightening version of a classes based - 3 layer deep neural network for non linear regression using pytorch builtin functionality of modules etc.,. backprop etc.,.
