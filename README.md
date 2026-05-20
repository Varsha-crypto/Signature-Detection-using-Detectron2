# Signature-Detection-using-Detectron2

## Overview

Developed a deep learning-based document signature detection system using **Detectron2 (PyTorch)** for object localization and computer vision inference tasks.
The model was trained on a custom annotated dataset to accurately detect and localize signature regions in document images.

---

## Features

* Signature detection and localization in documents
* Custom object detection model using Detectron2
* Bounding box prediction and visualization
* GPU-accelerated training with CUDA
* End-to-end training and inference pipeline
* Custom dataset annotation using Roboflow

---

## Tech Stack

* Python
* PyTorch
* Detectron2
* OpenCV
* Roboflow
* CUDA GPU Acceleration

---

## Workflow

1. Dataset annotation using Roboflow
2. Data preprocessing and augmentation
3. Model configuration and training
4. Bounding box localization
5. Model evaluation and validation
6. Inference on unseen document images
7. Prediction visualization

---

## Model Training

* Configured Detectron2 object detection architecture
* Tuned hyperparameters for signature localization
* Used custom annotated datasets for training
* Enabled GPU acceleration using CUDA for faster convergence

---

## Inference Pipeline

Implemented an inference workflow to:

* Detect signature regions from new documents
* Generate bounding box predictions
* Visualize detections for validation
* Improve localization accuracy

---

## Key Contributions

* Built an end-to-end document signature detection pipeline
* Trained and optimized Detectron2 models on custom datasets
* Developed preprocessing and inference workflows
* Implemented bounding box visualization for validation
* Optimized training performance using CUDA-enabled GPUs

---

## Future Improvements

* Multi-signature detection support
* Lightweight deployment using ONNX/TensorRT
* Real-time document verification API
* Integration with OCR pipelines
* Improved detection on low-quality scanned documents

---

## Use Cases

* Document verification systems
* Automated contract processing
* Banking and KYC workflows
* Digital document authentication
* Enterprise document management systems
