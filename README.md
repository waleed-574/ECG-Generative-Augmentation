# Extending the Nano Banana Pneumonia Study to ECG Images Using Multiple AI Models

## Project Overview
This project investigates whether AI-generated medical images can serve as viable data augmentation for deep learning models. Inspired by a study utilizing Nano Banana for synthetic pneumonia chest X-rays, this research extends the methodology into the **electrocardiogram (ECG)** domain. We systematically compare the augmentation quality of multiple generative AI models using a baseline Convolutional Neural Network (CNN).

## Repository Structure
* **data/raw/**: Source datasets containing text label data leakage.
* **data/cleaned/**: Preprocessed, masked images ready for training.
* **notebooks/**: Jupyter notebooks for preprocessing and training.
* **src/**: Core Python source scripts.