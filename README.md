# Polyp Segmentation using U-Net++

Medical image segmentation plays an important role in computer-aided diagnosis. This project focuses on segmenting polyps from colonoscopy images using a U-Net++ deep learning architecture built with PyTorch.

The goal is to generate accurate polyp masks from endoscopic images and support medical image analysis workflows with a practical deep learning pipeline.

## Overview

Polyp segmentation helps identify abnormal tissue regions in colonoscopy frames. In this project, a U-Net++ model is trained on colonoscopy image data along with corresponding ground-truth masks to learn pixel-wise segmentation.

This repository includes dataset organization, source code, reference materials, and output folders for experiments and predictions.

## Dataset

This project uses colonoscopy image data from the CVC-ClinicDB dataset. The dataset contains:

- Original colonoscopy frames
- Ground-truth segmentation masks
- Data available in both PNG and TIFF formats

## Objective

The main objective of this project is to build a robust deep learning model for polyp segmentation and understand the full workflow of a medical image segmentation task, from data preparation to model prediction.

## Tech Stack

- Python
- PyTorch
- OpenCV
- NumPy
- Pandas
- Scikit-learn
- Albumentations

## Workflow

The project covers the following steps:

1. Dataset understanding and preprocessing
2. Evaluation metric understanding, including IoU
3. U-Net architecture basics
4. U-Net++ architecture exploration
5. Environment setup
6. Data augmentation
7. Model building with PyTorch
8. Model training
9. Prediction and output generation

## Project Structure

- `data/`
  Contains the dataset in PNG and TIFF formats.

- `Code/input/`
  Input data used by the training and segmentation pipeline.

- `Code/source/`
  Core source code for preprocessing, model development, training, and inference.

- `Code/output/`
  Stores generated outputs such as model results, predictions, or saved artifacts.

- `Code/lib/`
  Reference materials and notebook-based exploratory work.

- `README.md`
  Project documentation and setup instructions.

## Learning Outcomes

This project helped build understanding in the following areas:

- Medical image segmentation
- Intersection over Union (IoU) metric
- Data augmentation for computer vision
- Practical PyTorch workflows
- OpenCV for image processing
- CNN-based segmentation models
- U-Net and U-Net++ architecture
- Training deep learning models for medical imaging tasks

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/srinivaspenumarthi/Image-Segmentation-DL-Project.git
cd Image-Segmentation-DL-Project
