# Industrial Surface Defect Detection

**A Reproducible Benchmark of YOLOv8n and YOLO26n for Steel Surface Visual Inspection**

## 1. Project Overview

This project aims to develop a reproducible deep learning-based computer vision pipeline for detecting and localizing surface defects in steel materials.

The project focuses on comparing YOLOv8n and YOLO26n for automated visual quality inspection, emphasizing detection performance, error analysis, and computational efficiency.

The implementation follows an engineering-oriented workflow covering dataset preparation, model development, evaluation, experiment tracking, and inference optimization.

- **Project Type:** Computer Vision Engineering Portfolio
- **Application Domain:** Industrial Manufacturing & Quality Control
- **Task:** Object Detection
- **Status:** In Development

## 2. Problem Statement

Surface defects in steel manufacturing can affect product quality and require reliable visual inspection.

Detecting these defects can be challenging due to variations in their shape, size, texture, and visual contrast. Manual inspection may also be affected by operator fatigue, inconsistencies, and production throughput requirements.

Deep learning-based object detection offers a potential approach to support automated visual inspection. However, detection accuracy alone is insufficient for assessing the suitability of a model for industrial applications.

This project investigates the detection performance, error characteristics, and inference efficiency of YOLOv8n and YOLO26n under reproducible experimental conditions using a publicly available dataset.

The intended outcome is an engineering-oriented prototype rather than a production-validated inspection system.

## 3. Project Objectives

The primary objectives are:

1. Develop a reproducible dataset preparation and validation pipeline.
2. Implement and evaluate YOLOv8n as the baseline object detection model.
3. Compare YOLOv8n and YOLO26n under controlled experimental conditions.
4. Evaluate detection performance using precision, recall, mAP50, and mAP50-95.
5. Conduct class-specific error analysis and investigate false positive and false negative predictions.
6. Evaluate inference efficiency through latency, throughput, and model size.
7. Export and benchmark trained models using ONNX Runtime.
8. Document technical decisions, experimental results, and system limitations.

## 4. Dataset

**Planned Dataset:** NEU-DET (Northeastern University Surface Defect Database)

The dataset covers six steel surface defect categories:

- Crazing
- Inclusion
- Patches
- Pitted Surface
- Rolled-in Scale
- Scratches

Dataset acquisition, annotation validation, integrity checking, and train/validation/test split preparation have not yet been performed.

## 5. Planned Methodology

The project will follow these development stages:

| Stage | Description |
|---|---|
| 1. Environment Setup | Configure the development environment and version control |
| 2. Dataset Engineering | Validate annotations, inspect class distributions, and prepare reproducible data splits |
| 3. Baseline Development | Train and evaluate YOLOv8n |
| 4. Comparative Experiments | Train and evaluate YOLO26n under comparable conditions |
| 5. Error Analysis | Investigate class-specific performance and detection failures |
| 6. Inference Optimization | Export models to ONNX and benchmark inference performance |
| 7. Documentation | Prepare technical reports, visualizations, and a demonstration |

## 6. Development Environment

### Hardware

- **Laptop:** Lenovo Legion Y545
- **GPU:** NVIDIA GeForce RTX 2060 (6 GB VRAM)
- **RAM:** 16 GB
- **Storage:** Samsung T7 Shield 1 TB External SSD

### Software

- **Operating System:** Windows 10
- **Python:** 3.11.9
- **Git:** 2.56.0.windows.2
- **IDE:** Visual Studio Code

### Planned Technologies

- PyTorch
- Ultralytics YOLO
- OpenCV
- NumPy
- MLflow
- ONNX Runtime
- pytest

Dependencies and exact package versions will be finalized after environment compatibility testing.

## 7. Project Status

**Current Phase: Sprint 1A — Project Initialization**

### Completed

- [x] Python installation
- [x] Git installation
- [x] Visual Studio Code installation
- [x] Hardware and software inspection

### Pending

- [ ] Git repository initialization and first commit
- [ ] Python virtual environment setup
- [ ] PyTorch installation and CUDA verification
- [ ] Ultralytics environment verification
- [ ] Dataset acquisition and initial audit

Model training and experimental evaluation have not yet started.

## 8. Limitations

This project is currently in the initialization stage. No experimental performance results are available.

The planned prototype will use a publicly available steel surface defect dataset. Its results should not be interpreted as evidence of readiness for deployment in a real manufacturing production line.
