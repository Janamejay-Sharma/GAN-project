## Introduction

Generative Adversarial Networks (GANs) are a machine learning and AI innovation developed in 2014 by Ian Goodfellow and colleagues. GANs have gained popularity for their prowess in creating intricate and realistic data, spanning images, music, and text.

GANs consist of two neural networks:

- **Generator**, responsible for crafting data resembling real examples.
- **Discriminator**, which assesses authenticity by distinguishing real from generated samples.

The continuous interplay between these networks fosters a competitive learning process where the generator strives to outwit the discriminator, ultimately aiming to produce data indistinguishable from reality. This achievement has widespread applications in image synthesis, style transfer, super-resolution, and more.

This implementation of a GAN will be trained on a Tensorflow dataset of fashion item images. The goal is to have the generator trained to level where it can create images similar to the originals in the dataset.
