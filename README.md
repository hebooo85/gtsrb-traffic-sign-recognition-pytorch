
Deep Learning_ Based German Traffic Sign Recognition Using PyTorch (Custom CNN, Autoencoder, DCGAN).

# German Traffic Sign Recognition Using Deep Learning with PyTorch

This repository contains the final project for **INFO 6147 – Deep Learning with PyTorch** at Fanshawe College.

## Project Overview

- Dataset: **GTSRB – German Traffic Sign Recognition Benchmark** (43 traffic sign classes).
- Models:
  - Custom CNN classifier (TrafficSignCNN).
  - Denoising Autoencoder for robust feature learning and noise removal.
  - DCGAN for synthetic traffic sign generation and data augmentation.
- Final test accuracy of the CNN: **~99.4%** on 43 classes.
- Implementation: Pure **PyTorch**, trained in Google Colab.

## Files in this repository

- Jupyter notebooks:
  - `gtsrb_cnn.ipynb` – Data loading, preprocessing, baseline CNN, final CNN, evaluation.
  - `gtsrb_autoencoder.ipynb` – Denoising autoencoder training and visual results.
  - `gtsrb_dcgan.ipynb` – DCGAN training and generated samples.
- `GTSRB_IEEE_Report.pdf` – IEEE-style project report (max 4 pages).
- `GTSRB_Presentation_Final.pptx` – Final presentation slides.
- Figures (PNG images) – Training curves, confusion matrix, autoencoder and DCGAN outputs.

## Requirements

- Python 3.x
- PyTorch, torchvision
- NumPy, Matplotlib, Seaborn

- ### Demo Video
  
You can watch the full demo video here:
[Click to Watch Demo](https://1drv.ms/v/c/a3bbb7d0adbdbbb2/EZ66GjVVSjpJkXyyvEsjN9gBVtmFTPwXi3ICOU6fWzfRpQ?e=efpjAc)


