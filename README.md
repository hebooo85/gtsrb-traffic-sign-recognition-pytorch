# gtsrb-traffic-sign-recognition-pytorch
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

## How to run (short version)

1. Open the notebook in Google Colab or Jupyter.
2. Download the **GTSRB** dataset (balanced version) and update the dataset path if needed.
3. Run all cells to:
   - Prepare train/validation/test splits.
   - Train the baseline CNN.
   - Apply augmentation and regularization to train the final CNN.
   - Evaluate on the test set and generate plots.
