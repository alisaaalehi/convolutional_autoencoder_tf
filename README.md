# Convolutional Autoencoder

### What is this?
 A tensorflow implementation of an autoencoder. In its simplest form, it has just one convolutional layer for encoding the input image and one deconvolution layer (or inverse or transpose convolution or whatever that you would like to call it).

### What is the purpose?
Having a simple network so I can take a look at the trained filters of the convolution and deconvolution parts of the network.

### Why are you using tf.name_scope() everywhere?
To have a simple and easy to understand summary results in the tensorboard. 

### What can be done more?
You can easily make the network deeper. I am training on the MNIST dataset, you can use it to train on other image datasets. I didn't use it for tasks like image denoising, you can pass the noisy images as input and original images as the target, and let the network to learn the denoising task.

### Have you written all of the codes?
No, I didn't. Some parts are from tensorflow tutorials and some of the functions from other's projects (with some modifications)

### Which libraries are used?
* tensorflow 1.9.0
* python 2.7.12
* tensorboard 1.11.0a0

