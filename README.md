# Computer Vision Project - HISDP
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/asiifkarim/Computer-Vision-project-HISDP-/blob/main/LICENSE)

This repository contains the **Facial Expression Recognition** project developed as part of the High Impact Skills Development Program (HISDP) for Gilgit Baltistan. The project leverages **deep learning** and **computer vision** techniques to classify facial expressions into seven basic categories using the **Expression in-the-Wild (ExpW)** dataset.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Project Overview
This project is focused on **facial expression classification** using deep learning techniques. The main goal is to build a model capable of recognizing human emotions from facial images, which can be useful in applications such as human-computer interaction, behavior analysis, and more.

The project is built with Python and utilizes popular deep learning frameworks such as **TensorFlow** and **Keras**. The model consists of **three convolutional layers**, followed by **max pooling layers** and a **dense layer**, achieving an accuracy of **76.64%** after 82 epochs of training.

## Dataset
The project uses the **Expression in-the-Wild (ExpW)** dataset, which contains **91,793** facial images annotated with seven basic expressions:
1. Angry
2. Disgust
3. Fear
4. Happy
5. Sad
6. Surprise
7. Neutral

The dataset is preprocessed to resize the images and normalize the pixel values for faster and more efficient training.

## Model Architecture
The model architecture is composed of:
- **Convolutional Layers:** Extracts features from the input images.
- **Max Pooling Layers:** Reduces the dimensionality of the features.
- **Dense Layer:** Maps the features to the output expression categories.

The detailed architecture can be found in the model definition file [model.py](https://github.com/asiifkarim/Computer-Vision-project-HISDP-/blob/main/model.py).

## Installation
To run the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/asiifkarim/Computer-Vision-project-HISDP-.git
   cd Computer-Vision-project-HISDP-
