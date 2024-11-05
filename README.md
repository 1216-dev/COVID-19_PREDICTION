# COVID-19_PREDICTION

Detection of COVID-19 Positive Cases Using Deep Learning leverages AI to classify chest X-ray images into categories: COVID-positive, lung opacity, normal, and viral pneumonia. This project aims to support healthcare providers with quick, accurate preliminary diagnoses, easing the strain on medical resources during high-demand periods.

## Project Overview

This project applies deep learning techniques to detect COVID-19 positive cases from chest X-ray images. By categorizing images as COVID-positive, lung opacity, normal, or viral pneumonia, this model aims to assist healthcare providers in identifying cases quickly and accurately.

![Sample X-Ray](https://github.com/1216-dev/COVID-19_PREDICTION/blob/main/download%20(3).png)

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Project Workflow](#project-workflow)
  - [1. Data Loading](#1-data-loading)
  - [2. Exploratory Data Analysis (EDA)](#2-exploratory-data-analysis-eda)
  - [3. Image Preprocessing and Augmentation](#3-image-preprocessing-and-augmentation)
  - [4. Model Building](#4-model-building)
  - [5. Model Training](#5-model-training)
  - [6. Model Evaluation](#6-model-evaluation)
  - [7. Grad-CAM Visualization](#7-grad-cam-visualization)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

---

## Dataset

The dataset is sourced from [COVID-19 Radiography Database on Kaggle](https://www.kaggle.com/tawsifurrahman/covid19-radiography-database), consisting of X-ray images classified into COVID, Normal, Lung Opacity, and Viral Pneumonia categories.

Project Workflow
1. Data Loading
The dataset of X-ray images is loaded, and images are labeled as either COVID or Normal. This process organizes the data into a structured format for easy access.

2. Exploratory Data Analysis (EDA)
EDA involves visualizing the data distribution for different classes. Count plots show the number of COVID-positive vs. negative cases, and sample images help understand image characteristics, which is essential for effective model training.

3. Image Preprocessing and Augmentation
Image preprocessing includes resizing and converting images to grayscale, with additional augmentations like rotation, brightness adjustment, and flipping. These steps improve model generalization and simulate varied conditions within the dataset.

4. Ben Graham's Method
Using Ben Graham's Method, images are converted to grayscale and smoothed with a Gaussian blur. This step reduces noise and highlights important structures in X-ray images, enabling the model to focus on relevant patterns associated with COVID-19.

5. Model Building
A Convolutional Neural Network (CNN) model is designed with layers for feature extraction and classification. The CNN leverages image patterns to classify X-rays, focusing on detecting features related to COVID-19.

6. Model Training
The model is trained on the dataset with validation monitoring to prevent overfitting. Techniques like early stopping and dropout regularization are used to enhance model performance, providing a balance between training and validation accuracy.

7. Model Evaluation
After training, the model’s performance is evaluated using metrics such as accuracy, recall, and F1 score on the test set. Confusion matrices give insights into classification accuracy across different classes.

8. Grad-CAM Visualization
Grad-CAM is used to generate heatmaps for COVID-positive and negative cases, highlighting areas in the X-rays where the model focuses to make its predictions. This step provides interpretability by showing which regions influenced the model’s decision.



Results
The model achieves high accuracy in differentiating between COVID-positive and negative cases, offering a potential tool for assisting radiologists in diagnosis. Below are the evaluation metrics:

Accuracy: 98%

Contributing
Contributions are welcome! Please fork this repository and submit a pull request with your changes


1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
