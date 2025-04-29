# Vehicle Damage Detection

This repository contains a deep learning model for classifying vehicle damage into three categories: **minor**, **moderate**, and **severe**. The model is trained using the **InceptionV3** architecture, which is pre-trained on ImageNet, and fine-tuned for vehicle damage classification. The goal is to predict the severity of vehicle damage based on an input image and provide an estimated repair cost for each category.

## Table of Contents

- [Project Description](#project-description)
- [Dataset](#dataset)


## Project Description

This project uses a convolutional neural network (CNN) built on top of the **InceptionV3** model, leveraging transfer learning. The model is trained on a dataset of vehicle damage images, which is divided into **training**, **validation**, and **test** sets.

- **Minor Damage**: Small scratches, dents, or minor cracks.
- **Moderate Damage**: Larger dents, moderate scratches, or cracks.
- **Severe Damage**: Extensive damage, large cracks, or broken parts.

## Dataset

The dataset used in this project is located in the `data3a` directory, which contains the following folders:
- `training`: Training images for model training.
- `validation`: Validation images for model validation.
- `test`: Test images to evaluate the final model.

The images are labeled into three categories: `01-minor`, `02-moderate`, and `03-severe`.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ayeshaakram88/Vehicle-Damage-Detection.git
   cd Vehicle-Damage-Detection
