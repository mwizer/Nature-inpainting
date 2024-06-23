# Nature Image Inpainting Project

## Table od Contents

- [Nature Image Inpainting Project](#nature-image-inpainting-project)
  - [Table od Contents](#table-od-contents)
  - [Project Description](#project-description)
  - [Dataset](#dataset)
  - [Problem Definition](#problem-definition)
  - [How to Start](#how-to-start)
  - [Explore Data](#explore-data)
  - [Notebooks Overview](#notebooks-overview)
    - [UNet.ipynb](#unetipynb)
    - [VAE.ipynb](#vaeipynb)
    - [DDPM.ipynb](#ddpmipynb)

## Project Description

The Nature Image Inpainting project aims to reconstruct missing fragments in images of nature to achieve coherent and realistic results. Missing fragments in images can be caused by damage, censorship, or other factors. This project focuses on filling these gaps in a way that preserves the original context of the images and maintains a natural appearance. Utilizing a dataset with over 100k images of nature across five classes, this project will develop and implement techniques for effective image inpainting.

## Dataset

**Name:** Nature

**Link:** [Nature Dataset on Kaggle](https://www.kaggle.com/datasets/heyitsfahd/nature)

**Description:** The dataset contains over 100k images of nature belonging to four classes. This diverse dataset provides a rich resource for training and evaluating image inpainting models.

## Problem Definition

**Task:**

- Fill in the gaps in the images to achieve a coherent and realistic result.

**Context:**

- Missing fragments may be caused by damage, censorship, or other factors. The aim is to reconstruct these fragments in a way that blends seamlessly with the rest of the image.

**Objectives:**

- Reconstruct the missing information.
- Preserve the image context.
- Achieve a natural and realistic appearance.

## How to Start

> [!NOTE]
> Supported Python versions: 3.10-3.12

1. **Clone the repository**
2. **Download the dataset:** [Nature](https://www.kaggle.com/datasets/heyitsfahd/nature)
3. **Unzip folders x64 or x128 into desired data folder inside project**
4. **Install the requirements**

   - If you have a GPU and want to use it:

   ```bash
   pip install -r requirements-gpu.txt
   ```

   - If you don't have a GPU or don't want to use it:

   ```bash
   pip install -r requirements-cpu.txt
   ```

  > [!NOTE]
  > It is recommended to run project using GPU. \
  > Please make sure that you have updated GPU drivers in case of running scripts locally

5. **Open prepare_data.ipynb notebook**
    - [Optional] Set your own path to data and size of image [64 or 128] that you want to process
6. **Run all cells in notebook to generate all required folders**
   - [Optional] You can generate pickle files to use for learning
7. **Select and run notebook with model that you want to train**
> [!IMPORTANT]
> Consider using Google Colab for training!  For this option, you'll need to utilize pickle files. Store them in your Google Drive and mount it at the start of each notebook you will use.

## Explore Data

To explore the data, go to the **EDA.ipynb** (Exploratory Data Analysis) file. This file contains analyses that will help you understand the dataset much better.

## Notebooks Overview

### UNet.ipynb

This notebook contains the implementation of the UNet model for image inpainting. It includes:

- Model implementation
- Training and evaluation
- Verification on ground truth images
- Display of model parameters
- Hyperparameter experiments

### VAE.ipynb

This notebook contains the implementation of the Variational Autoencoder (VAE) model for image inpainting. It includes:

- Model implementation
- Training and evaluation
- Verification on ground truth images
- Display of model parameters
- Hyperparameter experiments

### DDPM.ipynb

This notebook contains the implementation of a Denoising Diffusion Probabilistic Model (DDPM) for image inpainting. It includes:

- Model implementation
- Training and evaluation
- Verification on ground truth images
- Display of model parameters
- Hyperparameter experiments
