# Food Detection Application

This project is a food detection application that identifies various food items from images and provides their names as output. It leverages deep learning techniques to accurately recognize food items, assisting users in tasks such as dietary tracking and meal logging.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Installation](#installation)
- [Results](#results)

## Introduction

The goal of this project is to develop a robust model capable of detecting and classifying multiple food items within an image. This can be particularly useful for applications in health monitoring, dietary assessment, and culinary content analysis.

## Features

- Detects multiple food items in a single image.
- Provides the names of identified food items.
- High accuracy with real-time processing capabilities.

## Dataset

The model is trained on the [Food-101 dataset](https://www.kaggle.com/dansbecker/food-101), which consists of 101,000 images across 101 food categories. Each category contains 1,000 images, providing a diverse set of food items for robust model training.

## Model Architecture

The application utilizes a Convolutional Neural Network (CNN) based architecture for image classification. Specifically, the ResNet50 model pre-trained on ImageNet is fine-tuned on the Food-101 dataset to leverage transfer learning for improved accuracy.

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/satyavenkat2011/PRODIGY_ML_05.git
   cd PRODIGY_ML_05
## Results

The model achieves an accuracy of approximately 85% on the Food-101 test set. Below are some sample detections:

 Sample Detection 1.
 
  ![image](https://github.com/user-attachments/assets/4dcbb457-bc1c-4242-bf17-3f9fe5ba1691)

 Sample Detection 2.
 
  ![image](https://github.com/user-attachments/assets/98265c84-3b7a-48d8-913e-13056e687ad5)
  
 Sample Detection 3.
 
  ![image](https://github.com/user-attachments/assets/348e40fb-ab45-4283-80e3-41cc8e967605)

  
  
