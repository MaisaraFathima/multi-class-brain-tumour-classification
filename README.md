# Brain Tumor Classification using Deep Learning

## 📌 Overview

This project focuses on classifying brain MRI images into multiple tumor categories using deep learning. It helps in identifying different types of brain tumors based on image patterns.

##  Dataset

* Brain MRI images
* Multiple classes such as:

  * Glioma
  * Meningioma
  * Pituitary
  * No Tumor
* Images are organized into class-specific folders

##  Methodology

* Image preprocessing (resizing, normalization)
* Training using Convolutional Neural Networks (CNN)
* Multi-class classification using softmax output layer

##  Model

* Built using TensorFlow/Keras
* Learns complex visual features from MRI scans
* Capable of distinguishing between different tumor types

##  Results

The model can classify MRI images into multiple categories with good accuracy depending on dataset quality and training.

##  How to Run

1. Install dependencies
2. Open the notebook
3. Run all cells for training and evaluation

##  Files Included

* `brain_tumor_code(train).ipynb` → Model training notebook
* `brain_tumor_code(test).ipynb` → Model testing notebook
* `requirements.txt` → Python dependencies

##  Future Improvements

* Improve accuracy using advanced architectures (ResNet, EfficientNet)
* Add segmentation for tumor localization
* Deploy as a web-based diagnostic tool
