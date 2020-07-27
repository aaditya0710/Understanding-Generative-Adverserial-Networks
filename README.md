# Understanding-Generative-Adverserial-Networks
GAN is an unsupervised deep learning algorithm where we have a Generator pitted against an adversarial network called Discriminator.
Both Generator and Discriminator will be multi-layer perceptrons(MLP)
# Deep Convolutional Generative-Adverserial-Networks (DCGAN's)
DCGAN is one of the most popular and successful network design for GAN. It mainly composes of convolution layers without max pooling or fully connected layers. It uses convolutional stride and transposed convolution for the downsampling and the upsampling. It takes a noise vector as the input in order to diversify the potential outputs. This vector is reshaped into a structure with an important number of channels, followed by a succession of convolutional layers that will reduce the depth and form a pattern in the other dimensions until we are able to obtain the output, for a colorized image
