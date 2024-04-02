# TF-PyTorch-Jax-NN

In this repo, I create custom neural networks using the tensorflow, pytorch, and jax libraries commonly used for deep learning and experiment with differences in their low vs. high level API methods.

## Numpy Neural Network
### A non-linear (custom) Numpy Neural Network
I build a numpy only model having a 3-layer deep network for non linear regression. I'll be using a non linear activation function and identifying the proper number of hidden layer neurons by evaluating the results (loss and epochs training, prediction output). 

In this section, manual backprop and chain rule based gradient propagation will be used.

## Tensorflow Neural Networks

### Tensorflow Low-Level (custom) API Network using Matrix Multiply
In this section I built a Tensorflow model using the low level (functional/keras) api. A 3 layer deep non-linear Tensorflow neural network using a simple matrix multiplication in the custom forward method. 3 variables will be used in the non linear equation. Synthetically generated data will be processed with the non-linear equation and plotted using a 4d plot.

### Tensorflow High-Level API Network using Tensorflow Einsum
In this section I built a Tensorflow model using the high level tensorflow api. This 3-layer deep neural network will be using tensorflow's einsum instead of matrix multiplication in the forward method. A similar methodology will be used as in the low-level model (synthetically generated 3-dimensional data and 4-d plotting visual exploration and evaluation of the results)

## Jax Neural Network
Jax's high-level class-based API will be used to create a custom neural network.

## Pytorch Neural Networks
In this section, I use custom and built-in PyTorch methods to build non-linear regression models.

### Low-Level API
#### Non-linear custom Pytorch Neural Network
I build a custom non-linear pytorch neural network from scratch, having a 3-layer deep network, for linear regression 

In this section, PyTorch built-in layer functionality will not be used.

### High-Level API
#### A non-linear Pytorch API Neural Network
I build pytorch classes based - 3 layer deep neural network for non linear regression using pytorch builtin functionality of modules etc.,. backprop etc.,.


#### A non-linear Pytorch API Lightning Neural Network
A colab  pytorch lightening version of a classes based - 3 layer deep neural network for non linear regression using pytorch builtin functionality of modules etc.,. backprop etc.,.

## References

### References for Numpy numerical & non-linear Models using Tensorflow Einsum vs. Matrix Multiply

https://docs.google.com/presentation/d/1r0u-mOhrkDMRXkd4g2wgtbudZ2VCmCE0N3pTgTDWSw0/edit#slide=id.gbb803640d1_0_76 

https://colab.research.google.com/drive/1HS3qbHArkqFlImT2KnF5pcMCz7ueHNvY?usp=sharing&authuser=1#scrollTo=EGkS6nN6dQaz 

### References for low-level custom API networks with Tensorflow
https://colab.research.google.com/drive/1UCJt8EYjlzCs1H1d1X0iDGYJsHKwu-NO?authuser=1#scrollTo=KC5RgwGeBP-9

https://colab.research.google.com/drive/1UCJt8EYjlzCs1H1d1X0iDGYJsHKwu-NO?authuser=1#scrollTo=KC5RgwGeBP-9

https://colab.research.google.com/drive/1UCJt8EYjlzCs1H1d1X0iDGYJsHKwu-NO?authuser=1#scrollTo=WavMVtXGQk-z

### References for high-level API networks with Tensorflow

https://colab.research.google.com/drive/1UCJt8EYjlzCs1H1d1X0iDGYJsHKwu-NO?authuser=1#scrollTo=SyC7KfV-YcYS

https://colab.research.google.com/drive/169PfzM0kvtA5UP4k6Sl1yCG9tsE2MLia?authuser=1#scrollTo=C_2FyZeXjHd1

### References for high & low level APIs with PyTorch 
https://docs.google.com/presentation/d/13Oo5gXwcsoq9oMC4XriAyxkvgicatBxfI4cZzDhRyiE/edit#slide=id.g826a355833_0_525


https://colab.research.google.com/drive/1HS3qbHArkqFlImT2KnF5pcMCz7ueHNvY?usp=sharing&authuser=1#scrollTo=EGkS6nN6dQaz 
