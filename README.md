# AI_GAN_facegenerator

# Project Overview

In this project I wanted to create images of faces with a neural network. The project showcases the use of a generative 
adversarial network. A generator network is producing images and a discriminator is evaluating the generated images with
comparison to real images.

# Packages

For this jupyter notebook to run you need these common packages: Pyhton 3.6, jupyter notebook, numpy, matplotlib, tensorflow.

# Files

face_generation.ipynb: a jupyter notebook explaning the whole algorithm to generate the images

helper.py: python file with function for loading the data and get metadata of the images.

problem_unittests.py: python file to test the single function that are created for building and training the network.


# Conclusion, Findings

The final discriminator_loss: 0.6924 and generator_loss: 1.3721 are better visually interpreted as you can clearly recognize
the faces that are created

# Licensing, Authors, Acknowledgements

This repository is licensed under the MIT-License. Big thanks to udacity for providing the data and the code to start.
