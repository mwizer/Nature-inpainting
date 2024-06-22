# Nature Image Inpainting Project

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

1. **Clone the repository**
2. **[Download the dataset](https://www.kaggle.com/datasets/heyitsfahd/nature)**
3. **Install the requirements / pip install -r requirements.txt**
4. Maciek tutaj ten poradnik z instalką zdjęc do pickli

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

This notebook contains the implementation of a Diffusion model for image inpainting. It includes:

- Model implementation
- Training and evaluation
- Verification on ground truth images
- Display of model parameters
- Hyperparameter experiments
