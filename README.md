# COVID-19_PREDICTION
Detection of COVID-19 Positive Cases Using Deep Learning leverages AI to classify chest X-ray images into categories: COVID-positive, lung opacity, normal, and viral pneumonia. This project aims to support healthcare providers with quick, accurate preliminary diagnoses, easing the strain on medical resources during high-demand periods. 
Detection of COVID-19 Positive Cases Using Deep Learning
This project applies deep learning techniques to detect COVID-19 positive cases from chest X-ray images. By categorizing images as COVID-positive, lung opacity, normal, or viral pneumonia, this model aims to assist healthcare providers in identifying cases quickly and accurately.
![Alt Text]((https://github.com/1216-dev/COVID-19_PREDICTION/blob/main/download%20(3).png))

# Detection of COVID-19 Positive Cases Using Deep Learning

This project applies deep learning techniques to detect COVID-19 positive cases from chest X-ray images. By categorizing images as COVID-positive, lung opacity, normal, or viral pneumonia, this model aims to assist healthcare providers in identifying cases quickly and accurately.

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
![Alt Text][(https://github.com/1216-dev/COVID-19_PREDICTION/blob/main/download%20(4).png)]

## Project Overview

This project leverages a deep learning-based classifier to automate the analysis of chest X-ray images, categorizing them into COVID-positive, lung opacity, normal, and viral pneumonia classes. Built using TensorFlow and Keras, the model uses convolutional neural networks (CNNs) to identify visual patterns in X-rays, potentially aiding radiologists in diagnostic decision-making.

## Dataset

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
pip install -r requirements.txt


The dataset is sourced from [COVID-19 Radiography Database on Kaggle](https://www.kaggle.com/tawsifurrahman/covid19-radiography-database), consisting of X-ray images classified into COVID, Normal, Lung Opacity, and Viral Pneumonia categories. 


