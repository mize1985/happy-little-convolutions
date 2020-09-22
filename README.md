# Happy Little Convolutions: _the Joy of Neural Nets_

---

This folder contains files used for building and training a photo-to-Bob-Ross CycleGAN, based on the photo-to-Monet
CycleGAN in [this article](https://medium.com/analytics-vidhya/transforming-the-world-into-paintings-with-cyclegan-6748c0b85632)
and a closely related GAN for the purpose of upscaling the Bob Ross output of the CycleGAN from 256x256 to 1024x1024.

## CycleGAN.ipynb

Builds and trains a CycleGAN on Bob Ross data. Data is not included here, but is intended to be posted online.

## Upscaler.ipynb

Builds and trains a GAN to fill in details according to Bob Ross's style on 256x256 images of paintings bicubically scaled to 1024x1024.

## Plot.ipynb

Was used to produce a plot of different artists internet popularity.

## multiTimeline.csv

Contains Google search trend data for various painters.

## Happy_Little_Convolutions.pdf

Contains a slide deck used in presenting this project.
