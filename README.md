# Image-Denoising-Using-Autoencoders-in-Keras-and-Python
An Autoencoder Model was built to denoise the input image and output a clear image. The output layer of an autoencoder has the same dimensionality as the inputs. The idea is to try to reconstruct each dimension exactly by passing it through the network.

The dataset used for training was the Fashion MNIST dataset available in Keras datasets having 60,000 images for training. Autoencoder was constructed in Python using Keras API with Tensorflow in Backend. The model was trained to output Denoised images when the given input is a noised image of (28 x 28 x 1) dimension.

Training Error: 0.296
Testing Error: 0.298
