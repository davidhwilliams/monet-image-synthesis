# Monet Image Synthesis

This repository contains the Jupyter notebook for building, training, and evaluating a CycleGAN model that translates images between two domains—specifically, transforming Monet paintings into photos and vice versa.

## Overview

The project demonstrates how to:

- Construct U-Net style generators with skip connections for detailed image translations.
- Build discriminators that progressively extract features through downsampling.
- Combine adversarial, cycle consistency, and identity losses to enforce robust and realistic domain translation.
- Utilize TensorFlow and Keras, along with distributed training strategies, to improve performance.

## Requirements

- Python 3.x
- TensorFlow 2.x
- Keras
- Jupyter Notebook
