# CycleGAN: Human to Animal Translation 

This project is a simple demonstration of using CycleGAN for unpaired image-to-image translation. It focuses on translating images of humans to animals using two small, custom datasets.

## Overview

CycleGAN allows training models to perform image translation between two domains (e.g., humans ↔ animals) without requiring paired images. This notebook uses a pre-existing PyTorch implementation and walks through the following steps:

- Mounting Google Drive and loading image datasets
- Unzipping and preparing the data
- Training a CycleGAN model on two datasets: human faces and animals
- Generating and visualizing results (e.g., human → animal transformation)
- Saving model checkpoints

## Results

Example outputs include visual transformations such as turning an image of Hermione Granger into a stylized animal. While the visuals are illustrative, this notebook is meant as a basic introduction rather than a production-quality implementation.

Note: The training here is limited in both scale and duration. As a result, the generated outputs may not be of high quality. This project is meant for educational purposes and code experimentation.

## Dataset

- The datasets (`faces.zip`, `cat_and_dog-1.zip`) were custom-created and loaded from Google Drive.
- Due to licensing and privacy considerations, they are not included in this repository.

## Requirements

This project is run using Google Colab, and depends on:
- PyTorch
- torchvision
- OpenCV
- matplotlib
- [`pytorch-CycleGAN-and-pix2pix`](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix)

## Acknowledgements

CycleGAN implementation from the official PyTorch repo:  
https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix

---

This notebook was created as part of my learning journey in deep learning and computer vision.
