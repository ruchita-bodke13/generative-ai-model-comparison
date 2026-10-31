# Comparative Study of Generative AI Models

This repository contains the practical work for Assignment 02. It compares
four generative AI models:

- Autoencoder (AE)
- Variational Autoencoder (VAE)
- Deep Convolutional Generative Adversarial Network (DCGAN)
- Pretrained Diffusion Model

## Objective

The objective is to study image reconstruction using AE and VAE, and image
generation using DCGAN and a pretrained Diffusion Model. The experiments
compare their working principles, outputs, advantages, limitations, and
applications.

## Repository contents

- `notebooks/generative_ai_comparison.ipynb` — Colab notebook with the
  experiments and code.
- `report/assignment_report.md` — comparative study, output analysis, and
  reflection.
- `results/` — screenshots of the original, reconstructed, and generated
  images.

## Experiments

### Image reconstruction

The notebook trains an Autoencoder and a Variational Autoencoder on CIFAR-10.
The same test images are used to compare the reconstructed outputs.

### Image generation

The notebook trains a DCGAN on CIFAR-10 and uses a pretrained Diffusion Model
to generate an image from a text prompt.

## Run the notebook

1. Open the notebook in Google Colab.
2. Select a GPU runtime if one is available.
3. Run the cells in order.
4. Save screenshots of the original images, reconstructions, and generated
   outputs in `results/`.

The notebook downloads CIFAR-10 automatically. The Diffusion Model may require
additional download time and access to its model files.

## Requirements

See `requirements.txt`. Google Colab already includes PyTorch and torchvision.
The Diffusion Model section installs its additional libraries in the notebook.

## Results

Add screenshots and a short description of your observations in `results/`.
Describe what your own outputs show, including visible detail, blur, distortion,
variety, and prompt alignment.
